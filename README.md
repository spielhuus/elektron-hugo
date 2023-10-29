# elektron-hugo

the hugo theme for elektrophon provides all the partials and callouts to render the notebook markdown files.

## installation

Create a new site

```
hugo new site <name of site> -f yml
cd <name of site>
```

use as theme submodule

```
git submodule add --depth=1 https://github.com/spielhuus/elektron-hugo
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```
updating theme:

```
git submodule update --remote --merge
```
