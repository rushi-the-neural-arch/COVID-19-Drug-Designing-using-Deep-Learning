# SAMHAR-COVID-19

## Summary

This repository is made in lieu of submission in SAMHAR hackathon. 

## Objective

* Deep Learning aided COVID-19 vaccine development solution
* To identify ligands and genome sequences having high docking score with the COVID-19 strand(s)
* Ultimately suggest an existing FDA approved drug OR re-purposed existing FDA approved drug OR a new drug as a vaccine to the COVID-19

## Solution Architecture

A new coronavirus (CoV) identified as COVID-19 virus is the etiological agent responsible for the 2019-2020 viral pneumonia outbreak that commenced in Wuhan. Currently there are no targeted therapeutics and effective treatment options remain
very limited. Rigorous efforts are continuously being made by scientists and researchers all over the world to find molecules which can serve as a potential antidote. But practically, there are millions of compounds and such an exhaustive approach manually is extremely difficult and infeasible. Moreover, it might be very well possible that all the current drugs may not be an effective cure for this pandemic disease. This is where the role of AI comes in to help in the pursuit of discovering/generating an antidote. We propose a novel Composite Deep Learning solution consisting of a predictive network architecture and a novel interleaved GAN architecture to Predict and Generate potential antidotes.

## Modules

### Predictive Deep Learning Model

This model tries to cross reference the existing ligands and strands that fall in the genome family of COVID-19 (SARS-2) for highest docking score, and suggests a potential vaccine from the existing drugs.

### Generative Deep Learning Network

Here, we propose a novel interleaved GAN architecture that generates new potential drugs using the Generative model which maps from the latent space of proven molecules like N3, Ebselen which act as a potential inhibitor.

### Docking Evaluation & Deployment

Finally, the predicted and generated molecules can be evaluated by docking them with various enzymes and proteins essential for survival of CoV(for instance M proteinase) of CoV and can be further sent for synthesis or clinical trials and FDA tests can be conducted.

## Built With

* PyTorch
* Fast.ai
* Tensorflow

## Datasets

The following datasets are being used to train the Predictive and Generative model.

* [MOSES] (https://github.com/molecularsets/moses)
* [ChemBL] (https://www.ebi.ac.uk/chembl/)
* [Harmonizome] (http://amp.pharm.mssm.edu/Harmonizome/)

## Code & Literature
[add colab link and report link here]:

* [Google Colab Notebook - Starter Implementaion](https://colab.research.google.com/drive/1NnsEVRVaD2dKnTWtP4p5iPtiQ8fxpkEG?usp=sharing)
* [Detailed Report and Summary](https://docs.google.com/document/d/1IWB2wr_uuvgtudyrmNasx1orrYP3pm9mvvEdRHGbUvk/edit?usp=sharing)

## Contribution

Please feel free to raise issues and fix any existing ones. Further details can be found in our [code of conduct](https://github.com/Chintan2108/Text-Classification-and-Context-Mining-for-Document-Summarization/blob/master/CODE_OF_CONDUCT.md).

## References

We gratefully thank all the researchers and developers who constantly work hard and open-source their findings to develop the solution to battle this pandemic to find better cure or vaccination. The above-proposed work is made possible only because of their initial and continuous research and findings.

[Structure of Mpro from COVID-19 virus and discovery of its inhibitors](https://www.nature.com/articles/s41586-020-2223-y)

[Building Attention and Edge Convolution Neural Networks for Bioactivity and Physical-Chemical Property Prediction](https://chemrxiv.org/articles/Building_Attention_and_Edge_Convolution_Neural_Networks_for_Bioactivity_and_Physical-Chemical_Property_Prediction/9873599/2)

https://github.com/edvardlindelof/graph-neural-networks-for-drug-discovery

[Constrained Graph Variational Autoencoders for Molecule Design](https://arxiv.org/pdf/1805.09076.pdf)

https://github.com/microsoft/constrained-graph-variational-autoencoder​

[The crystal structure of COVID-19 main protease in complex with an inhibitor N3](https://www.rcsb.org/structure/6LU7)

https://github.com/schrodinger/pymol-open-source

​https://pymol.org/2/

​https://www.ncbi.nlm.nih.gov/pcassay/advanced​

http://vina.scripps.edu/download.html

[Generative Recurrent Networks for De Novo Drug Design](https://onlinelibrary.wiley.com/doi/full/10.1002/minf.201700111)
        
https://github.com/topazape/LSTM_Chem 

https://github.com/molecularsets/moses 

https://www.ebi.ac.uk/chembl/ 

http://amp.pharm.mssm.edu/Harmonizome/ 

https://pymol.org/2/ 
 
[tinkavidovic/competition](https://github.com/tinkavidovic/competition)



