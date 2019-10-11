# Identicon
## Authors: Will Fenton & Giancarlo Pernudi Segura

This is a short one-day project to make an Identicon generator (see [drhus/awesome-identicons](https://github.com/drhus/awesome-identicons)).

### Versions

`identicon.py`
+ outputs a simple ascii image based on a SHA-256 hash

`randomart.py`
+ implements the OpenSSH ascii fingerprint algorithm

`identicon.pde`
+ recursively colors rectangles based on a string seed

`sectors_rgb.py`
+ uses nearest neighbors algorithm to generate an unique image based on a SHA-256 hash

`sectors.py`
+ same as sectors_rgb.py but uses HSV for nicer colors (and some nice features like command line input and SHA-512)
+ Uasge: `./sectors.py <string>...`
+ images are saved in `output/` folder


### Examples
#### sectors.py

gino:

![gino.png](examples/gino.png "gino.png")

will:

![will.png](examples/will.png "will.png")

yeet:

![yeet.png](examples/yeet.png "yeet.png")

💯:

![💯.png](examples/💯.png "💯.png")
