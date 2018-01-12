# Sharing your work with GitHub and Binder

This chapter covers how to share your work with others. It focuses on
setting up a GitHub account and putting your code on a public repository,
as well as adding dependency files to your repository so that you can
share links to an interactive version of your code using Binder.

## Content generation steps

For certain parts, content needs to be re-generated from the source after
you change the source. _The goal is that this happen automatically through
continuous integration ([Travis CI](https://travis-ci.org)) in the future,
but currently it needs to be done manually._

Specifically, after modifying slides in the form of a Jupyter Notebook in the `slides/`
directory, or episodes in the form of a Jupyter Notebook in the `_episodes_notebook/`
directory, run the following command. (You must have Jupyter (and GNU Make)
installed for this to work.)

```sh
$ make lesson-ipynb
```
