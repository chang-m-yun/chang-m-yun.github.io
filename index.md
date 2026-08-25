---
layout: default
---
# Bio:
I am a PhD candidate in [Chemical Engineering](https://cheme.stanford.edu/) at Stanford University. 

I am advised by [Anshul Kundaje](https://kundajelab.github.io/) in Computer Science & Genetics, and co-advised by [Brian Hie](https://evodesign.org/) in Chemical Engineering & Data Science. 

__My interest is in all things DNA 🧬, proteins 🧪, and engineering 🤖.__

My current research focuses on understanding the interface of DNA and proteins at molecular-scale using deep learning methods.

Previously, I worked in management consulting at [Bain & Company](https://www.bain.com/) as an Associate Consultant in the pharma, healthcare & med tech practice.

For my Master's degree, I studied [Biotechnology](https://www.ceb.cam.ac.uk/) at the University of Cambridge, advised by [Graham Christie](https://www.ceb.cam.ac.uk/directory/graham-christie), investigating in engineering bacterial endospores for DNA data storage.

For my undergraduate degree, I studied [Chemical Engineering](https://www.cheme.columbia.edu/) at Columbia University, advised by [Ponisseril Somasundaran](https://blogs.cuit.columbia.edu/ps24/), investigating electrocatalytic reduction of CO2 using non-toxic, earth-abundant metals. I was an [Egleston Scholar](https://www.engineering.columbia.edu/academics/programs/undergraduate-programs/egleston-scholars-program/class-2020-egleston-scholars) in the Fu Foundation School of Engineering and Applied Sciences.

My other interests include [craft beers](https://brewery304.com/) 🍺, [oil painting](https://www.instagram.com/hands.and_lines/) 🎨 and skiing ⛷️.

_For more, see more below._

---
# Current projects:
## ENCODE GRAMMAR (Genomic Regulatory Atlas of sequence Models, Motifs, Annotations and Rules): A deep learning model resource for decoding the DNA sequence logic of regulatory elements in the human genome
![Figure: ENCODE GRAMMAR: A deep learning resource that transforms the extensive ENCODE compendium of genome-wide biochemical profiling experiments into predictive models and interpretable regulatory sequence annotations: (1) ENCODE experiments measure complementary layers of gene regulation, including TF binding by TF ChIP–seq, chromatin accessibility by DNase-seq and ATAC-seq, transcription initiation by PRO-cap, and sequence-driven regulatory activity by MPRAs. (2) Deep learning models from the BPNet family (BPNet, ChromBPNet, ProCapNet, and ReporterNet) are trained separately for each experiment and cellular context to predict the corresponding biochemical signal directly from local DNA sequence. (3) Product resources released for each experiment include the trained models; predicted, base-resolution biochemical profiles; sequence-contribution maps identifying bases that drive model predictions; recurring predictive sequence motifs; genomic motif instances; and predicted effects of genetic variants obtained by comparing reference and alternate allele sequences..](/assets/img/project_encode_grammar.png)
__Figure:__ ENCODE GRAMMAR: A collection of 3,865 regulatory DNA seq2func models trained on TF binding, chromatin accessibility, transcription initiation, and reporter assays across ENCODE, each with full model predictions and interpretations.

- __Blog post__: [Link](https://genomicsxai.github.io/blogs/2026-012/)
- __Main ENCODE 4 Preprint__: [Link](https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1)
- __Technical Note__: [Link](https://doi.org/10.5281/zenodo.17123347)
- __User-friendly resources__:
  - Models on __Hugging Face__: [Link](https://huggingface.co/collections/kundajelab/encode-bpnet-models) 
  - Tracks on __UCSC Genome Browser__: [Link](https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&hubUrl=https://kundajelab.github.io/ucsc-trackhub-encode.github.io/hub.txt)
  - All resources on __ENCODE Portal__: [Link](https://encodeproject.org/search/?type=Annotation&annotation_type=BPNet-model&annotation_type=ChromBPNet-model&status=released)

---
## A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays
![Figure: ENCODE MotifCompendium: A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays across ENCODE.](/assets/img/project_mc_encode.png)
![Figure: MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale.](/assets/img/project_mc_main.png)
__Figure:__ MotifCompendium: A GPU-accelerated Python package for clustering, annotating, and managing motifs, at scale. Across ENCODE GRAMMAR, we collapsed 286,836 deep learning contribution-based motifs into a single, non-redundant set of 3,384 unique motif patterns that capture TF binding and chromatin accessibility activity.

- __Technical Note__: [Link](https://doi.org/10.5281/zenodo.17123347) 
- __GitHub__: [Link](https://github.com/kundajelab/motifcompendium) 

---
## JASPAR 2026: expansion of transcription factor binding profiles and integration of deep learning models
![Figure: JASPAR 2026: Deep learning collection.](/assets/img/project_jaspar.jpg)
__Figure:__ JASPAR 2026: Deep learning collection: Characterizes TF–DNA interactions with 1,259 BPNet models trained on Homo sapiens ENCODE chromatin immunoprecipitation followed by sequencing (ChIP-seq) datasets from 240 TFs and interpreted to reveal predictive motif patterns for the models. The motifs associated with the same TF were clustered to provide a summary of the binding properties, resulting in 240 primary and 113 alternative motif patterns in the DL collection. The top panel illustrates the comprehensive workflow. The bottom panels present screenshots of the TF summary profile page (left) and the model page (right).

- __Publication__: [Link](https://doi.org/10.1093/nar/gkaf1209) 
- __JASPAR: Deep Learning Collection__: [Link](https://jaspar.elixir.no/collection/deep-learning/) 

---
# Past projects:
## Designing _de novo_ bacterial toxin-antitoxins using a generative genomic foundation model
![Figure: Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model.](/assets/img/project_tat.png)
__Figure:__ Strategy for de novo design of Type II toxin-antitoxins using a genomic foundation model. (a) Mechanism of Type II toxin-antitoxins. (b) High-level overview of the strategy for designing novel Type II toxin-antitoxins to expand the existing repertoire.

- __GitHub__: [Link](https://github.com/chang-m-yun/CS273B_TA_Evo)  

---
## Predicting post-transcriptional ADAR activity using a language model
![Figure: Adenosine Deadmidase acting on RNA (ADAR) activity.](/assets/img/project_adar.png)  
__Figure:__ Adenosine Deadmidase acting on RNA (ADAR) activity.

- __GitHub__: [Link](https://github.com/chang-m-yun/CS229_final_project/)

---
# Publications:
### [A unified lexicon of predictive DNA sequence motifs from ENCODE transcription factor binding and chromatin accessibility assays (Technial Note)](https://doi.org/10.5281/zenodo.17123347)
__Chang M. Yun\*__, Salil Deshpande\*, Vivekanandan Ramalingam\*, Vivian Hecht\*, Aman Patel\*, Anusri Pampari\*, Selin Jessa, Ryan Zhao, Austin Wang, Anshul Kundaje^.  
[_Zenodo_, August 2026]((https://doi.org/10.5281/zenodo.17123347)).  

### [The Encyclopedia of DNA Elements](https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1)
__The ENCODE Project Consortium\*__; Timothy E. Reddy\*.  
[_bioRxiv_, July 2026](https://www.biorxiv.org/content/10.64898/2026.07.06.731365v1).  

### [Decoding common and rare noncoding variant effects across cellular and developmental contexts](https://www.nature.com/articles/s41588-026-02619-6)
Andrew R. Marderstein\*, Soumya Kundu\*, Evin M. Padhi, Salil Deshpande, Austin Wang, Esther Robb, Ying Sun, __Chang M. Yun__, Diego Pomales-Matos, Yilin Xie, Serena H. Chang, Iris M. Chin, Aayushi J. Shah, Zachary A. Gardell, M. Ryan Corces, Daniel Nachun, Selin Jessa, Anshul Kundaje^ & Stephen B. Montgomery^.  
[_Nature Genetics_, June 2026](https://www.nature.com/articles/s41588-026-02619-6).  

### [JASPAR 2026: expansion of transcription factor binding profiles and integration of deep learning models](https://academic.oup.com/nar/article/54/D1/D184/8343514)
Damla Ovek Baydar\*, Ieva Rauluseviciute\*, Dina R Aronsen, Romain Blanc-Mathieu, Ine Bonthuis, Herman de Beukelaer, Katalin Ferenc, Alice Jegou, Vipin Kumar, Roza Berhanu Lemma, Jérémy Lucas, Mathis Pochon, __Chang M. Yun__, Vivekanandan Ramalingam, Salil Sanjay Deshpande, Aman Patel, Georgi K Marinov, Austin T Wang, Alejandro Aguirre, Jaime A Castro-Mondragon, Damir Baranasic, Jeanne Chèneby, Sveinung Gundersen, Morten Johansen, Aziz Khan, Marieke L Kuijjer, Eivind Hovig, Boris Lenhard^, Albin Sandelin^, Klaas Vandepoele^, Wyeth W Wasserman^, François Parcy^, Anshul Kundaje^, Anthony Mathelier^.  
[_Nucleic Acids Research_, January 2026](https://academic.oup.com/nar/article/54/D1/D184/8343514).  

### [Robust Electroreduction of CO2 at a Poly(4-vinylpyridine)–Copper Electrode](https://chemistry-europe.onlinelibrary.wiley.com/doi/full/10.1002/celc.201500421)
Sathish Ponnurangam\*, __Chang Min Yun__, Irina V. Chernyshova^.  
[_ChemElectroChem_, October 2015](https://chemistry-europe.onlinelibrary.wiley.com/doi/full/10.1002/celc.201500421).  

---
# Teaching:
### [Data Science and Machine Learning Approaches in Chemical and Materials Engineering (CHEMENG 177/277, MATSCI 166/176) [Winter 2026]](https://explorecourses.stanford.edu/search?q=CHEMENG+177%3a+Data+Science+and+Machine+Learning+Approaches+in+Chemical+and+Materials+Engineering&view=catalog&page=0&filter-coursestatus-Active=on&collapse=&academicYear=20252026)
As Course assistant (CA); Instructor: Brian Hie.

### [Data Science and Machine Learning Approaches in Chemical and Materials Engineering (CHEMENG 177/277, MATSCI 166/176) [Winter 2027]](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&q=CHEMENG+177%3A+Data+Science+and+Machine+Learning+Approaches+in+Chemical+and+Materials+Engineering&collapse=)
As Course assistant (CA); Instructor: Brian Hie.
