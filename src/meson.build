textnotes_sources = [
  'main.c',
  'textnotes-application.c',
  'textnotes-window.c',
]

textnotes_deps = [
  dependency('gtk4'),
  dependency('libadwaita-1', version: '>= 1.4'),
]

textnotes_sources += gnome.compile_resources('textnotes-resources',
  'textnotes.gresource.xml',
  c_name: 'textnotes'
)

executable('textnotes', textnotes_sources,
  dependencies: textnotes_deps,
       install: true,
)
