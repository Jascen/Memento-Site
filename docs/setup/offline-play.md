# Offline Play
Ultima: Memento follows suit with it's predecessors; it is an open source project. This means the source code is readily available to you for your consumption, review, and modification.

!!! tip "Online server is recommended"
	The live-hosted server has very relaxed rules but disallows griefing and PVP. As an added bonus, it will contain the latest and greatest features as well as most recent bugfixes.

!!! warning "Only use GitHub Releases"
	The live-hosted server runs the code directly from the GitHub, but it is generally recommended to avoid doing this. Instead, to ensure optimal stability and compatibility, only the [latest GitHub Release](https://github.com/Jascen/ultima-memento/releases/latest) should be downloaded and used for playing.

## Fresh Install
1. Download the attached `Ultima-Memento-Server.zip`
1. Unzip to `C:\Ultima-Memento\Server`
	- Alternatively, you may install it whereever you wish
1. If necessary (non-Windows users), compile the EXE (see [README](https://github.com/Jascen/ultima-memento/tree/main?tab=readme-ov-file#running-locally))
	- Compile the World.exe:
		- Navigate to `World\Source\Tools`
		- Execute `compile-world-win.bat` or `compile-world-linux.sh`
1. Run the `World.exe` in the `Ultima-Memento\World` folder
1. Log in to the Admin (password is 'password') and run the `[BuildWorld` command

## Upgrades (Existing Install)
1. Archive your old `Ultima-Memento\World` folder to `Ultima-Memento\World_Old`
1. Download and unzip the attached `Ultima-Memento-Server.zip`
	- Move the `Ultima-Memento\World` folder to your install location
1. Copy the following from `Ultima-Memento\World_Old` to `Ultima-Memento\World`:
	- (optional) Backups folder
	- Info folder
	- Saves folder
1. Run the `World.exe` in the `Ultima-Memento\World` folder