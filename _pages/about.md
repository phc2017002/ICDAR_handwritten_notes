


## Contents

- [Introduction](#iclr-2024-blogposts-track)
- [Challenge Description](#spotlight)
- [Dataset details](#accepted-posts)
- [Key Dates](#key-dates)
- [Submissions](#submissions)
- [Organizers](#organizers)

# Introduction

The field of Document Analysis and Recognition (DAR) has made remarkable strides in recent years, driven by the integration of Natural Language Processing (NLP) and Computer Vision (CV) techniques. These advancements have enabled holistic Document Understanding (DU) for Visually Rich Documents (VRDs), which require the seamless fusion of textual, visual, and layout information. Despite these achievements, the domain of handwritten document understanding remains a persistent challenge, especially for complex layouts and diverse content types.

To increase research in this field, we present this ICDAR Handwritten Notes Understanding competition, in which the model needs to answer the framed questions that span over 2000 handwritten note samples—composed of multipage handwritten exam notes from competitive exams in India, such as IIT-JEE, GATE, and various science disciplines. Spanning subjects like computer science, mathematics, physics, chemistry, and engineering. 

This competition will also present new performance measuring benchmarks like NDCG@5, Recall@K, and MRR alongside standard ANLS and Accuracy to assess transcription precision, ranking, and relevance. By bridging layout analysis, HTR, and question answering, this challenge aims to advance state-of-the-art methodologies in document AI, fostering innovation in handling complex, context-sensitive retrieval tasks. Furthermore, it aligns with the goals of ICDAR by promoting research that tackles real-world complexities, such as low-resource settings, multi-topic domains, and multipage reasoning.

Overall, this competition will catalyze practical applications in the handwritten domain, such as automated evaluation of handwritten exam responses and bridging academic and industrial needs. We aim to set a new standard for understanding handwritten documents and drive impactful advancements in the DAR landscape by fostering community engagement through robust benchmarks and reproducible platforms.

## Competition Details

In our competition the dataset will be given the question answers. The question answers span over 2000 Handwritten notes from different scientific fields like mathematics, physics, chemistry, computer science and engineering. The task is divide into two parts. One is Evidence based grounding and another one is open domain VQA on a collection of Handwritten Notes.

**Evidence-Based Grounding in Handwritten VQA**: This task involves developing a system to answer questions based on 3–4 pages of handwritten documents. It requires interpreting handwriting, understanding context, and providing evidence-based answers, ranging from specific extractions to contextually generated responses.

**Open-Domain VQA on a Collection of Handwritten Notes**: In this task, the focus shifts to an open-domain setting within the science domain, where the system must handle a vast collection of handwritten notes on various scientific subjects. The process involves retrieving relevant handwritten pages and using a generative model to interpret the content and produce accurate, query-based answers.




## Competition Updates

**Registration Opens**: 5th January, 2025

**Registration Close**: 31st March, 2025

**Test Data Release**: 1st April, 2025

**Results Submission Deadline**: 15th April, 2025

**Winner Announcement**: 30th April, 2025



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


