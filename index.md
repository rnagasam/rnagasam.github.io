---
title: Ramana's homepage
layout: default
picHeight: 150
---

# Ramana Nagasamudram

![Image]({{ site.url }}/assets/images/me-cropped.jpg){: height="{{ page.picHeight }}" }
![Image]({{ site.url }}/assets/images/me-looking.jpg){: height="{{ page.picHeight }}"}
![Image]({{ site.url }}/assets/images/me-camera.jpg){: height="{{ page.picHeight }}"}

I'm a Ph.D. candidate in the Computer Science department at [Stevens
Institute of
Technology](https://www.stevens.edu/school-engineering-science/departments/computer-science),
advised by [Dave Naumann](https://dnaumann.github.io) and
(unofficially) by [Anindya Banerjee](https://software.imdea.org/~ab/).
I'm part of the [Cypress](https://mgree.github.io/cypress) research group.

[Curriculum Vitae]({{ site.url }}/assets/docs/RamanaNagasamudramCV.pdf), [Google Scholar](https://scholar.google.com/citations?user=XBEIwuUAAAAJ&hl=en&oi=ao), [DBLP](https://dblp.org/pid/284/1130.html), [GitHub](https://github.com/rnagasam), [LinkedIn](https://linkedin.com/in/rnagasam0)

Contact: rnagasam [at] stevens [dot] edu

----

## Research

Computer programs evolve constantly.  It's challenging to obtain
strong guarantees that code revisions preserve behaviors, especially
in the absence of precise functional specifications.  My research
addresses this problem by building tools and techniques for
*verifying* relations, such as equivalence and refinement, between
programs.  The goal is to formally account for code updates,
bug-fixes, optimizations, etc. in the simplest possible manner.

I'm interested in program logics and tooling for verification.  I
primarily use the [Coq](https://coq.inria.fr/) proof assistant and the
[Why3](https://www.why3.org) deductive verification platform.  Even in
research projects where proofs are mostly done in pen-and-paper, I've
found these tools to be immensely valuable "debugging" aids.

----

## Publications

- *Alignment Complete Relational Hoare Logics for Some and All*.\\
  Ramana Nagasamudram, Anindya Banerjee, and David A. Naumann.\\
  In submission\\
  [arXiv](https://arxiv.org/abs/2307.10045)

- *Verifying a C implementation of Derecho's coordination mechanism using VST and Coq*.\\
  Ramana Nagasamudram, Lennart Beringer, Ken Birman, Mae Milano, and David A. Naumann.\\
  NASA Formal Methods (NFM), 2024.\\
  [Pre-print (PDF)]({{ site.url }}/assets/papers/NFM2024.pdf), [Talk slides (PPTX)]({{ site.url }}/assets/talks/NFM2024.pptx), [Software artifact (Zenodo)](https://zenodo.org/records/10819602)

- *The WhyRel Prototype for Modular Relational Verification of Pointer Programs*.\\
  Ramana Nagasamudram, Anindya Banerjee, and David A. Naumann.\\
  International Conference on Tools and Algorithms for the Construction and Analysis of Systems (TACAS), 2024.\\
  [Pre-print (PDF)]({{ site.url }}/assets/papers/TACAS2023.pdf), [Talk slides (PDF)]({{ site.url }}/assets/talks/TACAS2023.pdf), [Software artifact (Zenodo)](https://zenodo.org/records/7308342)

  Nominated for an [ETAPS best paper award](https://etaps.org/awards/best-paper/).\\
  Invited submission to the International Journal on Software Tools for Technology Transfer (STTT)

- *An Algebra of Alignment for Relational Verification*.\\
  Timos Antonopoulos, Eric Koskinen, Ton Chanh Le, Ramana Nagasamudram, David A. Naumann, and Minh Ngo.\\
  ACM Symposium on Principles of Programming Languages (POPL), 2023.\\
  [Pre-print (PDF)]({{ site.url }}/assets/papers/POPL2023.pdf), [Talk slides (PDF)]({{ site.url }}/assets/talks/POPL2023.pdf), [Talk video (YouTube)](https://www.youtube.com/watch?v=_H299Iy4Rlc), [Software artifact (Zenodo)](https://zenodo.org/records/7144067)

- *A Relational Program Logic with Data Abstraction with Dynamic Framing*.\\
  Anindya Banerjee, Ramana Nagasamudram, David A. Naumann, and Mohammad Nikouei.\\
  ACM Transactions on Programming Languages and Systems (TOPLAS), 2022.\\
  [Pre-print (PDF)]({{ site.url }}/assets/papers/TOPLAS2022.pdf)

- *WhyRel: A Prototype for Relational Verification (research abstract)*.\\
  Ramana Nagasamudram.\\
  International Symposium on Formal Methods (FM), Doctoral Symposium, 2021.\\
  [Article (PDF)]({{ site.url }}/assets/papers/FM2021.pdf), [Talk slides (ODP)]({{ site.url }}/assets/talks/FM2021.odp), [Talk video (FM webpage)](https://lcs.ios.ac.cn/fm2021/doctoral-symposium/)

  Won the best presentation award.

- *Alignment Completeness for Relational Hoare Logics.*\\
  Ramana Nagasamudram and David A. Naumann.\\
  IEEE Logic in Computer Science (LICS), 2021.\\
  [Pre-print (PDF)]({{ site.url }}/assets/papers/LICS2021.pdf), [Talk slides (PDF)]({{ site.url }}/assets/talks/LICS2021.pdf)

----

## Service

**Artifact evaluation**: POPL 2023, ICFP 2023, ICFP 2024\\
**Sub-reviewer**: POPL 2023, ECOOP 2024\\
**Student volunteer**: POPL 2021

----

## Teaching

I've TA'd the following courses at Stevens:
- *Programming Languages* (with Eduardo Bonelli): Spring 2024, Fall 2023, Fall 2022
- *Algorithmic Complexity* (with Sandeep Bhatt): Spring 2023
- *Type systems for Programming Languages* (with Eduardo Bonelli): Spring 2019
- *Algorithms, Design and Implementation* (with Reza Peyrovian): Fall 2018

----

## Software artifacts

- A verified C implementation of Derecho's SST data structure [(Zenodo)](https://zenodo.org/records/10819602)
- The WhyRel relational verifier [(GitHub)](https://github.com/dnaumann/RelRL.git)
- Coq formalization of BiKAT [(Zenodo)](https://zenodo.org/records/7144067)

----