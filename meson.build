project('fast-io', 'cpp', default_options: ['cpp_std=c++20'])

# Support both layouts: headers at repo root or under 'include/'
inc = include_directories('.', 'include')

fast_io_dep = declare_dependency(
  include_directories: inc
)

set_variable('fast_io_dep', fast_io_dep)
