# Mobile Client
Ultima: Memento keeps Mobile users in mind when designing interfaces.

!!! warning "Custom Data Files"
	Ultima: Memento does not use the standard UO data files. All custom files (including container.txt) are included in our packages below.

## Download the App
- [MobileUO on Google Play](https://play.google.com/store/apps/details?id=com.mobileuo.mobileuo)

- [MobileUO on the iOS App Store](https://apps.apple.com/us/app/mobileuo/id1511721667)

## Server Information
--8<-- "docs/setup/online-server-info.md"
- File Download Server Address: (see [Data Package](#data-package))

## Data Package
- Upload to Dropbox (and append `&dl=1` to the URL)
- Copy the files directly to your phone
- Use a local file server (like Mongoose)

### Using Mongoose (Advanced)
You need to host the client files and download them from yourself:

1. [Mongoose.exe google drive link](https://drive.google.com/file/d/1MqnVCdiEZjARozYsjtK6HovZW_OYmdmj/view?usp=sharing)
  	- Alternate link: https://github.com/cesanta/mongoose

1. Place the exe in the `C:\Ultima-Memento\Client\Data Files\` folder and run it
	- Verify you can see the files on your own computer: `http://localhost:8000`

1. Look up your PC's ip address for your local area network

1. Plug that IP address into MobileUO's configuration for `File Download Server Address` and verify the port is `8000` (as seen above)

1. Try to connect to the server using MobileUO and it will download all the files it needs to run

## Supporting Links
- [Main MobileUO Wiki (setup)](https://github.com/VoxelBoy/MobileUO/wiki)
- (optional) [Host your own Mongoose file server](https://github.com/VoxelBoy/MobileUO/wiki/UO-File-Server-Setup-Instructions)