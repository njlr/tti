include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-tti',
  header_only = True,
  header_namespace = 'boost/tti',
  exported_headers = subdir_glob([
    ('include/boost/tti', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
