# Decide less, communicate more: On the construct validity of end-to-end fact-checking in medicine

This is the repository where we release the annotation data and interface described in our paper: "Decide less, communicate more: On the construct validity of end-to-end fact-checking in medicine".

![Task Overview](img/Task_fig.png)

Please contact Sebastian Joseph (sebaj@utexas.edu) or Lily Chen (l1ly@mit.edu) if you need access to any of the data or code not found in this repository.

# Annotation Interface
To explore the annotations:
1. Visit the viewer [Annotation Interface](https://sebajoe.github.io/redhot_viewer/)
2. Upload the corresponding `.json` file from the `annotation_data/` or `retrieval_test/` folders

![Claims](img/claims.png)
![PIO Elements](img/pios.png)
![Tiers](img/tiers.png)
![Label and Explanation](img/exps.png)
![Abstract Level Annotations](img/abs.png)

> 💡 If you'd like to perform your own annotations using the interface, ensure your data follows the same `.json` format as used in this study. For annotation instrcutions used in our study, see this [presentation](https://docs.google.com/presentation/d/1hz-jw6UKyi0cDkzWuJoKoLTYP4ejuqwR-WPpuZMTg7o/edit?slide=id.g33d47a9936b_0_0#slide=id.g33d47a9936b_0_0).

# Repository Structure
`annotation_data/` 
* Annotations from six annotators
* Covers three splits:
  * Split 1: First pilot set of 10 claims
  * Split 2: Refinement set of 5 claims
  * Split 3: Final set of 5 claims
* Filenames follow the format `<annotatorID>_split<splitNumber>.json` (e.g., `3_split1.json`)

`retrieval_test/` 
* Contains `.json` files for eight different RCT abstract retrieval strategies
* `relevance_anno/` has eight `.json` files with the relevance annotated for each RCT abstract

`redhot_viewer`
* Linked repository containing the source code for the annotation interface

# Citation
If you found any of these resources useful, please consider citing our paper.
Coming soon.
