# $Id: pkgbuild-mode.el,v 1.23 2007/10/20 16:02:14 juergen Exp $
# Maintainer: <ivo@arch>
pkgname=dot-org-files
pkgver=3a04eb0
pkgrel=1
epoch=
pkgdesc="A package to set up my archlinux working environment"
arch=('i686')
url="https://github.com/ivoarch/.dot-org-files"
license=('UNLICENSE')
groups=()
depends=("abs"
         "arch-wiki-lite"
	 "htop"
	 "pkgstats"
	 "pkgfile"
	 "reflector"
	 "gstreamer0.10"
	 "gstreamer"
	 "git"
	 "python-pip"
	 "sbcl"
	 "sxiv"
         "xorg-server"
	 "xorg-xinit"
	 "xorg-utils"
	 "xorg-server-utils"
	 "xorg-xfontsel"
	 "emacs"
	 "xf86-video-intel"
	 "xf86-input-synaptics"
	 "ttf-dejavu"
	 "xorg-xlsfonts"
	 "terminus-font"
	 "imagemagick"
	 "scrot"
	 "wireless_tools"
	 "dosfstools"
	 "rfkill"
	 "w3m"
	 "offlineimap"
	 "ffmpeg"
	 "mplayer"
	 "youtube-dl"
	 "flashplugin"
	 "openssh"
	 "alsa-oss"
	 "alsa-plugins"
	 "alsa-utils"
	 "rxvt-unicode"
	 "urxvt-perls"
	 "xterm"
	 "screen"
	 "zsh"
	 "acpi"
	 "lsof"
	 "moreutils"
	 "p7zip"
	 "unrar"
	 "unzip"
	 "zip"
	 "xclip"
	 "xdotool"
	 "xdg-user-dirs"
	 "xorg-xmessage"
	 "wget"
	 "wpa_supplicant"
         "ghostscript"
         "dialog"
         "xulrunner"
         "yajl"
         "kernel-netbook"
	 "profile-sync-daemon"
	 "profile-cleaner"
	 "speedtest-cli"
         "dropbox"
	 "dropbox-cli"
         "conkeror-git"
	 "cower-git"
	 "transmission-gtk2"
	 "itmages-upload.git"
         "mu-git"
         "stint-git"
	 "xbanish"
         "trash-cli-git"
	 "antigen-git"
         "ratpoison-git"
         "perl-config-general"
         "perl-getopt-long-descriptive")
makedepends=('git')
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
noextract=()
source=("git+https://github.com/ivoarch/.dot-org-files.git")
md5sums=('SKIP')

gitname=".dot-org-files"

pkgver() {
  cd $srcdir/$gitname
  git describe --always | sed 's|-|.|g'
}

package() {
  cd $srcdir/$gitname
  exit
}

# vim:set ts=2 sw=2 et:
