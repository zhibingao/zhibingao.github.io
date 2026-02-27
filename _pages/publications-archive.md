---
title: "PUBLICATIONS"
layout: single
permalink: /Publications/
author_profile: true
---
{% assign publications = site.data.publications | sort: 'year' | reverse %}
{% for pub in publications %}
<div style="margin-bottom: 2em;">
  <p>
    <strong>{{ pub.title }}</strong><br>
    {{ pub.authors }}<br>
    <em>{{ pub.journal }}</em>, {{ pub.volume }}, {{ pub.pages }} ({{ pub.year }})
  </p>
  <p>
    {% if pub.url %}
      <a href="{{ pub.url }}" target="_blank" class="btn btn--primary btn--small">Publisher</a>
    {% endif %}
    {% if pub.pdf %}
      <a href="{{ pub.pdf | relative_url }}" class="btn btn--success btn--small">📥 PDF</a>
    {% endif %}
  </p>
</div>
{% endfor %}

-20. Hailing Guo#, Zhaofu Zhang#*, Yuzheng Guo, **Zhibin Gao**, Ruisheng Zheng, and Honglei Wu*, Impact of the interface vacancy on Schottky barrier height for Au/AlN polar interfaces, *Applied Surface Science*, 505, 144650 (2020). [pdf file] [Publisher's link to the manuscript]

-19. Mei Xiong, **Zhibin Gao**, Kun Luo, FeiFei Ling, YuFei Gao, Chong Chen, Dongli Yu, Zhisheng Zhao, and Shizhong Wei*, Three metallic BN polymorphs: 1D multi-threaded conduction in a 3D network, *Phys. Chem. Chem. Phys.*, 22, 489-496 (2020). [pdf file] [Publisher's link to the manuscript]

-18. **Zhibin Gao**\*, Mengyang Li, and Jian-Sheng Wang, Insight into Two-Dimensional Borophene: Five-Center Bond and Phonon-Mediated Superconductivity, *ACS Appl. Mater. Interfaces*, 11, 47279-47288 (2019). [pdf file] [Supporting Information] [Supporting moive] [Publisher's link to the manuscript]

-17. **Zhibin Gao**\*, Zhaofu Zhang, Gang Liu, and Jian-Sheng Wang, Ultra-low lattice thermal conductivity of monolayer penta-silicene and penta-germanene, *Phys. Chem. Chem. Phys.*, 21, 26033-26040 (2019). [pdf file] [Publisher's link to the manuscript]

-16. Gang Liu#, **Zhibin Gao**#, and Jie Ren*, Anisotropic thermal expansion and thermodynamic properties of monolayer β-Te, *Physical Review B*, 99, 195436 (2019). [pdf file] [Publisher's link to the manuscript]

-15. Jia Song, **Zhibin Gao**, Liang Zhang*, Wenheng Wu, Beibei He, and Lin Lu, Prediction on elastic properties of Nb-doped Ni systems, *Molecular Simulation*, 45, 935–941 (2019). [pdf file] [Publisher's link to the manuscript]

-14. **Zhibin Gao**, Zhixian Zhou, and David Tománek*, Degenerately Doped Transition Metal Dichalcogenides as Ohmic Homojunction Contacts to Transition Metal Dichalcogenide Semiconductors, *ACS Nano*, 13, 5103-5111 (2019). [pdf file] [Supporting Information] [Publisher's link to the manuscript]

-13. Gang Liu*, **Zhibin Gao**\*, and Jian Zhou, Strain effects on the mechanical properties of Group-V monolayers with buckled honeycomb structures, *Physica E: Low-dimensional Systems and Nanostructures*, 112, 59-65 (2019). [pdf file] [Publisher's link to the manuscript]

-12. Yi Wang#, **Zhibin Gao**#, and Jun Zhou*, Ultralow lattice thermal conductivity and electronic properties of monolayer 1T phase semimetal SiTe2 and SnTe2, *Physica E: Low-dimensional Systems and Nanostructures*, 108, 53-59 (2019). [pdf file] [Publisher's link to the manuscript]

-11. Liang Zhang, Jia Song, Wenheng Wu, **Zhibin Gao**, Beibei He, Xiaoqing Ni, Qianlei Long, Lin Lu, and Guoliang Zhu, Effect of processing parameters on thermal behavior and related density in GH3536 alloy manufactured by selective laser melting, *Journal of Materials research*, 34, 1405-1414 (2019). [pdf file] [Publisher's link to the manuscript]

-10. **Zhibin Gao**, Dan Liu, and David Tománek*, Two-Dimensional Mechanical Metamaterials with Unusual Poisson Ratio Behavior, *Physical Review Applied*, 10, 064039 (2018). [pdf file] [Publisher's link to the manuscript]

-9. Yanran Liu, **Zhibin Gao**, Ming Chen, Yang Tan, and Feng Chen, Thin Films: Enhanced Raman Scattering of CuPc Films on Imperfect WSe2 Monolayer Correlated to Exciton and Charge‐Transfer Resonances, *Adv. Funct. Mater.*, 28, 1870369 (2018). [pdf file] [Publisher's link to the manuscript]

-8. Yanran Liu, **Zhibin Gao**, Ming Chen, Yang Tan, and Feng Chen, Enhanced Raman Scattering of CuPc Films on Imperfect WSe2 Monolayer Correlated to Exciton and Charge‐Transfer Resonances, *Adv. Funct. Mater.*, 28, 1805710 (2018). [pdf file] [Publisher's link to the manuscript]

-7. **Zhibin Gao**, Gang Liu, and Jie Ren, High Thermoelectric Performance in Two-Dimensional Tellurium: An Ab Initio Study, *ACS Appl. Mater. Interfaces*, 10, 40702-40709 (2018). [pdf file] [Supporting Information] [Publisher's link to the manuscript]

-6. Yanran Liu, **Zhibin Gao**, Yang Tan, and Feng Chen, Enhancement of Out-of-Plane Charge Transport in a Vertically Stacked Two-Dimensional Heterostructure Using Point Defects, *ACS Nano*, 12, 10529–10536 (2018). [pdf file] [Publisher's link to the manuscript]

-5. **Zhibin Gao**, Fang Tao, and Jie Ren*, Unusually low thermal conductivity of atomically thin 2D tellurium, *Nanoscale*, 10, 12997-13003 (2018). [pdf file] [Supporting Information] [Publisher's link to the manuscript]

-4. **Zhibin Gao**, Xiao Dong, Nianbei Li, and Jie Ren, Novel Two-Dimensional Silicon Dioxide with in-Plane Negative Poisson’s Ratio, *Nano Lett.*, 17, 772-777 (2017). [pdf file] [Supporting Information] [Publisher's link to the manuscript]

-3. Yang Tan, Linan Ma, **Zhibin Gao**, Ming Chen, Feng Chen, Two-Dimensional Heterostructure as a Platform for Surface Raman Scattering, *Nano Lett.*, 17, 2621-2626 (2017). [pdf file] [Publisher's link to the manuscript]

-2. **Zhibin Gao**, Nianbei Li, and Baowen Li, Stretch diffusion and heat conduction in one-dimensional nonlinear lattices, *Physical Review E*, 93, 032130 (2016). [pdf file] [Publisher's link to the manuscript]

-1. **Zhibin Gao**, Nianbei Li, and Baowen Li, Heat conduction and energy diffusion in momentum-conserving one-dimensional full-lattice ding-a-ling model, *Physical Review E*, 93, 022102 (2016). [pdf file] [Publisher's link to the manuscript]
