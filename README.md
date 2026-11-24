<h1 align="center">far-reach</h1>

<p align="center"><code>Engineer who ships. Researcher who's learning too.</code></p>
<p align="center"><i>Deep learning for the things that crack, corrode, and compound.</i></p>

---

### The short version

I work on two problems that shouldn't have anything in common but do: **how structures fail**, and **how markets cycle**. Both reward patience, punish pattern-matching, and reveal themselves only to people willing to sit with the data longer than is comfortable.

Trained originally as an offshore engineer. Taught myself deep learning because waiting for permission to learn something is a terrible strategy.

---

### What I'm actually working on

🏗️ **Screen, then confirm: drone inspection that looks inside concrete.** Cameras only see the surface. So small drones screen every zone of a structure with a network of 0.14 M parameters, and a contact unit takes a single ultrasonic reading only where they flag damage. Both stages are tested on public data from independent labs, on specimens the models never saw. In simulation it finds 72% of what testing every zone finds, with 27% of the contacts. No hardware built yet; every assumption is stated and varied.

<p align="center">
  <img src="./screen-confirm.svg" alt="Animated screen, then confirm pipeline: scout, flag, confirm, fuse" width="680"/>
</p>

🔎 **Correcting my own preprint.** When I audited the code of my first paper ([doi.org/10.31224/7685](https://doi.org/10.31224/7685)) I found a class-order bug and a deeper flaw: each damage class came from a single image source, so the classifier had partly learned the source, not the damage. The new paper documents both, regenerates every affected result, and shows how much each flaw actually mattered. Published in full rather than fixed quietly.

📊 **Quantitative tools for gold and macro cycles.** A dashboard and algorithmic framework for tracking cycle-based market structure. In active private development. I lost a lot of money learning what I know. Now I'm building the tool I wish I'd had.

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

---

### Featured

[`structural-crack-detection`](https://github.com/far-reach/structural-crack-detection): code, results and weights for both studies, the screen-then-confirm paper (v2.0) and the corrected preprint (v1.0). Every number traces to a result file with its run manifest. Reproducible from open datasets.

---

### Working principles

> Ship before you're ready. Iterate in public. Respect the compounders.
>
> Cycles teach. I try to listen.

---

<p align="center"><i>Built through cycles.</i> 🥧</p>

<p align="center">
  <a href="https://orcid.org/0009-0007-8865-2300"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white"/></a>
  <a href="https://linkedin.com/in/farhad-abtahi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
</p>
