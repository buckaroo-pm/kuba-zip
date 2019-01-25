load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'miniz',
  exported_headers = subdir_glob([
    ('src', '*.h')
  ]),
  visibility = ['PUBLIC']
)
