demo_sources = [
  'main.c',
  'demo-application.c',
  'demo-window.c',
]

demo_deps = [
  dependency('gtk4'),
]

demo_sources += gnome.compile_resources('demo-resources',
  'demo.gresource.xml',
  c_name: 'demo'
)

executable('demo', demo_sources,
  dependencies: demo_deps,
       install: true,
)
