material_schemas = [
    'com.worldwidemann.plotinus.gschema.override',
    'org.gnome.desktop.background.gschema.override',
    'org.gnome.desktop.interface.gschema.override',
    'org.gnome.desktop.screensaver.gschema.override',
    'org.gnome.desktop.wm.preferences.gschema.override',
    'org.gnome.nautilus.icon-view.gschema.override',
    'org.gnome.nautilus.list-view.gschema.override',
    'org.gnome.nautilus.preferences.gschema.override',
    'org.gnome.settings-daemon.plugins.xsettings.gschema.override',
    'org.gnome.shell.extensions.dash-to-dock.gschema.override',
    'org.gnome.shell.extensions.topicons.gschema.override',
    'org.gnome.shell.extensions.user-theme.gschema.override',
    'org.gnome.shell.gschema.override',
]

custom_target('20_gnome_material_settings.gschema.override',
    output: '20_gnome_material_settings.gschema.override',
    capture: true,
    input: material_schemas,
    command: ['cat', '@INPUT@'],
    install: true,
    install_dir: path_schemadir,
)
