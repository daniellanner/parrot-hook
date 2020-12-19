# Readme Summary

This repository contains a python script to automatically edit the root level `README.md` file of a repository and a combination of pre-commit and post-commit git hooks to automise the process. This `README.md` has been created this way.

This text is before the generated table.

## Table of Content

<!-- start generated table -->
generated from commit d36f38b6a2defd17ab7d41d2a4e23dfaa5a560d1  
on 2020-12-19 at 17:02:39

[How to install](how-to-install/README.md)  

In your local git repository locate the folder `.git/hooks/`. Copy the `pre-commit` and `post-commit` from this repository into the hooks folder.  

[How to use](how-to-use/README.md)  

The script walks over the repository, collects the `h2 Introduction` segment of all `README.md` files and creates a content table in the root level `README.md` file.  

[HTTP Links](how-to-use/links/http/README.md)  
The following link is an http URL and will be resolved in the main README

![](https://images.unsplash.com/photo-1560939509-af421a48c187?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80)

<span>Photo by <a href="https://unsplash.com/@vivekdoshi?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Vivek Doshi</a> on <a href="https://unsplash.com/s/photos/parrot?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>  

[Relative Links](how-to-use/links/relative/README.md)  
The following link is relative and will be resolved in the main README

![](how-to-use/links/relative/img/rel_parrot.jpg)

<span>Photo by <a href="https://unsplash.com/@jenn_jpeg?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Jenn.jpeg</a> on <a href="https://unsplash.com/s/photos/parrot?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>  

<!-- end generated table -->

This text is after the generated table.


## Limitations
- This entire thing was hacked together and not properly tested yet so expect some bugs.
- Relative links in the generated table are not resolved.
- use of **powershell** sh command limits platform to Windows, to work around the issue download python script to your machine and call directly from pre-commit file
