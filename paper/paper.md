---
title: 'Evolving FAIR Image Analysis in Galaxy for Cross-domain and AI-ready Applications'
title_short: 'Evolving FAIR Image Analysis in Galaxy'
tags:
  - Imaging
  - Image analysis
  - Image processing
  - Interdisciplinary
  - Life sciences
  - Galaxy
authors:
  - name: Diana Chiang
    affiliation: 1
  - name: Pavankumar Videm
    affiliation: 1
  - name: David Lopez Tabernero
    affiliation: 1
  - name: Maarten Paul
    affiliation: 2
  - name: Alireza Heidari
    affiliation: 1
  - name: Martin Etzrodt
    affiliation: 3
  - name: Beatriz Serrano-Solano
    affiliation: 4
    orcid: 0000-0002-5862-6132
  - name: Leonid Kostrykin
    affiliation: 5
    orcid: 0000-0003-1323-3762
affiliations:
  - name: Department of Computer Science, University of Freiburg, Freiburg, Germany
    index: 1
  - name: Leiden Universiteit
    index: 2
  - name: ISCC Foundation
    index: 3
  - name: Euro-BioImaging ERIC Bio-Hub, European Molecular Biology Laboratory (EMBL), Heidelberg, Germany
    index: 4
  - name: Biomedical Computer Vision Group, Heidelberg University, BioQuant, Heidelberg, ELIXIR Germany
    index: 5
date: 7 November 2025
cito-bibliography: paper.bib
event: BH25EU
biohackathon_name: "BioHackathon Europe 2025"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Berlin, Germany, 2025"
group: Project 9
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/FAIR-imaging/bh2025-preprint
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Diana Chiang \emph{et al.}
---


# 1 | Introduction

The growing integration  of image-based technologies across life sciences, environmental research, and other domains has intensified the need for interoperable, reproducible, and FAIR-compliant image analysis infrastructures. The ELIXIR BioHackathon Europe 2025 provided a collaborative environment to advance these goals within the Galaxy ecosystem [@extends:galaxy2024].

Previous projects at the ELIXIR BioHackathon Europe focused on community development and establishing conventions [@citesAsRelated:Kostrykin2024] or implementing FAIR workflows and training materials [@citesAsRelated:Kostrykin2025] for image analysis using Galaxy. Building on the achievements of the previous years, Project 9 at the ELIXIR BioHackathon Europe 2025 was entitled _"Evolving FAIR Image Analysis in Galaxy for Cross-domain and AI-ready Applications"_ and aimed to strengthen Galaxy's capabilities for bioimage analysis while enhancing cross-domain interoperability and reproducibility. The project addressed three major challenges:

1. Improving semantic annotation for image analysis resources.
2. Introducing content-based reproducibility validation mechanisms.
3. Streamlining tools and training materials for accessible bioimage analysis.

To achieve these goals, the project involved participants with heterogeneous backgrounds from different institutions, including ELIXIR, Euro-BioImaging, and the ISCC Foundation, joining both on-site and online. The goals of the project were also closely aligned with the [OSCARS-FIESTA](https://oscars-project.eu/projects/fair-image-analysis-across-sciences) and [OSCARS-BIOCODES](https://oscars-project.eu/projects/bio-codes-enhancing-ai-readiness-bioimaging-data-content-based-identifiers) projects.

By integrating ontology development with standard-based validation tools, the project contributed to a FAIR-aligned, cross-domain image analysis framework within Galaxy.

# 2 | Implementation

Our work was structured into three coordinated work packages (WPs) as described below. WP1 focused on cross-domain discovery and interoperability (Section 2.1), WP2 on integrating content-based fingerprints to enhance reproducibility and AI-readiness (Section 2.2), and WP3 on streamlining bioimage analysis in general, by improving tools, training materials, and the usability thereof (Section 2.3).

## 2.1 | WP1: Cross-domain Support Improvements

WP1 focused on semantic interoperability through improvements to the EDAM Bioimaging ontology. The EDAM Bioimaging ontology extends the core EDAM ontology [@citesAsRelated:Ison2013] with terms specific to bioimage data and analysis. However, this ontology extension is still under development. In the future, it will enable fine-grained annotation of tools, workflows, and tutorials within our community for specific analysis tasks. The BioHackathon team proposed extensions to the EDAM Bioimaging ontology to better align with the image analysis tasks supported by Galaxy. Furthermore, we curated a specialized vocabulary that reflects both the latest EDAM Bioimaging version and our specific recommendations (Section 3.1), which was then used to annotate the image analysis tutorials on the Galaxy Training Network [@extends:Hiltemann2023]. This enhances the discoverability of the tutorials in the short term while ensuring seamless compatibility with evolving standards.

Through this work package, semantic annotation became a central mechanism to enable cross-domain discovery, interoperability, and alignment with evolving community standards.

# 2.2 | Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
