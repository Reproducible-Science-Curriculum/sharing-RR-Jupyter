# sharing-RR-Jupyter

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
