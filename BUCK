include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-endian',
  header_only = True,
  header_namespace = 'include/boost/endian',
  exported_headers = subdir_glob([
    ('include/boost/endian', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
