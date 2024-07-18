# OWASP CRS - WordPress Rule Exclusions Plugin
![Integration tests](https://github.com/coreruleset/wordpress-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg)

## Description

This plugin contains rule exclusions for [WordPress](https://wordpress.org/), a content management system (CMS), so it can be run flawlessly together with
OWASP CRS (CRS).

This plugin only supports functionality provided within vanilla WordPress (No plugins installed). If you encounter false positives with a WordPress plugin then you need to write a [rule exclusion](https://coreruleset.org/docs/concepts/false_positives_tuning/) to resolve the false positive yourself.

## Installation

For full and up to date instructions for the different available plugin
installation methods, refer to [How to Install a Plugin](https://coreruleset.org/docs/concepts/plugins/#how-to-install-a-plugin)
in the official CRS documentation.

## Testing

After the plugin is enabled, your WordPress instance should work without any
problems possibly caused by CRS (for example, false positives while blocking
requests). If you are still having any problems, please file a new issue on
[github](https://github.com/coreruleset/wordpress-rule-exclusions-plugin).

## License

Copyright (c) 2022-2024 OWASP CRS project. All rights reserved.

The OWASP CRS and its official plugins are distributed
under Apache Software License (ASL) version 2. Please see the enclosed LICENSE
file for full details.
