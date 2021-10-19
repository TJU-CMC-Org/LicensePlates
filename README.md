# MINTplates: codes for minting "license plates"

"License Plates" are invariant strings that can be used to label uniquely and unambiguously nucleic acid sequences (DNA and RNA). We originally proposed *license plates* as a labeling scheme for tRNA-derived fragments - see: [*MINTbase: a framework for the interactive exploration of mitochondrial and nuclear tRNA fragments*](https://pubmed.ncbi.nlm.nih.gov/27153631/). We have since extended the labeling scheme to:
- rRNA-derived fragments (rRFs) - see: [*Ribosomal RNA fragmentation into short RNAs (rRFs) is modulated in a sex- and population of origin-specific manner*](https://pubmed.ncbi.nlm.nih.gov/32279660/)
- microRNA (miRNA) and miRNA isoforms (isomiRs) - see [*IsoMiRmap-fast, deterministic, and exhaustive mining of isomiRs from short RNA-seq datasets*](https://pubmed.ncbi.nlm.nih.gov/33471076/)

**Local Installation:** By downloading the "MINTplates" code (Python) and installing it on your computer, you can do one of two things:
- generate license plates for your favorite nucleotide sequences; or,
- recover the nucleotide sequence that corresponds to a license plate.

**Web-based interface:**  If you would rather not install these codes, you can still generate *license plates* for your favorite nucleotide sequence(s) through our web portal at [https://cm.jefferson.edu/LicensePlates/](https://cm.jefferson.edu/LicensePlates/). 

For the latest version of the code, including pre-releases, visit [https://cm.jefferson.edu/license-plates-download/](https://cm.jefferson.edu/license-plates-download/).


## General Information
This code was created by Venetia Pliatsika, Isidore Rigoutsos, Jeffery Ma, and Phillipe Loher. To learn more about the *license plate* encoding, you can:
- look at the above mentioned publications
- visit [https://cm.jefferson.edu/license-plates-download/](https://cm.jefferson.edu/license-plates-download/)

## Contact 
[https://cm.jefferson.edu/contact-us/](https://cm.jefferson.edu/contact-us/)

## License and Terms of Use
- If you use this tool, please cite: [Pliatsika et al, "MINTbase: a framework for the interactive exploration of mitochondrial and nuclear tRNA fragments", *Bioinformatics*, 2016](https://pubmed.ncbi.nlm.nih.gov/27153631/)
- This MINTplates package is available under the open source GNU GPL v3.0 license ( [https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html)  ).


THE CODE IS PROVIDED "AS IS" WITH NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, EITHER EXPRESSED
OR IMPLIED. TO THE FULLEST EXTENT PERMISSIBLE PURSUANT TO APPLICABLE LAW. THOMAS JEFFERSON
UNIVERSITY, AND ITS AFFILIATES, DISCLAIM ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF TITLE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NON-INFRINGEMENT.


NEITHER THOMAS JEFFERSON UNIVERSITY NOR ITS AFFILIATES MAKE ANY REPRESENTATION AS TO THE RESULTS
TO BE OBTAINED FROM USE OF THE CODE.

## Usage Information

Usage (Python 2 and 3 compatible):

    python MINTplates.py example_sequences_to_encode.txt en --p [prefix to add to license plate]
    python MINTplates.py example_license_plates_to_decode.txt de --p [optional prefix, not used in decoding]
