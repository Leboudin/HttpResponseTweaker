For user
========

This is a tool for developers.
If you are not a web developer and been recommended this add-on from others, it is high chance that you are being socially attacked from a cracker.

We strongly recommend to use it if you can read what it is doing from the source code.

Current restrictions (TODOs)
----------------------------
- Can't modify header
- Filter fails when target data split in different chunks
- Only support UTF-8


For developers of this add-on
=============================

Prerequiste  
-----------
  - nvm
  - node installed via nvm
  - npm installed via nvm
Recommended
-----------
  - Linux (or UNIX-like OS)
  - direnv 
  - Firefox developer edition

Setup
-----
1. Setup node env
    `nvm use`
    `npm ci`

2. Build
    `npm run clean-build`

3. Try on local
Open your firefox and navigate to 'about:debugging'.
Load temporary add-on and open the 'dist/manifest.json' generated in the former step.


License
=======
GPL v3

See LICENSE.txt
