# learn-golang
a collection of golang tutorial from many sources, intended for learning and helping to grasp the concept of golang itself.

## INSTALING GOLANG
first of all, before running some project here, it's mandatory to install golang first. Please pay attention that this is intended for `Linux`.
1. Download a binary file from [here](https://golang.org/dl/). Please consider the version you're about to download. Between versions might have different functionality even it's just small. Rule of thumbs for this is use the same version with your colleagues.
2. Extract your binary to folder `/usr/local` by using `tar -C /usr/local -xzf your_binary.tar.gz` as root user. 
3. Export `/usr/local/go/bin` to the PATH environment variable and restart your pc or you can do it by adding this line to file `$HOME/.profile`. After adding and saving, please run `touch` to implement your change.
   ```
   export PATH=$PATH:/usr/local/go/bin
   ```