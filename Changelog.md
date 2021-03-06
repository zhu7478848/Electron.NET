# not release

# 5.0.12

ElectronNET.CLI:

* Implement 'add hosthook' command for add a ElectronHostHook-Directory
* Fixed bug: 'Unexpected firewall warnings' [\#181](https://github.com/ElectronNET/Electron.NET/issues/181)
* Fixed bug: 'found 8 vulnerabilities (1 low, 5 moderate, 2 high)' [\#199](https://github.com/ElectronNET/Electron.NET/pull/199)
* Merged pull request: Call electronize from the Path instead of via dotnet in launchSettings.json [\#243](https://github.com/ElectronNET/Electron.NET/pull/243) (thanks [grbd](https://github.com/grbd))

ElectronNET.API:

* Implement Electron 5.0.1 support, but not all new features
* Implement HostHook-API for execute own TypeScript/JavaScript code
* Fixed bug: 'X and Y options to not work on Windows 10' [\#193](https://github.com/ElectronNET/Electron.NET/issues/193)
* Merged pull request: Fix BrowserWindow::SetMenu [\#231](https://github.com/ElectronNET/Electron.NET/pull/231) thanks (thanks [CodeKenpachi](https://github.com/CodeKenpachi))
* Merged pull request: FIX application hangs after socket reconnect [\#233](https://github.com/ElectronNET/Electron.NET/pull/233) (thanks [pedromrpinto](https://github.com/pedromrpinto))
* Merged pull request: Reduce chance of detecting false positives when scanning subprocesses for errors. [\#236](https://github.com/ElectronNET/Electron.NET/pull/236) (thanks [BorisTheBrave](https://github.com/BorisTheBrave))
* Merged pull request: Updates the C# API to accept floating point as in JS. [\#240](https://github.com/ElectronNET/Electron.NET/pull/240) (thanks [BorisTheBrave](https://github.com/BorisTheBrave))
* Merged pull request: buildReleaseNuGetPackages should leave you in the same directory you …  [\#241](https://github.com/ElectronNET/Electron.NET/pull/241) (thanks [BorisTheBrave](https://github.com/BorisTheBrave))

# 0.0.11

ElectronNET.CLI:

* Invoke 'npm install' without --prod flag to install needed devDependencies as well.
* Enable SourceLink
* NuGet Package License Information updated (deprecation of licenseUrl)

ElectronNET.API:

* Documentation added for WebContents.GetUrl()
* Enable SourceLink
* NuGet Package License Information updated (deprecation of licenseUrl)

# 0.0.10

ElectronNET.API:

* manifestJsonFilePath fixed (thanks @smack0007)
* Use Electron release 3.0.0 and updated packages (thanks @deinok)
* fixes for Socket interaction (thanks @mojinxun)
* Fixing SingleInstances (thanks @yaofeng)
* Enhance WebContent.GetUrl (thanks @ru-sh)

ElectronNET.CLI:

* Show Resultcode for better debugging when using Build/Start Command
* ElectronNET.CLI is now a global dotnet tool

# 0.0.9

ElectronNET.API:

* Better Async handling - thanks @danielmarbach

ElectronNET.CLI:

* More options on the 'build' command, e.g. for a 32bit debug build with electron prune: build /target custom win7-x86;win32 /dotnet-configuration Debug /electron-arch ia32  /electron-params "--prune=true "
* .NET Core project is now build with Release configuration, but can be adjusted with the new params.
* Be aware: "Breaking" (but because of the alpha status of this project, we won't use SemVer)

# 0.0.8

This version was skipped because we unfortunatly released a pre version of this on NuGet.

# 0.0.7

ElectronNET.CLI:

* Fixed electronize start for macos/linux - thanks @yamachu
* Skip NPM install on start when node_modules directory already exists

# 0.0.6

ElectronNET.CLI:

* nuget packages are now release bits and have the correct assembly verion
* Version command 
* better devCleanup.cmd
* Better Platform Support Issue - thanks to @Petermarcu
* Start Command should now work on OSX/Linux - thanks to @r105m

ElectronNET.API:

* Thread-Safe methods - thanks to @yeskunall

# 0.0.5

ElectronNET.API:

* The last nuget package didn't contain the actual webpreferences settings with defaults - hopefully now.

# 0.0.4

ElectronNET.CLI:

* dotnet electronize start fixed

ElectronNET.API:

* WebPreferences settings with default values

# 0.0.3

ElectronNET.CLI:
* Init with Debug profile
* Build for all platforms (well... for newest OSX/Linux/Windows)

ElectronNET.API:
* Moar XML documentation 
* Hybrid support (e.g. running as normal website and electron app)
* Event bugfixing

# 0.0.2

ElectronNET.CLI:
* Added Init to Help page
* Added XML documentation to NuGet output
* Maybe fixed for https://github.com/GregorBiswanger/Electron.NET/issues/2

ElectronNET.API:
* Add XML documentation to NuGet output
* Implemented Notification-, Dialog- & Tray-API

# 0.0.1

* init everything and basic functionality
