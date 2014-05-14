This script was formerly [here](http://gnu.ethz.ch/linuks.mine.nu/amiga/), but the page seems to have disappeared.

The [FreeCode page](http://freecode.com/projects/amigashell) of the project.

(amigashell-2.3-4-any.pkg.tar.xz is the Arch Linux AUR package salvaged with bacman.)

## Usage

Start with

    systemctl start amigashell.service

Run automatically at boot with

    systemctl enable amigashell.service

### Originial description follows (from [archive.org](https://web.archive.org/web/20120106063129/http://gnu.ethz.ch/linuks.mine.nu/amiga/) )

AmigaSHELL makes your boring gray on black colored
bash shell revive like in the old days. Just like on
Amiga(tm), blue, white, orange, black at its finest.
With a nice informational bar at the top.
(ascii graphics not included, go to www.asciipr0n.com)

tested on debian gnu/linux (x86 and sparc)

send me a letter or screenshot
freshmeat.net record
download theme for wmpinboard


download and install
amigashell-2.3.tar.gz
amigashell-2.3.tar.bz2

    (be root)
    make install
    amigashell start
    cd /etc/rc2.d
    ln -s ../init.d/amigashell S99amigashell

changelog
old versions
"Where have all the Amigas gone?" - AmigaSHELL got mentioned in Linux Format (page 43, issue 21, December 2001), here is a scan. Thanks to James W. Robinson from here.
