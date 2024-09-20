# Setup

* `git submodule init` (only once)

* `git submodule update`
* `cd next-translate`
* `git checkout testing`

If you check out a different branch, you may have to delete the `node_modules` directory.

Then:

* `yarn`
* `yarn build:next-translate`
* `yarn build`
* `yarn dev`

# Basic example

![next-translate](../../images/translation-prerendered.gif 'Translations in prerendered pages')
