# Docker image For SNPE

Docker image for

[SNPE](https://developer.qualcomm.com/docs/snpe/setup.html) `Snapdragon Neural Processing Engine SDK` 

with caffe & adb

# Usage

  
## build

```bash
	docker build -t snpe .
```
	
## Run
```bash
	# First time run
	docker run -it  --privileged -v ~/Git/snpe-1.13.0:/root/snpe -v /dev/bus/usb:/dev/bus/usb --name=snpe snpe
	# Not First time
	docker start -i snpe
```

## Running demo
   
```
	Follow the instructions on https://developer.qualcomm.com/docs/snpe/usergroup5.html to run tests
```
    
