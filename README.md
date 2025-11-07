# Nipah Competition IPSAE Pipeline

![](https://framerusercontent.com/images/SYMSDnQhfwOdIm0UAiiFGkyfGA.png?scale-down-to=1024&width=1500&height=878)


We are computing the [ipSAE](https://www.biorxiv.org/content/10.1101/2025.02.10.637595v1) (interaction prediction Score from Aligned Errors) on each submission and the average across your collection. Then, the 60 best collections (600 designs) given the average ipSAE will be considered for wet-lab validation.

This score is computed on a structure prediction using the [Boltz2 method](https://github.com/jwohlwend/boltz)

In this repository we make available the pipeline and a precompute MSA so you can check your sequences before submission. Simply use the below link to open the Google Colab notebook and paste in your sequence. 

<a target="_blank" href="https://colab.research.google.com/github/adaptyvbio/nipah_ipsae_pipeline/blob/main/Boltz-IPSAE.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


--- 
Submit to the competition on [Proteinbase](https://proteinbase.com/competitions/adaptyv-nipah-competition)
