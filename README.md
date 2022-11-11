## Pronounce this Version 2.0

### Dependencies
There is only one required dependency `curl`,however the rest require some
configuration before you can replace them.

### Optional dependencies
* dmenu
* fzf
* parallel 
* mpv 

### Install

```sh
git clone https://github.com/AnasBoubechra/Pronounce_this.git
cd Pronounce_this && chmod +x pt
# Make sure you put the script in your $PATH
./pt # Or 'pt' if the script is in path
```

#### To put the script in your path 
```
PATH="$HOME/.local/share/bin/" # Or '/usr/bin'
```
### Usage

* Simple query based search `pt -q <string>`
* Generic pronunciation `pt -p "Hello world"`
* To list the audio files using dmenu  `pt -mq <string>` Or `pt -m -q <string>`
* To list the audio files using fzf  `pt -fq <string>` Or `pt -f -q <string>`
* Use a specific language code (en,de,fr...) `pt -q <string> -l de`

### Enhancements

* Fzf support
* Dmenu support
* Offline audio downloads
* generic Pronunciation of any language
* POSIX-compliant 
* parallel downloads 
* Efficient memory usage
---


#### Support
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q2EA2RO)
