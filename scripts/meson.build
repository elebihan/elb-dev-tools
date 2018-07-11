in_scripts = [
  'announce-release',
  'br2-gdb',
  'distribute-release',
  'gen-icon-theme',
  'scribble-release',
  'totoconf',
  'usage2mdman',
]

foreach script : in_scripts
  gen = configure_file(input : script + '.in',
                       output : script,
                       configuration : conf)

  install_data(gen,
               install_dir : get_option('bindir'))
endforeach
