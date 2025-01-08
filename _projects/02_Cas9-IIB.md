---
layout: page
title: PseCas9
description: A sticky-cutter enzyme from Cas9-IIBs
img: assets/img/projects/PseCas9.jpeg
importance: 2
category: work
related_publications: true
---

<h3>Background - CRISPR-Cas in bacteria </h3>
CRISPR-Cas9 was originally adapted from bacterial systems for precise genome editing in human cells. The discovery of CRISPR-Cas9 systems was driven by the pioneering work of Prof. Jennifer Doudna and Prof. Emmanuelle Charpentier, who sought to understand how bacteria acquire immunity against phages.

In prokaryotes, CRISPR-Cas systems are multi-component complexes comprising one or more Cas proteins (e.g., Cas1, Cas2) and short RNAs (e.g., crRNA and tracrRNA). Together, these components form a RiboNucleoProtein (RNP) complex. In most bacteria, multiple Cas proteins collaborate to identify and destroy the genetic material of invading viruses. However, in a small subset of bacteria, a single protein, Cas9, performs all the necessary functions to locate and eliminate the invading genomes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/CRISPR-Cas9_origin.png" title="CRISPR origin" class="img-fluid rounded z-depth-1" %}   
    </div>
</div>

<div class="caption">
    CRISPR-Cas9 originates from bacterial immune system {% cite shamshirgaran2022tools %}.
</div>


<h3>The challenge - harnessing novel CRISPR-Cas systems</h3>
To date, the most widely used CRISPR-Cas9 system in human cells is the Cas9 protein discovered in <i>Streptococcus pyogenes</i> (SpyCas9). Adapting new CRISPR-Cas9 systems from prokaryotic cells for use in human cells presents several challenges.

First, correctly identifying RNA species (e.g., crRNA and tracrRNA) from raw, unannotated sequencing data requires multidisciplinary expertise in bioinformatics and molecular biology. Second, fundamental differences in the central dogma of life between prokaryotic and eukaryotic cells add another layer of complexity, particularly when testing the activity of new Cas9 variants in human cells.

<h3>The acheivement</h3>
During my postdoctoral research at AstraZeneca, I contributed to the discovery and adaptation of several Cas9 proteins from the IIB class. We found that Cas9 proteins from this class cut DNA at different positions compared to the commonly used SpyCas9.

While spCas9 generates blunt ends or single-nucleotide overhangs during DNA cleavage, IIB-class Cas9s cleave DNA in a staggered manner, leaving 3- to 5-nucleotide overhangs {% cite bestas2023type %}. This novel nuclease activity has the potential to facilitate the development of more efficient knock-in strategies.

For more details, see patent number: WO2019099943A1