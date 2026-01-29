# xstore-sqli-cve


# XStore WordPress Theme SQL Injection Vulnerability

A Boolean-based SQL Injection vulnerability exists in the XStore WordPress theme (versions <= 9.4.7).

The vulnerability is caused by improper sanitization of user-supplied input in the `etheme_search_post_excerpt` function, allowing attackers to inject arbitrary SQL queries.

Details will be disclosed after the vendor releases a security patch.

## Affected Product
- XStore WordPress Theme
- Versions: <= 9.4.7

## Vulnerability Type
- SQL Injection (Boolean-based)

## Researcher
- Mingxuan Gu (Independent Security Researcher)

## Disclosure
This issue was responsibly disclosed to the vendor.

