# CentOS7-pptp-host1plus
# https://github.com/jiu-chuan/CentOS7-pptp-host1plus/releases/download/untagged-51608359652e0f7b8fb0/CentOS7-pptp-host1plus.sh
# chmod +x ./CentOS7-pptp-host1plus.sh
# ./CentOS7-pptp-host1plus.sh -u your_username -p your_password

## Build
Clone the repository and `cd` into the project folder. Then run the following:
```
cargo build --release
```

### Building Framework for Apple Devices
To build an XCFramework for macOS and iOS, run the following: 
```
./build-apple.sh
```
