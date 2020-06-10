<a name=top>
<h1 align=center>
   <a href="https://github.com/timm/blob/master/shape/README.md#top">
     SHape = Simple HAck 4   Programs + documeEntation
   </a>
</h1>
<p align=center>
   <a href="https://github.com/timm/shape/blob/master/LICENSE">license</a>
   :: <a href="https://github.com/timm/shape/blob/master/INSTALL.md#top">install</a>
   :: <a href="https://github.com/timm/shape/blob/master/CODE_OF_CONDUCT.md#top">contribute</a>
   :: <a href="https://github.com/timm/shape/issues">issues</a>
   :: <a href="https://github.com/timm/shape/blob/master/CITATION.md#top">cite</a>
   :: <a href="https://github.com/timm/shape/blob/master/CONTACT.md#top">contact</a>
</p>
<p align=center>
   <img width=600 src="https://github.com/timm/misc/blob/master/odd/etc/img/solidgallery.gif">
</p>
<p align=center>
   <img src="https://img.shields.io/badge/language-lua-orange">
   <img src="https://img.shields.io/badge/purpose-ai,se-blueviolet">
   <img src="https://img.shields.io/badge/platform-mac,*nux-informational">
   <a href="https://travis-ci.org/github/timm/shape"> <img src="https://travis-ci.org/timm/shape.svg?branch=master"></a>
   <a href="https://zenodo.org/badge/latestdoi/263210595"> <img src="https://zenodo.org/badge/263210595.svg" alt="DOI"></a>
</p>

## Installation

Install gawk

```sh
wget -O gawk.tar.gz https://ftp.gnu.org/gnu/gawk/gawk-5.1.0.tar.gz
tar xzf gawk.tar.gz
cd gawk-5.1.0
./configure
sudo make
sudo make install                                │~
```

Then run the set ups inside `ape`.

```
sh ape
```

Then run the test scripts.

```
sh ape test/allok.md
```