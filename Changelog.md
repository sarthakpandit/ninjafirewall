# Changelog #

### v1.1.0 ###

`[*] better XSS detection (UTF-7 encoding, BBcode etc).`

`[*] improved processing speed.`

`[+] security ruleset update.`

`[!] fixed an issue where IP:port in Host header was not detected.`

`[!] stats page wasn't showing the right number of banned IPs (Pro edn).`

`[!] fixed some tiny bugs and typo.`

### v1.0.9 ###

`[+] security ruleset update.`

`[!] fixed incorrect DOCUMENT_ROOT variable on some servers.`

### v1.0.8 ###

`[+] added stats from previous months in the 'Statistics' page.`

`[+] timezone can be set up in the 'Account/Options' menu.`

`[+] security ruleset update.`

`[+] added 'hooked PHP script' to the debug console.`

`[+] added isset($log_db_err) to the firewall to prevent potential`

`    PHP warning message.`

`[!] increased line-height value in CSS. Buttons looked too small when`

`    using either Chrome or Safari browsers.`

`[!] HTTP return code writes '200 OK' to log when sanitizing a value`

`    instead of a wrong '403 Forbidden' message.`

### v1.0.7 ###

`[+] security ruleset update.`

`[+] added 'From:' header to alerts sent by email.`

### v1.0.6 ###

`[+] added IPv4-mapped IPv6 addresses support to the whitelist.`

`[*] leading quotes in GET/POST as well as CR/LF in cookies, referrer`

`    and user-agent variables are now blocked rather than sanitised.`

`[+] added session_write_close() when redirecting from the login page`

`    to the index one to prevent potential PHP lost sessions.`

`[+] security ruleset update.`

### v1.0.5 ###

`[+] tighten rules to better block some nasty obfuscated code injection`

`    attempts.`

`[!] fixed regression introduced in ruleset 12.02.23 that could break`

`    some WordPress themes.`

`[!] fixed a bug in the stats page that would display crazy averages.`

### v1.0.4 ###

`[*] better filtering of multidimensional arrays in GET/POST requests.`

`[-] useless insensitive matching mode removed from a regex.`

`[+] X_FORWARDED_FOR strict verification to prevent XSS and injections.`

### v1.0.3 ###

`[+] option to block Linux binary files upload (ELF).`

`[+] option to sanitise PHP_SELF, PATH_TRANSLATED and PATH_INFO.`

### v1.0.2 ###

`[+] option to block any POST request missing a referrer header.`

`[+] option to automatically whitelist private IP address spaces.`

### v1.0.1 ###

`[!] SCRIPT_NAME was missing from "Sanitising user input" log lines.`

`[+] option to sanitise uploaded files name.`

`[+] option to hide PHP errors.`

`======================================================================`

`                    [+] = added       [!] = fixed`

`                    [*] = changed     [-] = removed`

`======================================================================`