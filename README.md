CiviBanking
===========

CiviCRM banking extension

Implements handling of bank accounts for contacts, as well as handling of bank files (and individual bank payements extracted from the files). Bank files can be imported, payments matched to CiviCRM entities, and the resulting data exported. Specific handlers for all of these actions are provided through plugins, some of which are shipped with the core banking extension, while some more complex ones are provided in separate extensions.


Documentation
=============

You can find the most recent (yet restricted) documentation as part of the [Official CiviCRM Documentation](https://docs.civicrm.org/banking/en/latest/). If you just want to get an idea of what this is about, we recommend watching the [**session on CiviBanking at CiviCon Amsterdam**](https://vimeo.com/143368850).


Installation
============

Simply download the ``org.project60.banking-x.x.zip`` file from the [**latest release**](https://github.com/Project60/org.project60.banking/releases/latest), unzip in your extension folder, and then press install in CiviCRM's extension screen.


Fork
====

ECOPLAN GmbH added some PR und bugfixes to create a working snapshot of the master branch. Looking forward for a new release... 

Changes: 
Issue #348 and #349 Search / filter list of statements not working
Translation de_DE for configuration_database/Matcher/DefaultOptions/Default Options.civbanking 
Issue #298 configuration_database/Matcher/DefaultOptions/Default Options.civbanking 
Issue #300 extension/CRM/Banking/PluginImpl/Importer/CSV.php 
Issue #293 PHP 7.2 compatibility https://github.com/Project60/org.project60.banking/issues/293 -> TODO
