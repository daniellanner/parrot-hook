# readme summary

This repository contains a python script to automatically edit the root level `README.md` file of a repository and a combination of pre-commit and post-commit git hooks to automise the process. This `README.md` has been created this way.

This text is before the generated table.

<!-- start generated table -->
[How to install](how-to-install/README.md)  

In your local git repository locate the folder `.git/hooks/` and copy the files `pre-commit` and `post-commit`.  

[How to use](how-to-use/README.md)  

The script walks over the repository, collects the `h2 Introduction` segment of all `README.md` files and creates a content table in the root level `README.md` file.  

<!-- end generated table -->

This text is after the generated table.


## Limitations
- This entire thing was hacked together and not properly tested yet so expect some bugs.
- Relative links in the generated table are not resolved.
- use of **powershell** sh command limits platform to Windows, to work around the issue download python script to your machine and call directly from pre-commit file