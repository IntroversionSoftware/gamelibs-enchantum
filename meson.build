project(
    'enchantum', ['cpp'],
    default_options: ['cpp_std=c++17'],
    version: '0.3.0',
)

enchantum_include = include_directories('enchantum/include')

enchantum_args = []

enchantum_dep = declare_dependency(
    include_directories: enchantum_include,
    compile_args: enchantum_args,
)

meson.override_dependency('enchantum', enchantum_dep)
