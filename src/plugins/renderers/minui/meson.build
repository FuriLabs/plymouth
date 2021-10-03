minui_plugin = shared_module('minui',
  sources: [
    'plugin.c',
    'core/graphics.c',
    'core/graphics_fbdev.c',
    'core/events.c',
    'core/resources.c',
    'core/graphics_drm.c'
  ],
  dependencies: [
    libply_dep,
    libply_splash_core_dep,
    libdrm_dep,
  ],
  include_directories: config_h_inc,
  name_prefix: '',
  install: true,
  install_dir: plymouth_plugin_path / 'renderers',
)
