---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a postdoctoral fellow at the [HKUCDS BioAI lab](http://www.bio8.cs.hku.hk/), [School of Computing and Data Science, The University of Hong Kong](https://www.cs.hku.hk/). I work on bioinformatics algorithm development, deep learning, and genomics research, with extensive experience in Python, C, and C++. Feel free to visit my [GitHub page](https://github.com/zhengzhenxian) for details.

I received my Ph.D. in Computer Science from The University of Hong Kong in September 2023, supervised by Prof. [Ruibang Luo](http://www.bio8.cs.hku.hk/). Prior to that, I received my M.Eng. and B.Eng. in Software Engineering from the [School of Computer Science and Engineering, Sun Yat-sen University](https://cse.sysu.edu.cn/).

My research interests include long-read variant calling, somatic variant detection, RNA variant calling, and third-generation sequencing data analysis. I develop the Clair series variant callers ([Clair3](https://github.com/HKU-BAL/Clair3), [ClairS](https://github.com/HKU-BAL/ClairS), [ClairS-TO](https://github.com/HKU-BAL/ClairS-TO), [Clair3-RNA](https://github.com/HKU-BAL/Clair3-RNA), etc.), several of which are officially supported by Oxford Nanopore Technologies. I have published 15+ papers in peer-reviewed journals and conferences, including Nature Computational Science, Nature Communications, Briefings in Bioinformatics, and BMC Bioinformatics.


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 [Gungnir](https://www.nature.com/articles/s41467-026-71485-x) DNA storage codec was published in Nature Communications.
- *2025.12*: &nbsp;🎉🎉 [Clair3-RNA](https://www.nature.com/articles/s41467-025-67237-y) was published in Nature Communications.
- *2025.10*: &nbsp;🎉🎉 [ClairS-TO](https://www.nature.com/articles/s41467-025-64547-z) was published in Nature Communications.
- *2025.01*: &nbsp;🎉🎉 [Repun](https://academic.oup.com/bib/article/26/1/bbae613/7928434) was published in Briefings in Bioinformatics.
- *2023.09*: &nbsp;🎉🎉 I graduated from the Department of Computer Science, the University of Hong Kong.
- *2023.08*: &nbsp;🎉🎉 A preprint describing ClairS's algorithms and results is at [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.08.17.553778v1).
- *2023.05*: &nbsp;🎉🎉 ClairS was supported as an official somatic small variant caller tool by Oxford Nanopore Technologies, link [here](https://labs.epi2me.io/colo-2023.05/).
- *2023.04*: &nbsp;🎉🎉 I gave a talk in Recomb-Seq on our new somatic variant caller [ClairS](https://github.com/HKU-BAL/ClairS).
- *2023.02*: &nbsp;🎉🎉 Our paper [Clair3](https://www.nature.com/articles/s43588-022-00387-x) was accepted by Nature Computational Science.
- *2021.10*: &nbsp;🎉🎉 Our first bioinformatics software [Clair3](https://github.com/HKU-BAL/Clair3) was supported as official variant caller tool by Oxford Nanopore Technologies, link [here](https://labs.epi2me.io/gm24385_q20_2021.10/).

# 📝 Publications 

First or co-first authored (`*`), Corresponding (`^`).

## Selected Publications
1. **Z. Zheng***, S. Li*, J. Su*, …, R. Luo^. [Symphonizing pileup and full-alignment for deep learning-based long-read variant calling](https://www.nature.com/articles/s43588-022-00387-x). *Nature Computational Science*, 2022, 2(12): 797-803. ([Code](https://github.com/HKU-BAL/Clair3))
2. **Z. Zheng***, J. Su*, L. Chen*, …, R. Luo^. [ClairS: a deep-learning method for long-read somatic small variant calling](https://www.biorxiv.org/content/10.1101/2023.08.17.553778v1). *bioRxiv*, 2023. ([Code](https://github.com/HKU-BAL/ClairS))
3. **Z. Zheng***, X. Yu*, …, R. Luo^. [Clair3-RNA: A deep learning-based small variant caller for long-read RNA sequencing data](https://www.nature.com/articles/s41467-025-67237-y). *Nature Communications*, 2025, 16: 11553. ([Code](https://github.com/HKU-BAL/Clair3-RNA))
4. L. Chen*, **Z. Zheng***^, …, T. Lam, R. Luo^. [ClairS-TO: a deep-learning method for long-read tumor-only somatic small variant calling](https://www.nature.com/articles/s41467-025-64547-z). *Nature Communications*, 2025, 16: 9630. ([Code](https://github.com/HKU-BAL/ClairS-TO))
5. **Z. Zheng**^, Y. Ren, …, R. Luo^. [Repun: An accurate small variant representation unification method for multiple sequencing platforms](https://academic.oup.com/bib/article/26/1/bbae613/7928434). *Briefings in Bioinformatics*, 2025, 26(1): bbae613. ([Code](https://github.com/zhengzhenxian/Repun))
6. J. Zhang, L. Chen, …, **Z. Zheng**^, R. Luo^. [Gungnir codec enabling high error-tolerance and low-redundancy DNA storage through substantial computing power](https://www.nature.com/articles/s41467-026-71485-x). *Nature Communications*, 2026. ([Code](https://github.com/HKU-BAL/Gungnir))
7. H. Yu*, **Z. Zheng***, …, R. Luo^. [Boosting variant-calling performance with multi-platform sequencing data using Clair3-MP](https://doi.org/10.1186/s12859-023-05428-5). *BMC Bioinformatics*, 2023, 24(1): 308. ([Code](https://github.com/HKU-BAL/Clair3-MP))
8. L. Chen*, J. Su*, **Z. Zheng***, …, R. Luo^. Large-scale Dataset and Effective Model for Variant-Disease Associations Extraction. *Proceedings of the 14th ACM International Conference on Bioinformatics, Computational Biology, and Health Informatics*, 2023: 1-6.
9. J. Su*, **Z. Zheng***, …, R. Luo^. [Clair3-trio: high-performance Nanopore long-read variant calling in family trios with trio-to-trio deep neural networks](https://doi.org/10.1093/bib/bbac301). *Briefings in Bioinformatics*, 2022, 23(5): bbac301. ([Code](https://github.com/HKU-BAL/Clair3-trio))
10. **Z. Zheng**, Y. Yi, …, J. Zhang. Adaptive updating siamese network with likelihood estimation for surveillance video object tracking. *IEEE International Conference on Multimedia & Expo*, 2019.
11. **Z. Zheng***, M. He*, X. Yu*, …, R. Luo^. [Accelerated long-read variant calling with Clair3 for whole-genome sequencing](https://doi.org/10.1093/bioinformatics/btag181). *Bioinformatics*, 2026, 42(5): btag181. ([Code](https://github.com/HKU-BAL/Clair3))
12. J. Su*, S. Li*, **Z. Zheng***, …, R. Luo^. [ClusterV-Web: a user-friendly tool for profiling HIV quasispecies and generating drug resistance reports from nanopore long-read data](https://doi.org/10.1093/bioadv/vbae006). *Bioinformatics Advances*, 2024, 4(1): vbae006. ([Code](https://github.com/HKU-BAL/ClusterV-Web))

Please check my Google Scholar for all publications [here](https://scholar.google.com/citations?user=NBH39WAAAAAJ&hl=zh-CN&oi=sra).

# 🎖 Honors and Awards
- *2019 - 2023* University Postgraduate Fellowships
- *2019 - 2023* Postgraduate Scholarships
- *2018* Kaggle Competition silver medal and bronze medal
- *2018* First-class Graduate Academic Scholarship
- *2014 - 2016* First-class Undergraduate Academic Scholarship

# 📖 Educations
- *2019.09 - 2023.09*, Ph.D., Department of Computer Science, The University of Hong Kong, Hong Kong.
- *2017.09 - 2019.06*, M.Eng., School of Computer Science and Engineering, Sun Yat-sen University, Guangzhou.
- *2013.09 - 2017.06*, B.Eng., School of Computer Science and Engineering, Sun Yat-sen University, Guangzhou.

# 💬 Presentations
- *2024.10*, ClairS: a deep-learning method for long-read somatic small variant calling. APBJC 2024, Okinawa, Japan.
- *2023.04*, Accurate haplotype-aware long-read somatic variant calling using deep learning-based synthetic data learning. RECOMB-SEQ 2023, Istanbul, Turkey.
- *2020.05*, Claire: Clair-extended to support full alignment as input to a deep neural network for more accurate germline variant calling in low complexity genome regions. RECOMB-SEQ 2020, Padua, Italy.

# 💻 Internships
- *2018.05 - 2018.09*, Summer intern, Intelligent Recommendation Center, Tencent.
- *2017.06 - 2017.09*, Research intern, Medical Image Group, Sun Yat-sen University Cancer Center.
