---
---

## Welcome to the SynthBioLab!

The SynthBioLab fuses synthetic biology with machine learning to drive applied and translational research. We design biological components and systems, harnessing generative AI to refine and decode the blueprints of life. Our goal is bold: to revolutionize bioengineering, healthcare, and environmental tech. Our commitment is not just to innovate in specific areas but to remove the boundaries of traditional silos of discreet disciplines to pave the way for a new era of biotechnological advancements.

<!-- {%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%} -->

{% include section.html %}

## Our Research

{% capture text %}

The ability to equip genomes with novel properties offers potential for addressing questions not easily approachable with conventional gene-at-a-time methods. This include questions about evolution and about how genomes are wired logically, metabolically, and genetically. While DNA remains the foundation of biological engineering, and innovations like CRISPR have transformed genome targeting. Nevertheless, challenges persist in designing DNA that successfully expresses functional heterologous, AI-enhanced proteins, especially challenging when engineering large biochemical pathways. Using generative AI, we design genomic DNA aiming to expand to entire chromosomes, encoding sustainable processes, altogether getting us closer to synthetic life. 

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/bioengineering2.png"
  link=null
  title="Generative Engineering Biology: Genes and Beyond"
  text=text
%}

{% capture text %}

At the heart of every cellular function lies the intricacy of protein expression. Leveraging the power of machine learning and high-throughput microfluidic technologies, we are deciphering the mechanisms of protein expression, regulation, and control. By mastering the machinery of gene expression, we aim to control biological systems, enhance their efficiency and adapt to diverse applications, from discovering efficient product-specific expression hosts to precision control of gene expression – paving the way for more targeted and effective gene therapies.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/gene_expression.png"
  link="projects"
  title="Control of Gene Expression: Towards Targeted Gene Therapies"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our planet's microbiome is a parallelly evolving universe of enzymes, many of which remain undiscovered or underutilised for human applications. Recognising this enormous potential, we are on a quest to explore the planet's enzymatic repertoire. Particularly, we're focused on harnessing microbiome enzymes for bioremediation, currently working on plastic degrading enzymes towards developing feasible, sustainable approaches to remove environmental contaminants or convert them to useful products.


{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/plastics2.png"
  link="team"
  title="Tapping into the Planet's Enzymatic Repertoire for Bioremediation"
  text=text
%}
