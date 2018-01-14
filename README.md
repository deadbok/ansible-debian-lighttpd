# Ansible role to install lighttpd

## Compatibility

 * Debian 9 (stretch)

## Variables

 * **lighttpd_state** (*started/stopped*): State of the lighttpd server
 * **lighttpd_restart_state** (*restarted/reloaded*): State to enforce when the lighttpd configuration changes.
 * **lighttpd_packagess_state** (*installed/latest*): Whether to make sure the latest lighttpd package is installed.
 * **lighttpd_modules** = (*list of module names*): Lighttpd modules to enable
 * **lighttpd_site_root** = (*path*): Path to the web site root files.
