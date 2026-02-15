<p align="center">
  <img src="https://raw.githubusercontent.com/NexFolia/.github/main/assets/nexfolia-logo-combined.svg" alt="NexFolia" width="240">
</p>

<h3 align="center">Where Data Converges</h3>

<p align="center">
NexFolia is a financial data infrastructure company that helps fund administrators and asset managers modernize their ETL pipelines. Our platform, adAPPter, connects disparate data sources — from Bloomberg to internal systems — into a unified, auditable data flow. We blend deep IT expertise with financial domain knowledge to deliver solutions that institutional clients can trust.
</p>

<p align="center"><em>A <strong>jeannAI</strong> company</em></p>

---

## Organizational Structure

NexFolia operates as an **AI-native organization** — an 18-role NexFolia structure (22 nodes incl. holding context) where humans, hybrid human+AI roles, and autonomous AI agents work together under clear accountability frameworks.

> **[Open interactive org chart](https://nexfolia.github.io/.github/organigram.html)** — zoomable, expandable D3 visualization with agent details

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 30, "rankSpacing": 60}} }%%
flowchart TD
    classDef human fill:#2E8B57,color:#fff,stroke:#0F172A
    classDef hybrid fill:#0D5C63,color:#fff,stroke:#0F172A
    classDef ai fill:#00B894,color:#fff,stroke:#0F172A
    classDef holding fill:#1E1B4B,color:#fff,stroke:#0F172A

    %% Holding context nodes (jeannAI)
    CEO["CEO<br/><small>jeannAI</small>"]:::holding
    GC["Gen. Counsel<br/><small>jeannAI</small>"]:::holding
    MD["Mkt. Director<br/><small>jeannAI</small>"]:::holding
    HOD["Head of Design<br/><small>jeannAI</small>"]:::holding
    CEO --> GC
    CEO --> MD
    CEO --> HOD

    %% NexFolia C-Suite & Directors
    CTO["CTO<br/><small>Hybrid</small>"]:::hybrid
    PM["Product Mgr<br/><small>Hybrid</small>"]:::hybrid
    SD["Sales Director<br/><small>Human</small>"]:::human
    CEO --> CTO
    CEO --> PM
    CEO --> SD

    %% Engineering
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

    %% Product
    BA["Biz Analyst<br/><small>Hybrid</small>"]:::hybrid
    MIA["Market Intel<br/><small>AI</small>"]:::ai
    PM --> BA
    PM --> MIA
    DA["Data Analyst<br/><small>AI</small>"]:::ai
    BA --> DA

    %% Design
    UXD["UX/UI<br/><small>Hybrid</small>"]:::hybrid
    HOD --> UXD

    %% Legal
    SP["Sr. Paralegal<br/><small>Hybrid</small>"]:::hybrid
    CA["Compliance<br/><small>AI</small>"]:::ai
    GC --> SP
    GC --> CA

    %% Marketing & Sales
    CW["Content<br/><small>Hybrid</small>"]:::hybrid
    SEO["SEO<br/><small>AI</small>"]:::ai
    MD --> CW
    MD --> SEO

    SDR["SDR<br/><small>AI</small>"]:::ai
    SD --> SDR
```

**Legend:** Human (2) · Hybrid (10) · AI (6) · Holding (4) · **22 nodes**

---

<p align="center">
  <sub><strong><span style="color:#0D5C63">Nex</span><span style="color:#2E8B57">Folia</span></strong> — Precision. Convergence. Transparency. Evolution.</sub>
</p>
