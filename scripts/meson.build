in_scripts = [
  'announce-release',
  'distribute-release',
  'gen-icon-theme',
  'totoconf',
]

foreach script : in_scripts
  gen = configure_file(input : script + '.in',
                       output : script,
                       configuration : conf)

  install_data(gen,
               install_dir : get_option('bindir'))
endforeach
