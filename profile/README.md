<p align="left">
  <a href="https://parkinsonsroadmap.org/">
    <img src="https://storage.googleapis.com/dnastack-assets/explorer/asap-parkinsons/asap-crn-cloud-logo.png" alt="ASAP CRN Cloud Logo" width="520"/>
  </a>
</p>

<h1 align="left">Welcome to the ASAP CRN GitHub 👋 </h1>

<p align="left">
  Open science resources, workflows, and tools for exploring ASAP CRN Cloud data.
</p>

<p align="left">
  <a href="https://cloud.parkinsonsroadmap.org/collections">
    <img src="https://img.shields.io/badge/Explore-CRN%20Cloud-0078D4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Explore CRN Cloud"/>
  </a>
  <a href="https://asap-crn.github.io/asap-crn-learning-lab/">
    <img src="https://img.shields.io/badge/Utilize-Learning%20Lab-34A853?style=for-the-badge&logo=jupyter&logoColor=white" alt="Learning Lab"/>
  </a>
  <a href="https://parkinsonsroadmap.org/research-network/#">
    <img src="https://img.shields.io/badge/About-ASAP%20CRN-6C3483?style=for-the-badge" alt="About ASAP CRN"/>
  </a>
</p>

---

The [ASAP Collaborative Research Network (CRN)](https://parkinsonsroadmap.org/research-network/#) is the first of its kind to foster an environment that facilitates the rapid and free exchange of scientific ideas to spark new discoveries for Parkinson’s disease (PD). 
The CRN is an international, multidisciplinary, and multi-institutional network of collaborating investigators working to address high-priority basic science questions. Teams are awarded grant funding through request for applications in partnership with the Michael J. Fox Foundation for Parkinson’s Research (MJFF).

---

## Start Here

| Goal | Resource |
|---|---|
| Explore available datasets and collections | [CRN Cloud Explorer](https://cloud.parkinsonsroadmap.org/collections) |
| Run tutorials and sample notebooks | [ASAP CRN Learning Lab](https://asap-crn.github.io/asap-crn-learning-lab/) |
| Learn more about the research network | [ASAP CRN Website](https://parkinsonsroadmap.org/research-network/#) |

---

# Repositories

## Learning Resources

![Type](https://img.shields.io/badge/Type-Tutorials-34A853?style=flat-square)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Verily%20Workbench-4285F4?style=flat-square)

Hands-on tutorials, sample notebooks, and reproducible examples for researchers getting started with CRN Cloud data.

| Repository | Description |
|---|---|
| [`asap-crn-learning-lab`](https://github.com/ASAP-CRN/asap-crn-learning-lab) | Tutorials, sample notebooks, and reproducible workflows for exploring CRN Cloud data in Verily Workbench |

---

## Cloud Data Infrastructure

![Type](https://img.shields.io/badge/Type-Cloud%20Infrastructure-0078D4?style=flat-square)
![Data](https://img.shields.io/badge/Data-Releases%20%26%20Collections-00A3A3?style=flat-square)

Public records and automation resources that describe CRN Cloud releases, data collections, and orchestration workflows.

| Repository | Description |
|---|---|
| [`cloud-releases`](https://github.com/ASAP-CRN/cloud-releases) | Versioned CRN Cloud release records and release-management resources |
| [`cloud-collections`](https://github.com/ASAP-CRN/cloud-collections) | Public definitions of CRN Cloud data collections |
| [`cloud-orchestration`](https://github.com/ASAP-CRN/cloud-orchestration) | Workflows and automation for coordinating CRN Cloud releases |

---

## Analysis Pipeline Workflows

![Type](https://img.shields.io/badge/Type-Analysis%20Workflows-6C3483?style=flat-square)
![Workflow](https://img.shields.io/badge/Workflow-WDL-7952B3?style=flat-square)
![Data](https://img.shields.io/badge/Data-PMDBS-8E44AD?style=flat-square)

Public [WDL](https://openwdl.org/) workflows used to curate and harmonize CRN datasets, including postmortem-derived brain sequencing resources.

| Repository | Description |
|---|---|
| [`pmdbs-sc-rnaseq-wf`](https://github.com/ASAP-CRN/pmdbs-sc-rnaseq-wf) | PMDBS single-cell RNA-seq curation workflow |
| [`pmdbs-bulk-rnaseq-wf`](https://github.com/ASAP-CRN/pmdbs-bulk-rnaseq-wf) | PMDBS bulk RNA-seq curation workflow |
| [`wf-common`](https://github.com/ASAP-CRN/wf-common) | Shared WDL tasks, utilities, and workflow components |

---

## Tools

![Type](https://img.shields.io/badge/Type-Tools-34495E?style=flat-square)
![Use](https://img.shields.io/badge/Use-Validation%20%26%20Utilities-16A085?style=flat-square)

Reusable and operational tools that support CRN Cloud workflows, metadata validation, and reproducibility.

| Repository | Description |
|---|---|
| [`crn-utils`](https://github.com/ASAP-CRN/crn-utils) | Utility functions used across CRN Cloud workflows and resources |
| [`crn-meta-validate`](https://github.com/ASAP-CRN/crn-meta-validate) | Streamlit app for validating CRN metadata against expected formats and schemas |

---

## Private Operational Resources

![Type](https://img.shields.io/badge/Type-Operations-555555?style=flat-square)
![Access](https://img.shields.io/badge/Access-Private-lightgrey?style=flat-square)
![Purpose](https://img.shields.io/badge/Purpose-Internal%20Support-999999?style=flat-square)

Some repositories support the internal mechanics of building and maintaining the CRN Cloud. These remain private because they may contain operational configuration or internal process tooling.

Scientific outputs, workflow methods, release records, and public provenance are captured in the public repositories listed above.

| Repository | Description |
|---|---|
| `asap-crn-cloud-release-resources` | Internal release-resource management |
| `asap-crn-cloud-dataset-metadata` | Internal dataset metadata operations |

---

## How to Navigate

| I want to... | Start with... |
|---|---|
| Find CRN datasets | [CRN Cloud Explorer](https://cloud.parkinsonsroadmap.org/collections) |
| Run example analyses | [ASAP CRN Learning Lab](https://asap-crn.github.io/asap-crn-learning-lab/) |
| Understand data releases | [`cloud-releases`](https://github.com/ASAP-CRN/cloud-releases) |
| Inspect data collections | [`cloud-collections`](https://github.com/ASAP-CRN/cloud-collections) |
| Review curation workflows | [`pmdbs-sc-rnaseq-wf`](https://github.com/ASAP-CRN/pmdbs-sc-rnaseq-wf) and [`pmdbs-bulk-rnaseq-wf`](https://github.com/ASAP-CRN/pmdbs-bulk-rnaseq-wf) |
| Explore validation and utility tools | [`crn-utils`](https://github.com/ASAP-CRN/crn-utils) and [`crn-meta-validate`](https://github.com/ASAP-CRN/crn-meta-validate) |
