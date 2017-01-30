# Yet Another (Biostatistics) M.A. Thesis

> "Targeted Data-Adaptive Estimation of Local Treatment Effects with
> Applications in Genomics," a masters thesis submitted in partial satisfaction
> of the requirements for the M.A. in Biostatistics, at U.C. Berkeley, by [Nima
> Hejazi](http://nimahejazi.org).

---

## Summary

This thesis presents a generalized method for using Targeted Minimum Loss-Based
Estimation (TMLE) to...

---

## Contents

* Chapter 1: Causal inference in high-dimensional biology

* Chapter 2: The local average treatment effect parameter

* Chapter 3: Applications to the study of DNA methylation

* Chapter 4: Software module - the "methadapt" R package

---

## Related

* [`methadapt`](https://github.com/nhejazi/methadapt/tree/master) - an R
    package implementing a specific realization of the local average treatment
    effect parameter (discussed in this thesis), designed to provide inference
    on CpG sites based on data produced by DNA methylation assays.

---

## Compilation

* `make all` - compile the thesis document, generating two subdirectories: `pdf`
    (containing the thesis and approval page in PDF) and `output` (containing
    auxiliary documents created in the compilation process).

* `make clean` - removes the subdirectories generated by the use of `make all`.

_N.B._, a functional installation of a LaTeX distribution (_e.g._,
[MacTeX](http://www.tug.org/mactex/)) is required to compile this thesis
document.

---

## License

&copy; 2017 [Nima Hejazi](http://nimahejazi.org)

The contents of this repository are released under a <a rel="license"
href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img
alt="Creative Commons License"
style="border-width:0"
src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a>

A human-readable version of the CC BY-NC-SA 4.0 license is available
[here](https://creativecommons.org/licenses/by-nc-sa/4.0/); the full license may
be examined [here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).
