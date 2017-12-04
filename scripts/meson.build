in_scripts = [
  'announce-release',
  'distribute-release',
]

foreach script : in_scripts
  gen = configure_file(input : script + '.in',
                       output : script,
                       configuration : conf)

  install_data(gen,
               install_dir : get_option('bindir'))
endforeach
