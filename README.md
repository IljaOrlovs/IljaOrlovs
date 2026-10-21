# Ilja Orlovs

**Software Engineer and Technical Lead**

Milton Keynes, UK · [ilja@release.art](mailto:ilja@release.art) · [linkedin.com/in/iorlovs](https://www.linkedin.com/in/iorlovs/) · [github.com/IljaOrlovs](https://github.com/IljaOrlovs) · [release.art](https://www.release.art)

## Summary

Software engineer and technical lead with **15+ years** across cloud platforms, data systems and production AI. Led the ML data platform at Vortexa (**over 1 billion events a day**), built production LLM systems on Azure for a UK financial-services group, and founded Release.art, which publishes open-source Python and MCP tooling. Hands-on in Python, Azure, AWS, Terraform and Kafka, with a focus on regulated, audit-sensitive systems.

## Skills

- **Cloud and infrastructure:** Azure, AWS, Terraform, CI/CD and release engineering, Azure DevOps, Docker
- **AI and ML engineering:** Agentic pipelines (ReAct, reflection, self-consistency), Azure OpenAI, Azure AI Search, Azure AI Foundry, PydanticAI, MCP servers
- **Data platforms:** Kafka, Airflow, Dagster, Databricks, RabbitMQ, Elasticsearch
- **Languages:** Python, TypeScript, Kotlin, Java

## Experience

### AI Engineer, [Stonebridge Group](https://stonebridgegroup.co.uk) (Sep 2025 – Present)
- Engaged to architect and deliver **two production AI platforms** on Azure and to shape the company's AI strategy and analytics roadmap.
- Built a queue-driven platform that monitors **over 500** mortgage broker websites for compliance: Playwright crawls, Azure OpenAI (GPT-4.1) assessment against Stonebridge's rules and the FCA Financial Services Register API, producing annotated screenshots and colour-coded Excel audit reports. Delivered via FastAPI on Azure Functions, with a Vue 3 web UI (later retired in favour of the client's own front end).
- Took over and re-engineered a production agentic AI mortgage-review pipeline handling **about 4–6 cases a day**.
- Advised on enterprise AI strategy, defined Stonebridge analytics use cases and coordinated external AI/ML proof-of-concept contractors and Databricks integration.

**Technologies:** Python, Azure OpenAI, PydanticAI, Databricks, Azure Functions, FastAPI, Terraform, Container Apps

### Founder & DevOps/AI Consultant, [Release.art](https://www.release.art) (Jun 2022 – Present)
_Own limited company, the vehicle for personal ventures._
- Published open-source Python clients and MCP servers for the FCA Financial Services Register and Companies House APIs (fca-api, ch-api, fca-mcp, ch-mcp), plus pydantic-prism and tf-project, all on PyPI with CI-gated trusted publishing.
- Founded Release.art, a consultancy and platform for AI assistants and workflow automation, serving SMEs across industries.
- Built a regulatory-data archive for public registers with tamper-evident records, Merkle manifests, hash chains anchored to Bitcoin and offline verification.

**Technologies:** Python, Terraform, AWS, Azure

### DevOps Consultant, [Stonebridge Group](https://stonebridgegroup.co.uk) (Jan 2025 – Jul 2025)
- Migrated 14 years of historical documents (**30M+**) to Azure Blob Storage with metadata indexing.
- Automated Azure and Azure DevOps infrastructure with Terraform, cutting environment builds **from 8 hours to 15 minutes**.
- Built prototype AI agents for staff extraction and FCA website-change detection; the compliance prototype became a production platform, started in May 2025.

**Technologies:** Azure, Azure DevOps, Terraform, Windows, .NET Framework, PowerShell, Playwright

### Lead Software Engineer, [Vortexa](https://www.vortexa.com) (Sep 2022 – Oct 2024)
- Led the development of the ML data ingestion pipeline: a team delivering pipelines that process **over 1 billion events a day** at a **95% SLA**, built on Kafka, Airflow and Dagster on AWS.
- Designed and launched the 'ML model as a service' deployment framework, cutting the model deployment cycle **from weeks to hours**.
- Responsible for introducing new features and maintaining the overarching data processing pipeline.

