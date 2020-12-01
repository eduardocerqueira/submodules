# git submodules

testing git [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

```
# adding new modules
git submodule add https://github.com/eduardocerqueira/notes.git <path>

# clonning
# option 1
git clone https://github.com/eduardocerqueira/submodules.git
cd submodule
git submodule update

# option 2
git clone --recurse-submodules https://github.com/eduardocerqueira/submodules.git
```
