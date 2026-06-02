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

I am currently a postdoctoral fellow at the [HKUCDS BioAI lab](http://www.bio8.cs.hku.hk/), [School of Computing and Data Science, The University of Hong Kong](https://www.cds.hku.hk/). I work on bioinformatics algorithm development, deep learning, and genomics research, with extensive experience in Python, C, and C++. Feel free to visit my [GitHub page](https://github.com/zhengzhenxian) for details.

I received my Ph.D. in Computer Science from The University of Hong Kong in September 2023, supervised by Prof. [Ruibang Luo](http://www.bio8.cs.hku.hk/). Prior to that, I received my M.Eng. and B.Eng. in Software Engineering from the [School of Computer Science and Engineering, Sun Yat-sen University](https://cse.sysu.edu.cn/).

My research interests include long-read variant calling, somatic variant detection, RNA variant calling, and third-generation sequencing data analysis. I develop the Clair series variant callers ([Clair3](https://github.com/HKU-BAL/Clair3), [ClairS](https://github.com/HKU-BAL/ClairS), [ClairS-TO](https://github.com/HKU-BAL/ClairS-TO), [Clair3-RNA](https://github.com/HKU-BAL/Clair3-RNA), etc.), several of which are officially supported by Oxford Nanopore Technologies. I have published 15+ papers in peer-reviewed journals and conferences, including Nature Computational Science, Nature Communications, Bioinformatics, Briefings in Bioinformatics, and BMC Bioinformatics.


# 🔥 News
- <em>2026.04</em>: &nbsp;🎉🎉 [Gungnir](https://www.nature.com/articles/s41467-026-71485-x) DNA storage codec was published in Nature Communications.
- <em>2025.12</em>: &nbsp;🎉🎉 [Clair3-RNA](https://www.nature.com/articles/s41467-025-67237-y) was published in Nature Communications.
- <em>2025.10</em>: &nbsp;🎉🎉 [ClairS-TO](https://www.nature.com/articles/s41467-025-64547-z) was published in Nature Communications.
- <em>2025.01</em>: &nbsp;🎉🎉 [Repun](https://academic.oup.com/bib/article/26/1/bbae613/7928434) was published in Briefings in Bioinformatics.
- <em>2023.09</em>: &nbsp;🎉🎉 I graduated from the Department of Computer Science, the University of Hong Kong.
- <em>2023.08</em>: &nbsp;🎉🎉 A preprint describing ClairS's algorithms and results is at [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.08.17.553778v1).
- <em>2023.05</em>: &nbsp;🎉🎉 ClairS was supported as an official somatic small variant caller tool by Oxford Nanopore Technologies, link [here](https://labs.epi2me.io/colo-2023.05/).
- <em>2023.04</em>: &nbsp;🎉🎉 I gave a talk in Recomb-Seq on our new somatic variant caller [ClairS](https://github.com/HKU-BAL/ClairS).
- <em>2023.02</em>: &nbsp;🎉🎉 Our paper [Clair3](https://www.nature.com/articles/s43588-022-00387-x) was accepted by Nature Computational Science.
- <em>2021.10</em>: &nbsp;🎉🎉 Our first bioinformatics software [Clair3](https://github.com/HKU-BAL/Clair3) was supported as official variant caller tool by Oxford Nanopore Technologies, link [here](https://labs.epi2me.io/gm24385_q20_2021.10/).

# 📝 Publications 

## Selected Publications (<sup>&#42;</sup>equal contribution, <sup>&#35;</sup>corresponding)

1. **Z. Zheng**<sup>&#42;</sup>, S. Li<sup>&#42;</sup>, J. Su<sup>&#42;</sup>, A. W. S. Leung, T. W. Lam, R. Luo<sup>&#35;</sup>. Symphonizing pileup and full-alignment for deep learning-based long-read variant calling. **Nature Computational Science**, 2022, 2(12): 797-803. [Full text](https://www.nature.com/articles/s43588-022-00387-x) · [Code](https://github.com/HKU-BAL/Clair3)
2. **Z. Zheng**<sup>&#42;</sup>, X. Yu<sup>&#42;</sup>, L. Chen, Y. L. Lee, C. Xin, A. O. K. Wong, M. Jain, R. K. Kesharwani, F. J. Sedlazeck<sup>&#35;</sup>, R. Luo<sup>&#35;</sup>. Clair3-RNA: A deep learning-based small variant caller for long-read RNA sequencing data. **Nature Communications**, 2025, 16(1): 11553. [Full text](https://www.nature.com/articles/s41467-025-67237-y) · [Code](https://github.com/HKU-BAL/Clair3-RNA)
3. **Z. Zheng**<sup>&#42;</sup>, L. Chen<sup>&#42;</sup>, J. Su<sup>&#42;</sup>, Y. L. Lee, T. W. Lam, R. Luo<sup>&#35;</sup>. ClairS: a deep-learning method for long-read somatic small variant calling. **bioRxiv**, 2023. [Full text](https://www.biorxiv.org/content/10.1101/2023.08.17.553778v1) · [Code](https://github.com/HKU-BAL/ClairS)
4. **Z. Zheng**, M. He, X. Yu, J. Li, L. Chen, A. O. K. Wong, J. Zhang, Y. Zhou, R. Luo<sup>&#35;</sup>. Accelerated long-read variant calling with Clair3 for whole-genome sequencing. **Bioinformatics**, 2026, 42(5): btag181. [Full text](https://doi.org/10.1093/bioinformatics/btag181) · [Code](https://github.com/HKU-BAL/Clair3)
5. **Z. Zheng**<sup>&#42;&#35;</sup>, Y. Ren<sup>&#42;</sup>, L. Chen, A. O. K. Wong, S. Li, X. Yu, T. W. Lam, R. Luo<sup>&#35;</sup>. Repun: An accurate small variant representation unification method for multiple sequencing platforms. **Briefings in Bioinformatics**, 2025, 26(1): bbae613. [Full text](https://academic.oup.com/bib/article/26/1/bbae613/7928434) · [Code](https://github.com/zhengzhenxian/Repun)
6. **Z. Zheng**, M. He, X. Yu, L. Chen, A. O. K. Wong, J. Zhang, Y. Zhou, R. Luo<sup>&#35;</sup>. T2T-CHM13 reveals missing truth variants and improves deep-learning-based variant calling in long-read sequencing data. Accepted by **Quantitative Biology**, 2026.
7. L. Chen<sup>&#42;</sup>, **Z. Zheng**<sup>&#42;&#35;</sup>, J. Su, X. Yu, A. O. K. Wong, J. Zhang, Y. L. Lee, R. Luo<sup>&#35;</sup>. ClairS-TO: a deep-learning method for long-read tumor-only somatic small variant calling. **Nature Communications**, 2025, 16(1): 9630. [Full text](https://www.nature.com/articles/s41467-025-64547-z) · [Code](https://github.com/HKU-BAL/ClairS-TO)
8. J. Zhang<sup>&#42;</sup>, L. Chen<sup>&#42;</sup>, J. Sun<sup>&#42;</sup>, S. Li, Y. Zhou, Z. Wu, C. Li, **Z. Zheng**<sup>&#35;</sup>, R. Luo<sup>&#35;</sup>. Gungnir codec enabling high error-tolerance and low-redundancy DNA storage through substantial computing power. **Nature Communications**, 2026. [Full text](https://www.nature.com/articles/s41467-026-71485-x) · [Code](https://github.com/HKU-BAL/Gungnir)
9. J. Su<sup>&#42;</sup>, **Z. Zheng**<sup>&#42;</sup>, S. S. Ahmed, T. W. Lam, R. Luo<sup>&#35;</sup>. Clair3-trio: high-performance Nanopore long-read variant calling in family trios with trio-to-trio deep neural networks. **Briefings in Bioinformatics**, 2022, 23(5): bbac301. [Full text](https://doi.org/10.1093/bib/bbac301) · [Code](https://github.com/HKU-BAL/Clair3-trio)
10. L. Chen<sup>&#42;</sup>, **Z. Zheng**<sup>&#42;&#35;</sup>, M. He, A. O. K. Wong, X. Yu, J. Li, J. Zhang, Y. Zhou, R. Luo<sup>&#35;</sup>. Clair-Mosaic: A deep-learning method for long-read mosaic small variant calling. **bioRxiv**, 2025. [Full text](https://www.biorxiv.org/content/10.1101/2025.10.31.685831v1) · [Code](https://github.com/HKU-BAL/Clair-Mosaic)
11. H. Yu<sup>&#42;</sup>, **Z. Zheng**<sup>&#42;</sup>, J. Su<sup>&#35;</sup>, T. W. Lam<sup>&#35;</sup>, R. Luo<sup>&#35;</sup>. Boosting variant-calling performance with multi-platform sequencing data using Clair3-MP. **BMC Bioinformatics**, 2023, 24: 308. [Full text](https://link.springer.com/article/10.1186/s12859-023-05434-6) · [Code](https://github.com/HKU-BAL/Clair3-MP)
12. L. Chen<sup>&#42;</sup>, J. Su<sup>&#42;</sup>, **Z. Zheng**<sup>&#42;</sup>, T. W. Lam, R. Luo<sup>&#35;</sup>. Large-scale Dataset and Effective Model for Variant-Disease Associations Extraction. **Proceedings of the 14th ACM International Conference on Bioinformatics, Computational Biology, and Health Informatics**, 2023, 1-6. [Full text](https://doi.org/10.1145/3584371.3612995)

Please check my Google Scholar for all publications [here](https://scholar.google.com/citations?user=NBH39WAAAAAJ&hl=zh-CN&oi=sra).

# 🎖 Honors and Awards

<ul class="cv-list cv-list-honors">
<li><span class="cv-date"><em>2019 - 2023</em></span> University Postgraduate Fellowships</li>
<li><span class="cv-date"><em>2019 - 2023</em></span> Postgraduate Scholarships</li>
<li><span class="cv-date"><em>2018</em></span> Kaggle Competition silver medal and bronze medal</li>
<li><span class="cv-date"><em>2018</em></span> First-class Graduate Academic Scholarship</li>
<li><span class="cv-date"><em>2014 - 2016</em></span> First-class Undergraduate Academic Scholarship</li>
</ul>

# 📖 Educations

<ul class="cv-list cv-list-edu">
<li><span class="cv-date"><em>2019.09 - 2023.09</em></span>, Ph.D., Department of Computer Science, The University of Hong Kong, Hong Kong.</li>
<li><span class="cv-date"><em>2017.09 - 2019.06</em></span>, M.Eng., School of Computer Science and Engineering, Sun Yat-sen University, Guangzhou.</li>
<li><span class="cv-date"><em>2013.09 - 2017.06</em></span>, B.Eng., School of Computer Science and Engineering, Sun Yat-sen University, Guangzhou.</li>
</ul>

# 💬 Presentations
- <em>2024.10</em>, ClairS: a deep-learning method for long-read somatic small variant calling. APBJC 2024, Okinawa, Japan.
- <em>2023.04</em>, Accurate haplotype-aware long-read somatic variant calling using deep learning-based synthetic data learning. RECOMB-SEQ 2023, Istanbul, Turkey.
- <em>2020.05</em>, Claire: Clair-extended to support full alignment as input to a deep neural network for more accurate germline variant calling in low complexity genome regions. RECOMB-SEQ 2020, Padua, Italy.

# 💻 Internships
- <em>2018.05 - 2018.09</em>, Summer intern, Intelligent Recommendation Center, Tencent.
- <em>2017.06 - 2017.09</em>, Research intern, Medical Image Group, Sun Yat-sen University Cancer Center.
