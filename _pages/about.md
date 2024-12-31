


## Contents

- [Introduction](#iclr-2024-blogposts-track)
- [Challenge Description](#spotlight)
- [Dataset details](#accepted-posts)
- [Key Dates](#key-dates)
- [Submissions](#submissions)
- [Organizers](#organizers)

# Introduction

ield, we present this ICDAR Handwritten Notes Understanding competition, in which the model needs to answer the framed questions that span over 2000 handwritten note samples—composed of multipage handwritten exam notes from competitive exams in India, such as IIT-JEE, GATE, and various science disciplines. Spanning subjects like computer science, mathematics, physics, chemistry, and engineering. 

This competition will also present new performance measuring benchmarks like NDCG@5, Recall@K, and MRR alongside standard ANLS and Accuracy to assess transcription precision, ranking, and relevance. By bridging layout analysis, HTR, and question answering, this challenge aims to advance state-of-the-art methodologies in document AI, fostering innovation in handling complex, context-sensitive retrieval tasks. Furthermore, it aligns with the goals of ICDAR by promoting research that tackles real-world complexities, such as low-resource settings, multi-topic domains, and multipage reasoning.

Overall, this competition will catalyze practical applications in the handwritten domain, such as automated evaluation of handwritten exam responses and bridging academic and industrial needs. We aim to set a new standard for understanding handwritten documents and drive impactful advancements in the DAR landscape by fostering community engagement through robust benchmarks and reproducible platforms.

## A Blog Post Conference Track

Last year, we ran the **second** iteration of the [Blogpost track](https://iclr-blogposts.github.io/2023/about) at ICLR 2023!

It was very successful, with accepted posts presented in person at the main conference.

Our goal is to create a formal call for blog posts at ICLR to incentivize and reward researchers to review past work and summarize the outcomes, develop new intuitions, or highlight some shortcomings. A very influential initiative of this kind happened after the Second World War in France. Because of the lack of up-to-date textbooks, a collective of mathematicians under the pseudonym Nicolas Bourbaki [[Halmos 1957]](#Halm), decided to start a series of textbooks about the foundations of mathematics [[Bourbaki, 1939]](#Bour). In the same vein, we aim to provide a new way to summarize scientific knowledge in the ML community.

Due to the large diversity of topics that can be discussed in a blog post, we decided to restrict the range of topics for this call for blog posts. We identified that the blog posts that would bring to most value to the community and the conference would be posts that distill and discuss *previously published papers*.

## Spotlight

**[The N Implementation Details of RLHF with PPO]({% post_url 2024-05-07-the-n-implementation-details-of-rlhf-with-ppo %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Shengyi Costa Huang, Tianlin Liu, Leandro von Werra_

**[How to compute Hessian-vector products?]({% post_url 2024-05-07-bench-hvp %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Mathieu Dagréou, Pierre Ablin, Samuel Vaiter, Thomas Moreau_

**[Bridging the Data Processing Inequality and Function-Space Variational Inference]({% post_url 2024-05-07-dpi-fsvi %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Andreas Kirsch_

## Accepted Posts

**[Understanding in-context learning in transformers]({% post_url 2024-05-07-understanding-icl %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Simone Rossi, Rui Yuan, Thomas Hannagan_

**[Behavioral Differences in Mode-Switching Exploration for Reinforcement Learning]({% post_url 2024-05-07-mode-switching %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Loren J Anderson_

**[Fairness in AI: two philosophies or just one?]({% post_url 2024-05-07-fairness-ai-two-phil-or-just-one %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _MaryBeth Defrance_

**[Towards Robust Foundation Models: Adversarial Contrastive Learning]({% post_url 2024-05-07-robust-foundation-model %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Jingfeng Zhang, Xilie Xu_

**[A New Alchemy&#58; Language Model Development as a Subfield?]({% post_url 2024-05-07-language-model-development-as-a-new-subfield %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Colin Raffel_

**[Understanding gradient inversion attacks from the prior knowledge perspective]({% post_url 2024-05-07-understanding-gradient-inversion-attacks-from-the-prior-knowledge-perspective %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Yanbo Wang, Jian Liang, Ran He_

**[Building Diffusion Model's theory from ground up]({% post_url 2024-05-07-diffusion-theory-from-scratch %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Ayan Das_

**[Masked Language Model with ALiBi and CLAP head]({% post_url 2024-05-07-alibi-mlm %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Jason Chuan-Chih Chou_

**[What exactly has TabPFN learned to do?]({% post_url 2024-05-07-what-exactly-has-tabpfn-learned-to-do %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Calvin McCarter_

**[Elaborating on the Value of Flow Matching for Density Estimation]({% post_url 2024-05-07-elaborating-on-the-value-of-flow-matching-for-density-estimation %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Maternus Herold, Faried Abu Zaid_

**[The Hidden Convex Optimization Landscape of Two-Layer ReLU Networks]({% post_url 2024-05-07-hidden-convex-relu %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Victor Mercklé, Franck Iutzeler, Ievgen Redko_

**[Deep Equilibrium Models For Algorithmic Reasoning]({% post_url 2024-05-07-deqalg-reasoning %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Sophie Xhonneux, Yu He, Andreea Deac, Jian Tang, Gauthier Gidel_

**[Fair Model-Based Reinforcement Learning Comparisons with Explicit and Consistent Update Frequency]({% post_url 2024-05-07-update-frequency-in-mbrl %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Albert Thomas, Abdelhakim Benechehab, Giuseppe Paolo, Balázs Kégl_

**[Exploring Meta-learned Curiosity Algorithms]({% post_url 2024-05-07-exploring-meta-learned-curiosity-algorithms %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Batsirayi Mupamhi Ziki_

**[Unraveling The Impact of Training Samples]({% post_url 2024-05-07-unraveling-the-impact-of-training-samples %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Daiwei Chen, Jane Zhang, Ramya Korlakai Vinayak_

**[RLHF without RL - Direct Preference Optimization]({% post_url 2024-05-07-rlhf-without-rl %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Michael Panchenko_

**[It's Time to Move On: Primacy Bias and Why It Helps to Forget]({% post_url 2024-05-07-primacy-bias-and-why-it-helps-to-forget %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Matthew Kielo, Vladimir Lukin_

**[Double Descent Demystified]({% post_url 2024-05-07-double-descent-demystified %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Rylan Schaeffer, Zachary Robertson, Akhilan Boopathy, Mikail Khona, Kateryna Pistunova, Jason W. Rocks, Ila R. Fiete, Andrey Gromov, Sanmi Koyejo_

**[On Bayesian Model Selection: The Marginal Likelihood, Cross-Validation, and Conditional Log Marginal Likelihood]({% post_url 2024-05-07-clml %})**
: &nbsp;&nbsp;&nbsp;&nbsp; _Andreas Kirsch_


## Key Dates

**Abstract deadline**: December 11th 00:00GMT, 2023 (submit to OpenReview - to be announced soon).

**Submission deadline**: December 17th 00:00GMT, 2023 (any modifications to your blog post, via a pull request on GitHub).

**Decision Notification**: ~~January 30th, 2024~~ UPDATED: February 15th, 2024

**Camera-ready merge**: March 15th, 2024

## A call for blog posts discussing work previously published at ICLR

#### Content 

Write a post on a subject that has been published at a top-tier venue (ICLR, ICML, NeurIPS, AAAI, UAI, CVPR, SIGGRAPH, ECCV, ICCV, etc.) relatively recently. 

#### Conflict of interest

The authors of the blog posts will have to declare their conflicts of interest (positive or negative) with the paper (and the paper's authors) they write about. Conflicts of interest include:
-   Recent collaborators (less than 3 years)
-   Current institution ​ Reviewers will be asked to judge if the submission is sufficiently critical and objective of the papers addressed in the blog post.  
-  **Blog Posts must not be used to highlight or advertise past publications of the **authors or their lab****.

We will only ask the authors to report if they have a conflict of interest. If so, reviewers will be asked to judge if the submission is sufficiently critical and objective of the papers addressed in the blog post. 


## Publication 

#### Blog post

The posts will be created and published under a unified template; see [the submission instructions]({{ '/submitting' | relative_url }}) and the [sample post]({% post_url 2024-05-07-distill-example %}) hosted on the blog of this website.

#### Poster
Additionally, accepted posts will have the option to present their work as a poster during the main poster session. For more information about the main poster session (time, poster format, etc.) please refer to the ICLR homepage.

## Submissions

Our goal is to avoid heavily engineered, professionally-made blog posts ---Such as the “100+ hours” mentioned as a standard by the [Distill guidelines](https://distill.pub/journal/)---to entice ideas and clear writing rather than dynamic visualizations or embedded javascript engines.
Please check our [submission instructions]({{ '/submitting' | relative_url }}) for more details.
We accept submissions in both Markdown and HTML. We believe this is a good trade-off between complexity and flexibility. 

**Submit** your blogpost on [Openreview](https://openreview.net/group?id=ICLR.cc/2024/BlogPosts&referrer=%5BHomepage%5D(%2F))

## Contact

For any technical issues with the blog post repository (for example, blog posts not displaying correctly or issues while following the [submission instructions](https://iclr-blogposts.github.io/2024/submitting/#creating-a-blog-post)), please open an [issue in our github repository](https://github.com/iclr-blogposts/2024/issues).

For other inquiries, reach us via email at: [blog.track.chairs@gmail.com](mailto:blog.track.chairs@gmail.com)

## Organizers

<div class="row row-cols-2 projects pt-3 pb-3">
  {% include people_horizontal.html name="Gauthier Gidel" affiliation="Mila, Université de Montréal" url="https://gauthiergidel.github.io/" img="assets/img/organizers/gg.jpg" %}
  {% include people_horizontal.html name="Charlie Gauthier" affiliation="Mila, Université de Montréal" url="https://velythyl.github.io/" img="assets/img/organizers/cg.jpg" %}
  {% include people_horizontal.html name="David Dobre" affiliation="Mila, Université de Montréal" url="" img="assets/img/organizers/dd.jpg" %}
  {% include people_horizontal.html name="Claire Vernade" affiliation="University of Tuebingen" url="https://www.cvernade.com/" img="assets/img/organizers/cv.jpg" %}
  {% include people_horizontal.html name="Fabian Pedregosa" affiliation="Google DeepMind" url="https://fa.bianp.net/pages/about.html" img="assets/img/organizers/fp.jpg" %}
  {% include people_horizontal.html name="Leo Schwinn" affiliation="Technical University of Munich" url="https://schwinnl.github.io//" img="assets/img/organizers/ls.jpg" %}
</div>

---

## References

<a name="Litt">Michael L Littman. Collusion rings threaten the integrity of computer science research. Communications of the ACM, 2021.</a>

<a name="Tran">David Tran, Alex Valtchanov, Keshav Ganapathy, Raymond Feng, Eric Slud, Micah Goldblum, and Tom Goldstein. An open review of OpenReview: A critical analysis of the machine learning conference review process. arXiv, 2020. </a>

<a name="Lin">Hsuan-Tien Lin, Maria-Florina Balcan, Raia Hadsell, and Marc’Aurelio Ranzato. What we learned from NeurIPS 2020 reviewing process. Medium https://medium.com/@NeurIPSConf/what-we-learned-from-neurips-2020-reviewing-process-e24549eea38f, 2020. </a>

<a name="Brow">Eryn Brown and Chris Woolston. Why science blogging still matters. Nature, 2018.</a>

<a name="Halm">Paul R Halmos. Nicolas Bourbaki. Scientific American, 1957.<a>

<a name="Bour">Nicolas Bourbaki. Elements of mathematics. Éditions Hermann, 1939.</a>
