# worklogs

This is a worklogs plugin for Redmine.


## Installation

To install the plugin, execute the following commands from the root of your Redmine directory:

```
cd plugins
git clone git@github.com:IceskYsl/worklogs.git
bundle install
```

and then execute the following commands from the root of your Redmine directory:

```
$ rake redmine:plugins:migrate
```	

More information on installing Redmine plugins can be found at [redmine.org](http://www.redmine.org/wiki/redmine/Plugins.).


After the plugin is installed you will need to restart Redmine for the plugin to be available.

### Uninstallation

To remove the plugin, from the root of your installation directory do the following:
```
rm -rf plugins/worklogs
bundle install
```
