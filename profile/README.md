<p align="center">
  <img src="https://raw.githubusercontent.com/NexFolia/.github/main/assets/nexfolia-logo-combined.svg" alt="NexFolia" width="240">
</p>

<h3 align="center">Where Data Converges</h3>

<p>
NexFolia is a financial data infrastructure company that helps fund administrators and asset managers modernize their ETL pipelines. Our platform, adAPPter, connects disparate data sources — from Bloomberg to internal systems — into a unified, auditable data flow. We blend deep IT expertise with financial domain knowledge to deliver solutions that institutional clients can trust.
</p>

---

## Organizational Structure

NexFolia operates as an **AI-native organization** — a 25-role structure where humans, hybrid human+AI roles, and autonomous AI agents work together under clear accountability frameworks.

> **[Open interactive org chart](https://nexfolia.github.io/.github/organigram.html)** — zoomable, expandable D3 visualization with agent details

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 30, "rankSpacing": 60}} }%%
flowchart TD
    classDef human fill:#2E8B57,color:#fff,stroke:#0F172A
    classDef hybrid fill:#0D5C63,color:#fff,stroke:#0F172A
    classDef ai fill:#00B894,color:#fff,stroke:#0F172A

    CEO["CEO<br/><small>Human</small>"]:::human

    CTO["CTO<br/><small>Hybrid</small>"]:::hybrid
    CFO["CFO<br/><small>Hybrid</small>"]:::hybrid
    CEO --> CTO
    CEO --> CFO

    PM["Product Mgr<br/><small>Hybrid</small>"]:::hybrid
    HOD["Head of Design<br/><small>Human</small>"]:::human
    GC["Gen. Counsel<br/><small>Human</small>"]:::human
    MD["Mkt. Director<br/><small>Human</small>"]:::human
    SD["Sales Director<br/><small>Human</small>"]:::human
    OM["Ops Manager<br/><small>Hybrid</small>"]:::hybrid
    CEO --> PM
    CEO --> HOD
    CEO --> GC
    CEO --> MD
    CEO --> SD
    CEO --> OM

    VPE["VP Eng<br/><small>Human</small>"]:::human
    CTO --> VPE

    SFE["Sr. Fullstack<br/><small>Hybrid</small>"]:::hybrid
    BE["Backend Eng<br/><small>Hybrid</small>"]:::hybrid
    FE["Frontend Eng<br/><small>Hybrid</small>"]:::hybrid
    DOE["DevOps Eng<br/><small>Hybrid</small>"]:::hybrid
    QA["QA Eng<br/><small>AI</small>"]:::ai
    VPE --> SFE
    VPE --> BE
    VPE --> FE
    VPE --> DOE
    VPE --> QA

    BA["Biz Analyst<br/><small>Hybrid</small>"]:::hybrid
    PM --> BA
    DA["Data Analyst<br/><small>AI</small>"]:::ai
    BA --> DA

    UXD["UX/UI<br/><small>Hybrid</small>"]:::hybrid
    HOD --> UXD

    SP["Sr. Paralegal<br/><small>Hybrid</small>"]:::hybrid
    CA["Compliance<br/><small>AI</small>"]:::ai
    GC --> SP
    GC --> CA

    CW["Content<br/><small>Hybrid</small>"]:::hybrid
    SEO["SEO<br/><small>AI</small>"]:::ai
    MD --> CW
    MD --> SEO

    SDR["SDR<br/><small>AI</small>"]:::ai
    SD --> SDR

    HRC["HR Coord.<br/><small>Hybrid</small>"]:::hybrid
    ITS["IT/Sec Admin<br/><small>Hybrid</small>"]:::hybrid
    OM --> HRC
    OM --> ITS
```

**Legend:** Human (6) · Hybrid (14) · AI (5) · **25 roles total**

---

<p align="center">
  <sub><strong><span style="color:#0D5C63">Nex</span><span style="color:#2E8B57">Folia</span></strong> — Precision. Convergence. Transparency. Evolution.</sub>
</p>
