---
layout: default
---
## Bio:
Hi! I'm a PhD candidate in Chemical Engineering at Stanford University. I'm advised by Anshul Kundaje in Computer Science & Genetics, and co-advised by Brian Hie in Chemical Engineering & Data Science. 

__My interest is in all things DNA 🧬, proteins 🧪, and engineering 🤖.__

My current research focuses on understanding the interface of DNA and proteins at molecular-scale using deep learning methods.

I briefly worked in consulting at Bain & Company as an Associate Consultant in the pharma, healthcare & med tech practice.

For my Master's, I studied at the University of Cambridge in Biotechnology, advised by Graham Christie, investigating in engineering bacterial endospores for DNA data storage.

For my undergraduate, I studied at Columbia University in Chemical Engineering, advised by Ponisseril Somasundaran, investigating electrocatalytic reduction of CO2 using non-toxic, earth-abundant metals.  

Feel free to reach out: [X](https://x.com/chang_m_yun), [LinkedIn](https://www.linkedin.com/in/chang-m-yun/), or email (chang.m.yun [at] stanford [dot] edu)!

## Current projects:
#### ENCODE GRAMMAR (Genomic Regulatory Atlas of sequence Models, Motifs, Annotations and Rules): A deep learning model resource for decoding the DNA sequence logic of regulatory elements in the human genome
![Figure: ENCODE GRAMMAR: A deep learning resource that transforms the extensive ENCODE compendium of genome-wide biochemical profiling experiments into predictive models and interpretable regulatory sequence annotations: (1) ENCODE experiments measure complementary layers of gene regulation, including TF binding by TF ChIP–seq, chromatin accessibility by DNase-seq and ATAC-seq, transcription initiation by PRO-cap, and sequence-driven regulatory activity by MPRAs. (2) Deep learning models from the BPNet family (BPNet, ChromBPNet, ProCapNet, and ReporterNet) are trained separately for each experiment and cellular context to predict the corresponding biochemical signal directly from local DNA sequence. (3) Product resources released for each experiment include the trained models; predicted, base-resolution biochemical profiles; sequence-contribution maps identifying bases that drive model predictions; recurring predictive sequence motifs; genomic motif instances; and predicted effects of genetic variants obtained by comparing reference and alternate allele sequences..](/assets/img/project_encode_grammar.png)
___Figure:___ _ENCODE GRAMMAR: A collection of 3,865 regulatory DNA seq2func models trained on TF binding, chromatin accessibility, transcription initiation, and reporter assays across ENCODE, each with full model predictions and interpretations._

- __Blog post__: [https://genomicsxai.github.io/blogs/2026-012/](https://genomicsxai.github.io/blogs/2026-012/)
- __Main ENCODE 4 Preprint__: [https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1](https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1)
- __Technical Note__: [https://doi.org/10.5281/zenodo.17123347](https://doi.org/10.5281/zenodo.17123347)
- __User-friendly resources__:
  - Models on Hugging Face: [https://huggingface.co/collections/kundajelab/encode-bpnet-models](https://huggingface.co/collections/kundajelab/encode-bpnet-models) 
  - Tracks on UCSC Genome Browser: [https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&hubUrl=https://kundajelab.github.io/ucsc-trackhub-encode.github.io/hub.txt](https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&hubUrl=https://kundajelab.github.io/ucsc-trackhub-encode.github.io/hub.txt)
  - All resources on ENCODE Portal: [https://encodeproject.org/search/?type=Annotation&annotation_type=BPNet-model&annotation_type=ChromBPNet-model&status=released](https://encodeproject.org/search/?type=Annotation&annotation_type=BPNet-model&annotation_type=ChromBPNet-model&status=released)

---
#### A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays
![Figure: MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale.](/assets/img/project_mc_main.png)
![Figure: ENCODE MotifCompendium: Pipeline process.](/assets/img/project_mc_pipeline.png)
___Figure:___ _MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale. Example process collapsing FOX dimer motif, starting from TF ChIP-seq BPNet-derived motifs into ENCODE TF MotifCompendium pattern. The process was completed on the ENCODE Project, across 19,739 TF ChIP-seq BPNet-derived motifs, resulting in 1,921 unique motif patterns._

- __Technical Note__: [https://doi.org/10.5281/zenodo.17123347](https://doi.org/10.5281/zenodo.17123347) 
- __GitHub__: [https://github.com/kundajelab/motifcompendium](https://github.com/kundajelab/motifcompendium) 

---
#### JASPAR 2026: expansion of transcription factor binding profiles and integration of deep learning models
![Figure: JASPAR 2026: Deep learning collection.](/assets/img/project_jaspar.jpg)
___Figure:___ _JASPAR 2026: Deep learning collection: Characterizes TF–DNA interactions with 1,259 BPNet models trained on Homo sapiens ENCODE chromatin immunoprecipitation followed by sequencing (ChIP-seq) datasets from 240 TFs and interpreted to reveal predictive motif patterns for the models. The motifs associated with the same TF were clustered to provide a summary of the binding properties, resulting in 240 primary and 113 alternative motif patterns in the DL collection. The top panel illustrates the comprehensive workflow. The bottom panels present screenshots of the TF summary profile page (left) and the model page (right)._

- __Publication__: [https://doi.org/10.1093/nar/gkaf1209](https://doi.org/10.1093/nar/gkaf1209) 
- __JASPAR: Deep Learning Collection__: [https://jaspar.elixir.no/collection/deep-learning/](https://jaspar.elixir.no/collection/deep-learning/) 

## Past projects:
#### Designing _de novo_ bacterial toxin-antitoxins using a generative genomic foundation model
![Figure: Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model.](/assets/img/project_tat.png)
___Figure:___ _Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model. (a) Mechanism of Type II toxin-antitoxins. (b) High-level overview of the strategy for designing novel Type II toxin-antitoxins to expand the existing repertoire._

- __GitHub__: [https://github.com/chang-m-yun/CS273B_TA_Evo](https://github.com/chang-m-yun/CS273B_TA_Evo)  

---
#### Predicting post-transcriptional ADAR activity using a language model
![Figure: Adenosine Deadmidase acting on RNA (ADAR) activity.](/assets/img/project_adar.png)  
___Figure:___ _Adenosine Deadmidase acting on RNA (ADAR) activity_

- __GitHub__: [https://github.com/chang-m-yun/CS229_final_project/](https://github.com/chang-m-yun/CS229_final_project/)
