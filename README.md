# ensmarteditor Runtime version 3


ensmarteditor is an open-source [Programmable Logic Controller](https://en.wikipedia.org/wiki/Programmable_logic_controller) that is based on easy to use software. Our focus is to provide a low cost industrial solution for automation and research. OpenPLC has been used in [many research papers](https://scholar.google.com/scholar?as_ylo=2014&q=openplc&hl=en&as_sdt=0,1) as a framework for industrial cyber security research, given that it is the only controller to provide the entire source code.
The Ensmarteditor Project consists of three sub-projects:
1. [Runtime](https://github.com/ensmartcontrols/ensmarteditor)
2. [Programming editor](http://www.openplcproject.com/plcopen-editor)


## Installation:
```bash
git clone https://github.com/ensmartcontrols/ensmarteditor.git
cd ensmarteditor
./install.sh [platform]
```

Where `[platform]` can be:

`win` - Install Ensmarteditor on Windows over Cygwin

`linux` - Install EnsmartEditor on a Debian-based Linux distribution

`docker` - Used by the `Dockerfile` (i.e. doesn't invoke `sudo`)

`rpi` - Install EnsmartEditor on a Raspberry Pi

`custom` - Skip all specific package installation and tries to install Ensmarteditor assuming your system already has all dependencies met. This option can be useful if you're trying to install OpenPLC on an unsuported Linux platform or had manually installed all the dependency packages before.


