# hydra-lite
I like Hydra, but it just does too much. Stripping out the parts I like since that's probably less headache than fighting default behaviors all the time.

**DISCLAIMER: THIS IS A WORK IN PROGRESS**. will remove this disclaimer when it's ready for use.

## Intended Features

* SDK backwards compatibility. Should be a drop in replacement, a la `import hydra_lite as hydra` is all you need to add at top of file (or at least before hydra imports)
* Hierarchical nested configs
* CLI override
* current working directory is default location for configs
* simple customization

## Stuff I don't want

* automated working directory changing/renaming and output capture/redirection
* installation directory is default location for configs
* complex macro registration system
