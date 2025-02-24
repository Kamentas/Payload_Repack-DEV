# payload.bin repack tool

Using delta_generator to repack `payload.bin`.

### Requirements

- A compatible Linux system (x86_64/aarch64)
- git
- openjdk-jre
- python
- python-protobuf 
- zip
- unzip
- openssl
- openssl-tool

### Install
```bash
pkg upgr
pkg install git openssl-tool zip unzip python openjdk-17 xxd
pip install -r requirements.txt
```

## Usage

### repack `payload.bin`

```bash
cd Payload_Repack_Tool
#copy *.img into IMAGES folder
#cp -a *.img IMAGES
./repackPayload.sh
```