**Technologies:** Python, Kotlin, Java, Linux, Docker, Kafka, Airflow, Pandas

### Back End Developer, [AIG](https://www.aig.com) (Oct 2021 – Jun 2022)
- Owned database and API design, security and testing for a document aggregation NLP system.
- Designed an Elasticsearch query generator that extracts the trends identified by the AI, improving trend-extraction accuracy by **35%**.

**Technologies:** Python, Linux, Docker, AWS, RabbitMQ, Elasticsearch

### Principal Software Engineer, [Barclaycard UK](https://www.barclaycard.co.uk) (Sep 2018 – Oct 2021)
_Senior Software/DevOps Engineer from Sep 2018, Principal Software Engineer from Sep 2020. Led a team of four infrastructure automation specialists._
- Helped build a fraud detection platform: cloud-hosted, with components on AWS and on-premises.
- Designed and ran **12 Kafka clusters and 500+ topics**, handling **2 billion messages a day** at **99.999% availability**.

**Technologies:** Chef, Ruby, Python, Terraform, Kafka, AWS, OpenShift, Docker

## Earlier experience

- [RSRCHXchange](https://en.wikipedia.org/wiki/RSRCHXchange), Senior Software Developer (2017–2018)
- [Cranfield University](https://www.cranfield.ac.uk), Software Architect / Developer (2016–2017)
- [Cranfield University IVHM Centre](https://www.cranfield.ac.uk), Software Engineer (2013–2015)
- [Imagination Technologies](https://www.imaginationtech.com), Design Engineer (2010–2013)
- Independent, Freelance Software Developer (2010–2015)
- SIA ANK, Software Developer (2005–2009)

## Projects

### [Tilewick (mc-manager)](https://tilewick.uk), Sole author and owner (Sep 2026 – Present)
Minecraft parental controls: bedtime, playtime and chat-safety limits enforced in the game, on the family's own server with no cloud service and no AI. In private testing; early access open at tilewick.uk.
- About **190,000 lines** of Python, TypeScript, Kotlin and Svelte, with around **1,900 Python tests** at 100% coverage.
- Delivered **78 commits** in four weeks (24 September to 21 October 2026), with a first canary release on 2 October.
- Built solo in under two months with an agentic coding workflow (Claude Code), with 100% coverage gates and CI checks as the quality gate.

### proofpress (proof-pdf), Author (Oct 2026 – Present)
Open-source print-PDF preflight CLI and library that checks PDF/X-4, PDF/A, trim and bleed, ink coverage and image resolution, with TeX Live and veraPDF Docker images.
- Checked print PDFs in four layers (veraPDF PDF/A, PDF/X-4 structure, trim and bleed, colour) with an opt-in K-only text rule; a check whose tool was missing failed rather than being skipped.
- Ran veraPDF and Ghostscript through one asyncio subprocess helper that killed and reaped processes on timeout or cancellation, verifying up to **4** files concurrently by default.

## Education

### MSc by Research, [Cranfield University, School of Applied Sciences](https://www.cranfield.ac.uk) (Oct 2009 – Oct 2010)
[Thesis: Micro-Electro-Mechanical System design synthesis and optimisation by means of Genetic Algorithms](https://dspace.lib.cranfield.ac.uk/handle/1826/6289)

### BSc Computer Science, [University of Latvia](https://www.lu.lv/eng/) (Sep 2005 – Jul 2009)
Thesis: Evolutionary optimisation methods in dynamic environments

- **Languages:** English (fluent), Russian (native), Latvian (advanced)

## Certifications

- MBCS (BCS, The Chartered Institute for IT) (May 2025)
- AWS Certified Security (Jun 2022, lapsed)
- AWS Certified Solutions Architect - Associate (May 2022 – May 2025, lapsed)

---

_CV updated 21 October 2026_
