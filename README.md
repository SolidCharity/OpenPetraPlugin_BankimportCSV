# Plugin BankimportCSV

This is a plugin for [www.openpetra.org](http://www.openpetra.org).

## Functionality

You can import bank statements into OpenPetra with the plugin [Bankimport](https://github.com/SolidCharity/OpenPetraPlugin_Bankimport).

Often banks allow in their online banking to download the transactions as a CSV file.
This plugin allows CSV files to be imported, that contain the bank statements.

## Dependencies

This plugin requires this plugin:

* https://github.com/SolidCharity/OpenPetraPlugin_Bankimport

## Installation

Please copy this directory to your OpenPetra working directory, to csharp\ICT\Petra\Plugins, or include it like this, if you are using git anyway:

    git submodule add https://github.com/SolidCharity/OpenPetraPlugin_BankimportCSV csharp/ICT/Petra/Plugins/BankimportCSV

and then run

    nant generateSolution

Please check the config directory for changes to your config files.

## License

This plugin is licensed under the GPL v3.