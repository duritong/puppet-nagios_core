# nagios

#### Table of Contents

1. [Description](#description)
2. [Limitations - OS compatibility, etc.](#limitations)
3. [Development - Guide for contributing to the module](#development)

<a id="description"></a>
## Description

The nagios module is used to manage Nagios's various configuration files.

<a id="limitations"></a>
## Limitations

All `nagios_*` types default to having a `target` under `/etc/nagios/`, but should work on any system as long as an appropriate `target` is set for that system.

<a id="deprecation"></a>
## Deprecation

When the `nagios_*` types were removed from Puppet in Puppet Platform 6 and extracted to this module, they were effectively deprecated and are now no longer under active develepment.

This repository has been archived, so you can still fork it and use the code. If you need help or have questions about this module, you can use our [Community Slack](https://slack.puppet.com/).