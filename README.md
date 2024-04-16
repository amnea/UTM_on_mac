# UTM_on_mac

## 1. Install Brew 
You can install Homebrew easily on mac:
* open a terminal
* Type or copy/paste this code and then press "return": 
```Shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


![Install_Brew](./videos/install_brew.gif) 

This script will install brew and Xcode. You'll need to Agree to install xcode.

## 2. Install UTM

To install UTM using brew:
```Shell
brew install --cask utm
```

![Install_UTM](./videos/install_utm.gif)

## 3. Install Crystal Fetch (Windows) [Move to step 7 for MacOS VMs]

To install Crystal Fetch using brew:
```Shell
brew install --cask crystalfetch
```

![Install_Crystal_Fetch](./videos/install_crystalfetch.gif)

## 4. Download Windows11 and Setup Your Win11 VM

![Download Windows 11 (ARM)](./videos/get_win11_vm_setup.gif)

## 5. Setup Win11

![Setup_Win11](./videos/installing_win11.gif)

## 6. Finishing Up Windows Install
![Finish Setup Win11](./videos/finishing_up.gif)

## 7. Install Mist (MacOS)

```Shell
brew install --cask mist
```

![Install_Mist](./videos/install_mist.gif)

## 8. Download MacOs Firmware Image


![Download_Mac_Firmware](./videos/download_ipsw_firmware_image.gif)


## 9. Setup Your MacOS VM

![Setup_MacOS_VM](./videos/setup_macos_vm.gif)


## 10. Setup Your MacOS 

![Setup_MacOS](./videos/setup_macos.gif)

## References:

[Homebrew](https://brew.sh/) - is a package manager for MacOS, used to easily install apps and programs from the web.

[UTM](https://mac.getutm.app/) - UTM is a GUI wrapper for KVM. UTM allows a user to easily create and edit virtual machines on MacOS.

[Crystal Fetch](https://github.com/TuringSoftware/CrystalFetch) - automation for downloading Windows 10/11

[Mist](https://github.com/ninxsoft/Mist) - automation for downloading MacOS firmware and installer images