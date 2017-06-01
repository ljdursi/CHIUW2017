# Chapel's Home in the Landscape of New Scientific Computing Languages
## (and what it can learn from the neighbours)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

This is the presentation and associated materials for my talk 
at [The 4th Chapel Implementers and Users Workshop](http://chapel.cray.com/CHIUW2017.html).
The slides can be viewed directly at http://ljdursi.github.io/CHIUW2017.html .

## Abstract

The last decade has seen an explosion of interest and diversity in
large-scale computing. Many scientists are interested in seizing
the opportunities these emerging new platforms, compiler frameworks,
and languages provide, aiming for bigger simulations, more data,
or higher levels of computational productivity in their research
than had been feasible before.  But with the landscape so quickly
changing and so many new tools becoming available, it is hard to
know where to focus attention. How is a researcher to choose a
language to start a new project in when new possibilities appear
so often? There are new languages for scientific computing like
Julia, which has linear algebra built in but only modest parallel
computing support. There are frameworks like Spark, which is parallel
and cluster-enabled from the beginning, but targeted for data
analysis rather than simulation. There are old stalwarts like R
which grow tendrils into tools like Spark or SCALAPACK; and even
new non-number crunching languages like Rust and Swift are starting
to have scientific computing adherents.

Chapel is a language from Cray that has fields over domains as
first-class entities, allowing for efficient and productive parallel
domain-decomposed computations. Where does Chapel fit in amongst
these new languages; when should a researcher use Chapel, when
should they use one of the others, and what ideas and techniques
are out there that could Chapel usefully adopt? It's these questions
I address in this talk.

I give a brief overview of some of these other platforms and
languages that are being adopted for different types of scientific
computing, and compare them to Chapel in the context of two quite
different types of scientific problems - high speed fluid flow, and
genomic bioinformatics. I discuss pros and cons, when to use
each, and look at what ideas could be poached by Chapel and its
community.
