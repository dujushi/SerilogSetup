# Serilog Setup
This is a sample program to setup [Serilog](https://serilog.net/) for AspNetCore.

## Setup process
1. Install nuget package [Serilog.AspNetCore](https://github.com/serilog/serilog-aspnetcore)
2. Add `Serilog` configuration to `appsettings.json` and `appsettings.Development.json`.
For Serilog configuration basics, please refer to [Configuration Basics](https://github.com/serilog/serilog/wiki/Configuration-Basics).
For configuration syntax, please refer to [Serilog.Settings.Configuration](https://github.com/serilog/serilog-settings-configuration).
3. Use `Serilog`
4. Use `SerilogRequestLogging` (Not setup in this project)
