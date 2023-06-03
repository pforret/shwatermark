![bash_unit CI](https://github.com/pforret/shwatermark/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/shwatermark/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/shwatermark)
![GH stars](https://img.shields.io/github/stars/pforret/shwatermark)
![GH tag](https://img.shields.io/github/v/tag/pforret/shwatermark)
![GH License](https://img.shields.io/github/license/pforret/shwatermark)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

![Under Development](https://img.shields.io/badge/under-development-orange)

# shwatermark

Resize and watermark photos

## 🔥 Usage

```
Program: shwatermark 0.1.1 by peter@forret.com
Updated: Dec 17 22:30:33 2021
Description: Resize and watermark photos
Usage: shwatermark [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-i <input>] [-e <output>] [-I <inexts>] [-E <outexts>] [-A <alpha>] [-C <color>] [-F <font>] [-M <mark>] [-O <position>] [-S <size>] [-X <fx>] [-E <email>] [-P <name>] [-S <shoot>] [-T <tags>] [-U <url>] [-p <pixel>] [-q <quality>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/shwatermark]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/shwatermark]
    -i|--input <?>   : [option] input folder  [default: .]
    -e|--output <?>  : [option] output folder  [default: ./export]
    -I|--inexts <?>  : [option] input extensions  [default: jpg,jpeg,JPG]
    -E|--outexts <?> : [option] output extensions  [default: jpg]
    -A|--alpha <?>   : [option] watermark alpha opacity  [default: 80]
    -C|--color <?>   : [option] watermark color  [default: FFF]
    -F|--font <?>    : [option] watermark font  [default: Helvetica]
    -M|--mark <?>    : [option] watermark text  [default: {name}]
    -O|--position <?>: [option] watermark position  [default: SouthWest]
    -S|--size <?>    : [option] watermark font size  [default: 20]
    -X|--fx <?>      : [option] watermark effect  [default: shadow]
    -E|--email <?>   : [option] email of photographer (EXIF)
    -P|--name <?>    : [option] name of photographer (EXIF)  [default: pforret]
    -S|--shoot <?>   : [option] shoot/event name (EXIF)
    -T|--tags <?>    : [option] shoot/event tags (EXIF)  [default: 2021]
    -U|--url <?>     : [option] photographer url (EXIF)
    -p|--pixel <?>   : [option] max pixel dimension  [default: 1600]
    -q|--quality <?> : [option] export quality %  [default: 95]
    <action>         : [parameter] action to perform: export/modify

### TIPS & EXAMPLES
* use shwatermark export to export photos
  shwatermark export
* use shwatermark modify to modify photos in place
  shwatermark modify
* use shwatermark check to check if this script is ready to execute and what values the options/flags are
  shwatermark check
* use shwatermark env to generate an example .env file
  shwatermark env > .env
* use shwatermark update to update to the latest version
  shwatermark check
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

## ⚡️ Examples


## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/shwatermark

or with `git`

	$ git clone https://github.com/pforret/shwatermark.git
	$ cd shwatermark

## 📝 Acknowledgements

* uses lots of tricks from [PaparazzoMark](https://github.com/pforret/PaparazzoMark)
* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2021 Peter Forret
