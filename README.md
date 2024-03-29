# Replication of [Simulating socioeconomic-based affirmative action](https://doi.org/10.1002/pam.22056)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10255347.svg)](https://doi.org/10.5281/zenodo.10255347)

Louis Béziaud, 2022

> Reardon, S.F., Baker, R., Kasman, M., Klasik, D. and Townsend, J.B. (2018), What Levels of Racial Diversity Can Be Achieved with Socioeconomic-Based Affirmative Action? Evidence from a Simulation Model. J. Pol. Anal. Manage., 37: 630-657. https://doi.org/10.1002/pam.22056

The code to reproduce the figures is located in another [repository](https://github.com/lbeziaud/mosaic).

The files contained in the sub-directory figures_original/ are from the [CEPA Working Paper No. 15-04](https://cepa.stanford.edu/sites/default/files/wp15-04-v201712.pdf).

### [ReScience C](https://rescience.github.io/) article template

This repository contains the Latex (optional) template for writing a ReScience
C article and the (mandatory) YAML metadata file. For the actual article,
you're free to use any software you like as long as you enforce the proposed
PDF style. A tool is available for the latex template that produces latex
definitions from the metadata file. If you use another software, make sure that
metadata and PDF are always synced.

You can also use overleaf with the [provided template](https://www.overleaf.com/read/kfrwdmygjyqw) but in this case, you'll have to enter `metadata.tex` manually.

#### Usage

For a submission, fill in information in
[metadata.yaml](./metadata.yaml), modify [content.tex](content.tex)
and type:

```bash
$ make 
```

This will produce an `article.pdf` using xelatex and provided font. Note that you must have Python 3 and [PyYAML](https://pyyaml.org/) installed on your computer, in addition to `make`.


After acceptance, you'll need to complete [metadata.yaml](./metadata.yaml) with information provided by the editor and type again:

```bash
$ make
```

(C) 2015-2020, Nicolas Rougier + co-authors GPL-3+, Apache v2+, SIL Open Font License

This set of template files is free-licensed. The files contained in
the sub-directories roboto/; source-code-pro/; source-sans-pro/;
source-serif-pro/; have their free licences indicated with a
"*License.txt" file. All other files, including this one, are licensed
under the GPL version 3 or later, at your choosing, by Nicolas Rougier
and co-authors, 2015-2020. See the file COPYING for details of the
GPL-3 licence.
