* Install autofac
	- install-package autofac
	- install-package Autofac.Extensions.DependencyInjection
	- set UseServiceProviderFactory in program
* Install serilog
	- install-package serilog
	- install-package Serilog.Extensions.Logging
	- install-package Serilog.Sinks.Console
	- install-package Serilog.Extensions.Hosting (for hostbuilder)
	- configure environment specific setting inside Program.UseSerilog in hostbuilder
* Add authentication
* Add swagger
* Add dbContext

* middleware