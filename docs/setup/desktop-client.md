# Desktop Client

!!! warning "Custom Data Files"
	Ultima: Memento does not use the standard UO data files. All custom files (including container.txt) are included in our packages below. You can also download them directly from [GitHub]({{github_assets_url}})

## Download Package
- Download the client and data files: [(1.8gb) Ultima-Memento.zip]({{client_download_link}})

??? tip "Have 7zip?"
	Download the same package, but smaller: [(1.3gb) Ultima-Memento.7z]({{client_download_link_7z}})

## Install Package
- Unzip the file at your root `C:\`

??? warning "Want to install elsewhere?"
	If you want to deviate from the default install location (`C:\Ultima-Memento\Client`), you may need to adjust the provided profiles.

	- Open the TazUO Launcher
	- Click the dropdown and select `[Edit Profile]`
	- Select the `Memento` (and/or `Testing`) profile
	- Update the `UO Directory` path
		- Old value: `C:\Ultima-Memento\Client\Data Files`
		- New value: `{{YOUR_PATH_CHOICE}}\Ultima-Memento\Client\Data Files`
	- Press the `Save` button

- Open the `Client\TazUO Launcher` folder
- Run `TazUO Launcher.exe`
- Select the `Memento` profile to join the live-hosted server
	- The `Testing` profile is used for for Offline/local play
- Click `Play`
- Create a username and password
	- Account creation is automatic

## Mac users

- Download Memento's custom [Data Files]({{github_assets_url}})
	- Unzip this in a ".../Memento/Client/Data Files" location
- Download the TazUO Launcher for Mac from the [TazUO website](https://tazuo.org/introduction/how-to-install/#installation-guide)
- Launch the TazUO Launcher and add a new server profile
	- Select Memento in the presets list
	- Configure the launcher as below
	- *Note*: The `UO Directory` should be pointing to the unzipped `Data Files` folder

## Server Information
--8<-- "docs/setup/_online-server-info.md"