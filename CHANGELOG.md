# Changelog

### Admin Panel Unique addon **[WHMCS](https://puqcloud.com/link.php?id=77)**
##### [Order now](https://puqcloud.com/store/whmcs-addon-modules) | [Download](https://download.puqcloud.com/WHMCS/addons/PUQ_WHMCS-Admin-Panel-Unique/) | [FAQ](https://community.puqcloud.com/)

## v1.0 — 2026-03-10

First release.

### New Features

- Dashboard page with current configuration overview (module info, customization status, dark mode status, active preset, current colors)
- Configuration page with modern card-based UI for all appearance settings
- Global enable/disable switch for all admin panel customization styles
- Dark mode toggle for admin interface surfaces
- 20 built-in theme presets with one-click apply
- 10 individual color controls for key admin UI elements
- Real-time live preview of pending changes before save
- CSRF protection on configuration save requests
- HEX color format validation before writing settings
- Safe PRG save flow (redirect after POST to prevent duplicate submissions)
- Automatic CSS injection into WHMCS admin area via `AdminAreaHeadOutput` hook
- License verification system with online/offline validation logic
- Configuration page locked when license is invalid; Dashboard remains accessible
- License warning banner inside module pages
- Additional license alert on WHMCS admin homepage via `AdminHomepage` hook
- Multilingual support with automatic admin language detection and fallback to English
- Persistent settings storage in `mod_puq_admin_panel_unique_config`
