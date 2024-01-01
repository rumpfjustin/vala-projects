project('daily-tasker', ['c', 'vala'],
  version : '0.1')

dependencies = [
    dependency('glib-2.0'),
    dependency('gobject-2.0'),
    dependency('gtk4')
]

exe = executable('DailyTasker', 'DailyTasker.vala', dependencies : dependencies,
  install : true)

test('basic', exe)
