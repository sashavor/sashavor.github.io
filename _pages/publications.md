---
layout: archive
title: "Full List of Publications"
permalink: /publications/
author_profile: true
---

I publish under my legal name, Alexandra Luccioni. 

2021
======

* [What's in the Box? An Analysis of Undesirable Content in the Common Crawl Corpus](https://arxiv.org/abs/2105.02732) -- <ins>A. Luccioni</ins> & J. Vivano, *2021 ACL/IJCAI Joint Conference*.
* [From Artificial Intelligence Bias to Inequality in the Time of COVID-19](https://arxiv.org/abs/2011.08073) -- M Luengo-Oroz, J Bullock, KH Pham, CSN Lam, <ins>A. Luccioni</ins>, *IEEE Technology and Society Magazine 40 (1), 71-79,2021*.

2020
======
* [Analyzing Sustainability Reports Using Natural Language Processing](https://arxiv.org/abs/2011.08073) -- <ins>A. Luccioni</ins>, E. Baylor, N. Duchene, *Tackling Climate Change workshop, NeurIPS 2020*.
* [Geo-Spatiotemporal Features and Shape-Based Prior Knowledge for Fine-Grained Imbalanced Data Classification](C. Kantor, C., M. Skreta, B. Rauby, L. Boussioux, E. Jehanno,  <ins>A. Luccioni</ins>, D. Rolnick, H. Talbot, *2020 Harvard AI for Social Good Workshop} poster presentation*.
* [Artificial intelligence cooperation to support the global response to COVID-19](https://www.nature.com/articles/s42256-020-0184-3), M. Luengo-Oroz, K. Hoffman-Pham, J. Bullock, R. Kirkpatrick,  <ins>A. Luccioni</ins>, *Nature Machine Intelligence*.
* [Using Artificial Intelligence to Visualize the Impacts of Climate Change]( <ins>A. Luccioni</ins>, V. Schmidt and Y. Bengio, *Visualization Viewpoints IEEE Computer Graphics \& Applications Magazine*.
* [Mapping the landscape of artificial intelligence applications against COVID-19](https://www.jair.org/index.php/jair/article/view/12162), J.Bullock,  <ins>A. Luccioni</ins>, K. Hoffman-Pham, M. Luengo-Oroz, *Journal of Artificial Intelligence Research*,  Vol. 69.
* [Considerations, Good Practices, Risks and Pitfalls in Developing AI Solutions Against COVID-19](https://arxiv.org/abs/2008.09043) <ins>A. Luccioni</ins>, J. Bullock, K. Hoffmann-Pham, C. Sin Nga Lam, M. Luengo-Oroz, *AI for Social Good Harvard CRCS workshop.
* [Estimating the Carbon Emissions of Artificial Intelligence](https://technologyandsociety.org/estimating-carbon-emissions-of-artificial-intelligence/), <ins>A. Luccioni</ins> A. Lacoste, V. Schmidt, *IEEE Technology and Society Magazine*, 39(2), pp. 48-51.
* [Leveraging Digital Disruptions for a Climate-Safe and Equitable World] (https://technologyandsociety.org/leveraging-digital-disruptions-for-a-climate-safe-and-equitable-world-the-d\%CB\%862s-agenda/) A. Luers, J. Garard, A. Clair, O. Gaffney, T. Hassenboehler, L. Langlois, M. Mougeot, <ins>A. Luccioni</ins>.  *IEEE Society and Technology Magazine* 39(2), pp. 18-31.
*[On the Morality of Artificial Intelligence](https://technologyandsociety.org/on-the-morality-of-artificial-intelligence), <ins>A. Luccioni</ins>, Y. Bengio, *IEEE Technology and Society Magazine*.
* [Establishing an Evaluation Metric to Quantify Climate Change Image Realism](https://iopscience.iop.org/article/10.1088/2632-2153/ab7657), S. Zhao, <ins>A. Luccioni</ins>, G. Cosne, M. Bernstein, Y. Bengio, *Machine Learning: Science and Technology.

2019
======
* [Quantifying the Carbon Emissions of Machine Learning](https://arxiv.org/abs/1910.09700), A. Lacoste*, <ins>A. Luccioni*</ins>, V. Schmidt*, T. Dandres, *Tackling Climate Change with Machine Learning, NeurIPS 2019 Workshop*.
* [Using Natural Language Processing to Analyze Financial Climate Disclosures](https://www.climatechange.ai/papers/icml2019/34/paper.pdf), <ins>A. Luccioni</ins> & H. Palacios, *Tackling Climate Change with Machine Learning, NeurIPS 2019 Workshop.
* [Tackling Climate Change with Machine Learning](https://arxiv.org/abs/1906.05433)   D. Rolnick, P. Donti, L. Kaack, A. Lacoste, K. Sankaran, <ins>A. Luccioni</ins> et al., *Pending Press*
* [Visualizing the consequences of climate change using cycle-consistent adversarial networks](https://arxiv.org/pdf/1905.03709.pdf) V. Schmidt*, <ins>A. Luccioni</ins>* , K. Sankaran, J. Chayes, Y. Bengio, *AI for Social Good Workshop}, ICLR 2019*.

2018
======
* [STI-DICO: an Intelligent Tutoring System to Foster Dictionary Skills for French Teachers-in-Training](https://archipel.uqam.ca/11201/1/D3388.pdf), <ins>A. Luccioni</ins>, Doctoral Dissertation, *Université du Québec à Montréal*.
* [STI-DICO: A Web-Based ITS for Fostering Dictionary Skills and Knowledge](https://www.researchgate.net/publication/307854625_STI-DICO_A_Web-Based_ITS_for_Fostering_Dictionary_Skills_and_Knowledge) <ins>A. Luccioni</ins>, J.Bourdeau, J.Massardi, R. Nkambou, *European Conference on Technology Enhanced Learning} (pp. 416-421)*.
* [STI-DICO: a web-based system for intelligent tutoring of dictionary skills] (https://link.springer.com/chapter/10.1007/978-3-319-45153-4_36), <ins>A. Luccioni</ins>, R. Nkambou, J. Massardi, J. Bourdeau, C. Coulombe, *Proceedings of the 25th International Conference Companion on World Wide Web} (pp. 923-928)*.


* [Overspecified references: An experiment on lexical acquisition in a virtual environment](https://daneshyari.com/article/preview/350307.pdf), <ins>A. Luccioni</ins>, L. Benotti, F.Landragin, *Computers in Human Behavior*, 49, 94-101.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
