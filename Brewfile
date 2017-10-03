#!/usr/bin/env bash

#BREWFILE_IGNORE
if ! which brew >& /dev/null;then
  brew_installed=0
  echo Homebrew is not installed!
  echo Install now...
  echo ruby -e \"\$\(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install\)\"
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  echo
fi
#BREWFILE_ENDIGNORE

# tap repositories and their packages

brew tap caskroom/cask
brew cask install aquaterm
brew cask install filezilla
brew cask install gimp
brew cask install haskell-platform
brew cask install hyperswitch
brew cask install iterm2
brew cask install java
brew cask install launchy
brew cask install osxfuse
brew cask install paraview
brew cask install skim
brew cask install vagrant
brew cask install xquartz

brew tap homebrew/boneyard

brew tap homebrew/core
brew install jpeg
brew install gd
brew install gcc@4.9 --with-fortran
brew install macvim
brew install x264
brew install gdbm
brew install gobject-introspection
brew install cln
brew install ocaml
brew install lapack
brew install fontconfig
brew install lv
brew install gdk-pixbuf
brew install htop-osx
brew install pyqt
brew install gmp
brew install yuicompressor
brew install pixman
brew install freetype
brew install python
brew install gtk+
brew install gnutls
brew install pango
brew install isl@0.11
brew install python3
brew install isl@0.12
brew install npth
brew install p11-kit
brew install makedepend
brew install yasm
brew install gnu-tar
brew install cscope
brew install findutils
brew install shared-mime-info
brew install cairo
brew install webp
brew install texi2html
brew install intltool
brew install emscripten
brew install libunistring
brew install geos
brew install libgpg-error
brew install automake
brew install lua
brew install proj
brew install libpng
brew install xvid
brew install boost
brew install gnu-time
brew install camlp5
brew install tree
brew install screen
brew install ginac
brew install wget
brew install libgcrypt
brew install openssl
brew install pandoc
brew install atk
brew install icu4c
brew install isl
brew install pkg-config
brew install open-mpi
brew install adns
brew install libtiff
brew install sqlite
brew install harfbuzz
brew install xz
brew install sshfs
brew install pcre
brew install mpfr@2
brew install gmp@4
brew install libmpc@0.8
brew install cabal-install
brew install libgeotiff
brew install glib
brew install nkf
brew install libmpc
brew install cgal
brew install graphite2
brew install libusb
brew install libevent
brew install peco
brew install grep
brew install ffmpeg
brew install mtr
brew install libtasn1
brew install gnupg
brew install autoconf
brew install gnu-sed
brew install hicolor-icon-theme
brew install libassuan
brew install sphinx-doc
brew install libcroco
brew install cloog
brew install gcc
brew install sip
brew install cmake
brew install gnuplot --with-cairo --with-aquaterm --with-x11
brew install lame
brew install librsvg
brew install coreutils
brew install tig
brew install openblas
brew install qt
brew install node
brew install llvm
brew install giflib
brew install pinentry
brew install libtool
brew install openssl@1.1
brew install libffi
brew install netcat
brew install readline
brew install lzlib
brew install gettext
brew install nettle
brew install mozilla-addon-sdk
brew install ghc
brew install libksba
brew install mpfr

brew tap homebrew/dupes

brew tap homebrew/fuse

brew tap homebrew/science

brew tap homebrew/versions

brew tap rcmdnk/file
brew install brew-file

# Cask applications
brew cask install sshfs

# App Store applications
#appstore 682658836 GarageBand
#appstore 408981434 iMovie
#appstore 409183694 Keynote
#appstore 414030210 LimeChat
#appstore 409203825 Numbers
#appstore 409201541 Pages
#appstore 803453959 Slack
#appstore 497799835 Xcode
#appstore 428834068 Yorufukurou
