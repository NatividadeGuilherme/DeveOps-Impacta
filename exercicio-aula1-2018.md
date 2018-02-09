Multiple MPMs can now be built as loadable modules at compile time. The MPM of choice can be configured at run time via LoadModule directive.
Event MPM
The Event MPM is no longer experimental but is now fully supported.
Asynchronous support
Better support for asynchronous read/write for supporting MPMs and platforms.
Per-module and per-directory LogLevel configuration
The LogLevel can now be configured per module and per directory. New levels trace1 to trace8 have been added above the debug log level.
Per-request configuration sections
<If>, <ElseIf>, and <Else> sections can be used to set the configuration based on per-request criteria.
General-purpose expression parser
A new expression parser allows to specify complex conditions using a common syntax in directives like SetEnvIfExpr, RewriteCond, Header, <If>, and others.
KeepAliveTimeout in milliseconds
It is now possible to specify KeepAliveTimeout in milliseconds.
NameVirtualHost directive
No longer needed and is now deprecated.
Override Configuration
The new AllowOverrideList directive allows more fine grained control which directives are allowed in .htaccess files.
Config file variables
It is now possible to Define variables in the configuration, allowing a clearer representation if the same value is used at many places in the configuration.
Reduced memory usage
Despite many new features, 2.4.x tends to use less memory than 2.2.x.
