i18n = import('i18n')

i18n.gettext(
  meson.project_name(),
  preset: 'glib',
  # Page width is set to 90 characters in order to avoid bad wrapping of the
  # bug reporting address.
  args: ['--msgid-bugs-address=https://gitlab.freedesktop.org/pipewire/wireplumber/issues/new',
         '--width=90', '--keyword=I18n.gettext:1', '--keyword=I18n.ngettext:1,2']
)

po_dir = meson.current_source_dir()
