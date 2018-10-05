wordpress.theme.weaver-ii.forbes-custom-css
===========================================

Custom css for use with the Weaver ii Wordpress theme, as used by
forbeslibrary.org

This repository consists of [LESS](http://lesscss.org/) code from which CSS can
be derived.

The resulting CSS is intended to be added using Weaver ii's advanced
options: `Weaver II Options → Advanced Options → <HEAD> Section → Custom CSS
Rules`

Note that many of these rules are very specific to Forbes Library's website.
You are welcome to adapt them to your needs, but are unlikely to find them
useful as is.

Required Software
-----------------
The easiest way to use LESS is with NPM and Node, available as a single download
from https://nodejs.org/en/download/.

Once NODE is installed type `npm install -g less` from the command line to
install LESS.

Instructions for compiling css
------------------------------
Type at command prompt:  `lessc --compress less/base.less > forbes-style.css`
