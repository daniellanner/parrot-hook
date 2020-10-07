# How to use

In case of repositories with a collection of tools or submodules this script creates a table of all `README.md` files available.

## Introduction

The script walks over the repository and collects the `## Introduction` segment of all `README.md` files and creates a table of them in the root level `README.md` file.

## Further options

Per default the table is appended to the end of the file. To manually place the table within your main `README.md` you can add html comments in the file. Add \<!-- start generated table -->\n
and \<!-- end generated table -->\n to the file, the table will be generated between those lines.
