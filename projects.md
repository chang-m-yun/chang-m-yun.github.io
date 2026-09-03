---
layout: default
title: Projects
permalink: /projects/
---

# Current projects:

### ENCODE GRAMMAR (Genomic Regulatory Atlas of sequence Models, Motifs, Annotations and Rules): A deep learning model resource for decoding the DNA sequence logic of regulatory elements in the human genome
![Figure: ENCODE GRAMMAR: A deep learning resource that transforms the extensive ENCODE compendium of genome-wide biochemical profiling experiments into predictive models and interpretable regulatory sequence annotations: (1) ENCODE experiments measure complementary layers of gene regulation, including TF binding by TF ChIP–seq, chromatin accessibility by DNase-seq and ATAC-seq, transcription initiation by PRO-cap, and sequence-driven regulatory activity by MPRAs. (2) Deep learning models from the BPNet family (BPNet, ChromBPNet, ProCapNet, and ReporterNet) are trained separately for each experiment and cellular context to predict the corresponding biochemical signal directly from local DNA sequence. (3) Product resources released for each experiment include the trained models; predicted, base-resolution biochemical profiles; sequence-contribution maps identifying bases that drive model predictions; recurring predictive sequence motifs; genomic motif instances; and predicted effects of genetic variants obtained by comparing reference and alternate allele sequences..](/assets/img/project_encode_grammar.png)
__Figure:__ ENCODE GRAMMAR: A collection of 3,865 regulatory DNA seq2func models trained on TF binding, chromatin accessibility, transcription initiation, and reporter assays across ENCODE, each with full model predictions and interpretations.

- __Note__: [GenomicsxAI](https://genomicsxai.github.io/blogs/2026-012/)
- __Main ENCODE 4 Preprint__: [bioRxiv](https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1)
- __Technical Note__: [Zenodo](https://doi.org/10.5281/zenodo.17123347)
- __User-friendly resources__:
  - __Models__: [Hugging Face](https://huggingface.co/collections/kundajelab/encode-bpnet-models)
  - __Tracks__: [UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&hubUrl=https://kundajelab.github.io/ucsc-trackhub-encode.github.io/hub.txt)
  - __All resources__: [ENCODE Portal](https://encodeproject.org/search/?type=Annotation&annotation_type=BPNet-model&annotation_type=ChromBPNet-model&status=released)

---

### A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays
![Figure: ENCODE MotifCompendium: A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays across ENCODE.](/assets/img/project_mc_encode.png)
![Figure: MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale.](/assets/img/project_mc_main.png)
__Figure:__ MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale. Across ENCODE GRAMMAR, we collapsed 286,836 deep learning contribution-based motifs into a single, non-redundant set of 3,384 unique motif patterns that capture TF binding and chromatin accessibility activity.

- __Technical Note__: [Zenodo](https://doi.org/10.5281/zenodo.17123347)
- __GitHub__: [MotifCompendium](https://github.com/kundajelab/motifcompendium)

---

### JASPAR 2026: expansion of transcription factor binding profiles and integration of deep learning models
![Figure: JASPAR 2026: Deep learning collection.](/assets/img/project_jaspar.jpg)
__Figure:__ JASPAR 2026: Deep learning collection: Characterizes TF–DNA interactions with 1,259 BPNet models trained on Homo sapiens ENCODE chromatin immunoprecipitation followed by sequencing (ChIP-seq) datasets from 240 TFs and interpreted to reveal predictive motif patterns for the models. The motifs associated with the same TF were clustered to provide a summary of the binding properties, resulting in 240 primary and 113 alternative motif patterns in the DL collection. The top panel illustrates the comprehensive workflow. The bottom panels present screenshots of the TF summary profile page (left) and the model page (right).

- __Publication__: [Nucleic Acids Research](https://doi.org/10.1093/nar/gkaf1209)
- __JASPAR 2026__: [JASPAR: DL](https://jaspar.elixir.no/collection/deep-learning/)

---
# Past projects:

### Designing _de novo_ bacterial toxin-antitoxins using a generative genomic foundation model
![Figure: Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model.](/assets/img/project_tat.png)
__Figure:__ Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model. (a) Mechanism of Type II toxin-antitoxins. (b) High-level overview of the strategy for designing novel Type II toxin-antitoxins to expand the existing repertoire.

- __GitHub__: [Evo-TA](https://github.com/chang-m-yun/CS273B_TA_Evo)

---

### Predicting post-transcriptional ADAR activity using a language model
![Figure: Adenosine Deadmidase acting on RNA (ADAR) activity.](/assets/img/project_adar.png)
__Figure:__ Adenosine Deadmidase acting on RNA (ADAR) activity.

- __GitHub__: [ADAR-LM](https://github.com/chang-m-yun/CS229_final_project/)
