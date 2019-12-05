# cisco_config_converter
Convert IOS configuration based on Excel file

This tool helps administrator needing to adapt Cisco configuration files in multiple ways.

Use case example:
------------------

- Migration between different switches / routers platforms
==========================================================

In this case, you can ask the script to add / replace or delete command lines on previous configurations.
This will generate a new configuration file that you can inject to your equipement.
For example this script has previously been used to convert ISR Gen 2 (1900/2900) configuration to ISR Gen 3 (4000).
This could be adapted to migrate any type of configuration from any Cisco device to other type.
