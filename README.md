# angular-foundation-thermondo
A Thermondo specific build for angular-foundation.

## Current Included components
 1. tooltip.

## To Add New Component

Follow https://github.com/pineconellc/angular-foundation#build

Shortly

```
 grunt html2js
 grunt build:tooltip
```

You will have your custom build in the ```./dist``` directory, move and **rename** the 4 files produced here. The ones with custom in their name.
When renaming you will just target the version you want and just remove it along with custom from the file name.
So

```sh
  mv mm-foundation-custom-tpls-0.6.0.min.js mm-foundation-tpls.min.js
  mv mm-foundation-custom-0.6.0.min.js mm-foundation.min.js
  mv mm-foundation-custom-tpls-0.6.0.js mm-foundation-tpls.js
  mv mm-foundation-custom-0.6.0.js mm-foundation.js
```

