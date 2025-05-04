# OWASP CRS - WordPress Rule Exclusions Plugin
![Integration tests](https://github.com/coreruleset/wordpress-rule-exclusions-plugin/actions/workflows/integration.yml/badge.svg)

## Description

This plugin contains rule exclusions for [WordPress](https://wordpress.org/), a content management system (CMS), so it can be run flawlessly together with
OWASP CRS (CRS).

This plugin only supports functionality provided with vanilla WordPress (without plugins installed). False positives that are due to WordPress plugins must be resolved with [custom rule exclusions](https://coreruleset.org/docs/concepts/false_positives_tuning/).

3rd Party themes are supported for both block based themes and classic site editor themes, however 3rd party theme plugins and builders are not supported, those must be tuned manually with a [custom rule exclusions](https://coreruleset.org/docs/concepts/false_positives_tuning/).

## Installation

For full and up to date instructions for the different available plugin
installation methods, refer to [How to Install a Plugin](https://coreruleset.org/docs/concepts/plugins/#how-to-install-a-plugin)
in the official CRS documentation.

### Conditionally enable plugins for multi-application environments

For full and up to date instructions on how to conditionally enable/disable this plugin on a multisite environment, please refer to [Conditionally enable plugins for multi-application environments](https://coreruleset.org/docs/concepts/plugins/#conditionally-enable-plugins-for-multi-application-environments) in the official CRS documentation.

## Testing

After the plugin is enabled, your WordPress instance should work without any
problems possibly caused by CRS (for example, false positives while blocking
requests). If you are still having any problems, please file a new issue on
[github](https://github.com/coreruleset/wordpress-rule-exclusions-plugin).

## License

Copyright (c) 2022-2025 OWASP CRS project. All rights reserved.

The OWASP CRS and its official plugins are distributed
under Apache Software License (ASL) version 2. Please see the enclosed LICENSE
file for full details.
