# Awesome Ai in Europe

![Build AI Systems in Europe](hero.png)

> List of resources for building AI systems in Europe: infrastructure, agent tooling, vector systems, deep-tech applications, models, datasets, compliance tooling, funding, and research labs.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## At a glance

| Section | Focus | Count |
| --- | --- | ---: |
| [Inference Providers](#inference-providers) | EU-hosted APIs, sovereign clouds, and managed model access | 17 |
| [Agent Frameworks & Developer Tooling](#agent-frameworks--developer-tooling) | Agent builders, orchestration, and AI-native dev platforms | 5 |
| [RAG, Vector & Data Tooling](#rag-vector--data-tooling) | Retrieval, vector search, reranking, and data curation | 4 |
| [Datasets (GDPR-Safe)](#datasets-gdpr-safe) | Licensed corpora, speech, and legal data | 10 |
| [EU AI Act Tooling](#eu-ai-act-tooling) | Risk classification, documentation, audit, and assessment | 10 |
| [Grants & Compute](#grants--compute) | Funding programs and European supercomputing access | 23 |
| [Models](#models) | Open models and model families for European languages | 46 |
| [AI Companies & Products](#ai-companies--products) | Flagship European AI companies and developer-facing products | 4 |
| [Deep Tech AI & Frontier Applications](#deep-tech-ai--frontier-applications) | Autonomy, robotics, chips, scientific AI, and frontier systems | 9 |
| [Multilingual Resources](#multilingual-resources) | Language-tech projects and Europe-wide corpora | 2 |
| [Research Labs & Institutes](#research-labs--institutes) | Academic and applied AI research hubs | 31 |
| [Communities & Events](#communities--events) | Ecosystem groups, conferences, and media | 20 |

## Featured Picks

| Pick | Section | Why it stands out |
| --- | --- | --- |
| [Infomaniak AI Services](https://www.infomaniak.com/en/hosting/ai-services) | Inference Providers | Swiss privacy-first managed inference with a free tier and Geneva hosting. |
| [Haystack](https://docs.haystack.deepset.ai/docs) | Agent Frameworks & Developer Tooling | One of Europe's most established open stacks for RAG and agent orchestration. |
| [Qdrant](https://qdrant.tech/documentation/) | RAG, Vector & Data Tooling | A European-founded vector database that has become core infrastructure for modern RAG systems. |
| [JUPITER (FZJ)](https://www.fz-juelich.de/en/ias/jsc/jupiter) | Grants & Compute | Europe's first exascale system, designed for large-scale AI training and research. |
| [Occiglot](https://occiglot.eu/) | Models | Pan-European foundation-model initiative for all 24 official EU languages. |
| [ElevenLabs](https://elevenlabs.io/about) | AI Companies & Products | A globally important European AI audio company with strong developer tooling and agent momentum. |
| [Prophesee](https://www.prophesee.ai/) | Deep Tech AI & Frontier Applications | A rare European company building neuromorphic vision hardware and AI for autonomy and industrial perception. |
| [COMPL-AI](https://compl-ai.org/) | EU AI Act Tooling | A benchmark-driven ETH Zurich project that turns AI Act discussion into evaluable model behavior. |
| [Kyutai](https://kyutai.org/) | Research Labs & Institutes | A rare open-science lab proving frontier voice research can still be done transparently. |
| [Swiss AI Association](https://swissai.ch/) | Communities & Events | Switzerland's primary AI ecosystem body for research, business, and policy. |

The section lists below keep each entry to one line, with tags and licensing notes to make trust, openness, and geography easy to scan at a glance while still explaining why each resource matters.

## Browse by Geography

| Region | What to look for |
| --- | --- |
| Switzerland | Sovereign inference, Swiss-language resources, applied AI hubs, and research bodies |
| Nordics | Nordic language models, regional corpora, and strong public compute programs |
| DACH | German-language models, enterprise inference, agent tooling, and AI Act tooling |
| Western Europe | Major labs, enterprise AI services, AI-native products, deep-tech AI, and large multilingual projects |
| Southern Europe | Catalan, Spanish, Italian, Portuguese, and Greek resources |
| Central & Eastern Europe | Slavic, Baltic, and Balkan models, labs, and communities |
| Pan-European | EU-wide datasets, compute, funding, and foundational models |

## Contents

- [At a glance](#at-a-glance)
- [Featured Picks](#featured-picks)
- [Browse by Geography](#browse-by-geography)
- [Inference Providers](#inference-providers)
- [Agent Frameworks & Developer Tooling](#agent-frameworks--developer-tooling)
- [RAG, Vector & Data Tooling](#rag-vector--data-tooling)
- [Datasets (GDPR-Safe)](#datasets-gdpr-safe)
- [EU AI Act Tooling](#eu-ai-act-tooling)
- [Grants & Compute](#grants--compute)
- [Models](#models)
- [AI Companies & Products](#ai-companies--products)
- [Deep Tech AI & Frontier Applications](#deep-tech-ai--frontier-applications)
- [Multilingual Resources](#multilingual-resources)
- [Research Labs & Institutes](#research-labs--institutes)
- [Communities & Events](#communities--events)
- [Contributing](#contributing)
- [Scope & Disclaimer](#scope--disclaimer)
- [License](#license)

---

## Inference Providers

EU-based or EU-compliant LLM inference hosts.

- [Mistral AI](https://mistral.ai/) — French AI company and one of Europe's best-known frontier-model labs, offering EU-hosted API endpoints and open-weight releases that give European builders a credible local alternative to US hyperscaler stacks. `[EU-hosted]` `[Open weights]`
- [Aleph Alpha](https://aleph-alpha.com/) — German sovereign AI company known for enterprise LLMs and regulated deployment support, with a strong focus on explainability, secure hosting, and public-sector adoption. `[EU-hosted]` `[GDPR-DPA]`
- [OVHcloud AI Endpoints](https://www.ovhcloud.com/en/public-cloud/ai-endpoints/catalog/) — Managed AI inference on OVHcloud's EU-sovereign infrastructure with open-source models, making it easier to run European AI workloads on established cloud rails. `[EU-hosted]` `[GDPR-DPA]`
- [Scaleway Generative APIs](https://www.scaleway.com/en/generative-apis/) — French cloud provider running managed LLM inference from EU data centers, useful for teams that want a simpler API path without leaving European hosting. `[EU-hosted]` `[GDPR-DPA]`
- [Deutsche Telekom Industrial AI Cloud](https://www.telekom.com/en/company/details/industrial-ai-cloud-1100158) — German sovereign AI cloud from T-Systems for training and running models inside Germany, aimed at industrial and regulated deployments that need strong residency guarantees. `[EU-hosted]` `[GDPR-DPA]`
- [IONOS AI Model Hub](https://cloud.ionos.com/managed/ai-model-hub) — German cloud provider offering LLM inference from EU-sovereign data centers, giving smaller teams a straightforward way to consume models under familiar infrastructure contracts. `[EU-hosted]` `[GDPR-DPA]`
- [Nebius AI](https://nebius.com/) — Amsterdam-headquartered AI cloud offering GPU clusters and LLM API with EU data-residency and zero-retention options, making it attractive for high-performance training and enterprise inference. `[EU-hosted]` `[GDPR-DPA]` `[Free tier]`
- [STACKIT](https://stackit.com/en/) — German sovereign cloud platform from Schwarz Group offering scalable AI compute and model hosting, with a strong positioning around European digital sovereignty for large enterprises. `[EU-hosted]` `[GDPR-DPA]`
- [Nscale](https://www.nscale.com/) — UK-based high-performance GPU cloud and AI infrastructure provider, notable for giving European teams access to serious AI compute without defaulting to US cloud incumbents. `[EU-hosted]`
- [Verda (DataCrunch)](https://verda.com/) — Nordic green-compute AI cloud provider running H100 clusters in Finland on renewable energy, combining high-end training capacity with a sustainability-first story. `[EU-hosted]` `[GDPR-DPA]`
- [Gcore Inference](https://gcore.com/) — Luxembourg-based edge and cloud AI inference platform with sovereign EU infrastructure and 200+ Tbps network, useful when low-latency delivery and geographic reach both matter. `[EU-hosted]`
- [Infomaniak AI Services](https://www.infomaniak.com/en/hosting/ai-services) — Swiss privacy-first managed AI services from Geneva with a developer-friendly API surface, standing out as an accessible Swiss-hosted option for startups and SMBs. `[EU-hosted]` `[GDPR-DPA]` `[Free tier]`
- [Exoscale GPU Compute](https://www.exoscale.com/gpu/) — Swiss cloud provider offering A100/H100 GPU instances for model serving and AI workloads, giving privacy-conscious teams a practical European compute base for custom stacks. `[EU-hosted]` `[GDPR-DPA]`
- [DeepL API](https://www.deepl.com/pro-api) — German translation AI platform with a widely used API for multilingual products and workflows, and one of the clearest examples of a European AI product with global developer relevance. `[EU-hosted]` `[GDPR-DPA]`
- [Swisscom Swiss AI Platform](https://www.swisscom.ch/en/business/enterprise/offer/platforms-applications/data-driven-business/swiss-ai-platform.html) — Swisscom's sovereign AI platform from Switzerland's largest telecom operator, positioned for customers that want AI services embedded in Swiss enterprise infrastructure. `[EU-hosted]` `[GDPR-DPA]`
- [Alpine AI (SwissGPT)](https://alpineai.swiss/) — Swiss-hosted enterprise LLM access platform with strong privacy positioning and multilingual support, especially relevant for German-speaking and Swiss-regulated environments. `[EU-hosted]` `[GDPR-DPA]`
- [LightOn](https://lighton.ai/) — French enterprise AI company focused on managed LLM products and EU-hosted infrastructure, representing the European push toward enterprise-ready generative AI beyond raw model releases. `[EU-hosted]`

## Agent Frameworks & Developer Tooling

Resources for building AI agents, orchestration pipelines, and AI-native product workflows in Europe.

- [pi.dev](https://pi.dev/) — Austrian terminal coding harness by Mario Zechner for extensible coding-agent workflows, packages, and custom context engineering; a notable European-native entry in the fast-growing coding-agent layer.
- [Haystack](https://docs.haystack.deepset.ai/docs) — German open-source framework for production AI agents, retrieval-augmented generation pipelines, and multimodal search, and one of the most established European orchestration stacks. `[Open-source]`
- [Dust](https://docs.dust.tt/docs) — French enterprise platform for building and orchestrating secure AI agents connected to company knowledge and tools, making it one of the clearest European players in business-grade agent systems. `[Proprietary]`
- [Lovable](https://docs.lovable.dev/introduction/welcome) — Stockholm-built full-stack AI development platform for creating and deploying web apps from natural language, with an increasingly explicit focus on agents, evals, and AI-native software creation. `[Proprietary]`
- [Runner H](https://hcompany.ai/runner-h) — Paris-built web agent platform from H Company for browser automation and multi-step execution in enterprise workflows, representing the shift from chatbots toward software action systems. `[Proprietary]`

## RAG, Vector & Data Tooling

Resources for retrieval, vector search, reranking, and data curation for European AI systems.

- [Qdrant](https://qdrant.tech/documentation/) — Germany-based open-source vector database and retrieval engine for production RAG, search, and agent memory, widely adopted because it combines strong performance with a developer-friendly operating model. `[Open-source]`
- [Weaviate](https://weaviate.io/developers/weaviate/introduction) — Netherlands-founded open-source vector database with hybrid search, filtering, and RAG-friendly modules, making it a major European building block for knowledge-heavy AI applications. `[Open-source]`
- [Argilla](https://argilla.io/) — Spain-born open-source data curation platform for labeling, feedback collection, evaluation, and improving LLM datasets, especially valuable when model quality depends on human-in-the-loop iteration. `[Open-source]`
- [Jina AI](https://jina.ai/es/about-us/) — Berlin-founded search AI tooling company offering embeddings, rerankers, readers, and small models for RAG and agent systems; acquired by Elastic on October 9, 2025, but still highly relevant as European-founded search infrastructure. `[Proprietary]`

## Datasets (GDPR-Safe)

Datasets with clear EU-compatible licensing for training and evaluation.

- [OPUS Corpora](https://opus.nlpl.eu/) — University of Helsinki-led collection of freely available parallel corpora for European machine translation, and one of the practical backbones for multilingual benchmarking, bootstrapping, and product evaluation. `Various open licenses`
- [EuroParl](https://www.statmt.org/europarl/) — Landmark parallel corpus from European Parliament proceedings in 21 EU languages, widely used because it captures high-quality aligned text across the continent's major official languages. `Free for research`
- [OSCAR](https://oscar-project.org/) — Inria- and DFKI-backed open multilingual web corpus with per-language subsets and metadata, giving researchers a large-scale base for training models beyond English-only web data. `CC0-1.0`
- [SwissDial](https://mtc.ethz.ch/publications/open-source/swiss-dial.html) — ETH Zurich corpus of spoken Swiss German dialects with audio and High German transcripts, making it unusually valuable for speech, dialect modeling, and Swiss-language AI. `Research access`
- [EUR-Lex](https://eur-lex.europa.eu) — Official EU law and legal documents across all EU languages, useful for legal NLP and especially important for retrieval systems that need primary-source European regulation text. `Public domain (EU reuse policy)`
- [JRC-Acquis](https://joint-research-centre.ec.europa.eu/language-technology-resources/jrc-acquis_en) — European Commission parallel legal corpus covering the EU acquis in 22 languages, giving builders aligned legal language across jurisdictions rather than just generic translation data. `Public domain`
- [Leipzig Corpora Collection](https://corpora.uni-leipzig.de/en) — German university corpus collection with comparable monolingual resources across many European languages, helpful when smaller-language coverage matters more than pure benchmark popularity. `Academic`
- [Europeana Data](https://pro.europeana.eu/data) — European cultural-heritage data from museums, libraries, and archives across the continent, useful for retrieval, multimodal research, and historically grounded European knowledge systems. `Mixed`
- [Portuguese Corpus (AC/DC)](https://www.linguateca.pt/) — Large Portuguese text corpus for NLP research from the Linguateca ecosystem, and still one of the most practical starting points for serious Portuguese-language work. `Academic`
- [Nordic Dialect Corpus](https://www.tekstlab.uio.no/norsk/dialekt/) — University of Oslo collection of Nordic dialect recordings and transcriptions, especially useful for speech technology that needs to reflect real regional variation rather than standard-language assumptions. `Academic`

## EU AI Act Tooling

Resources for EU AI Act compliance workflows built by European organizations. This section lists tools for understanding and preparing for EU AI Act requirements — it does not constitute legal advice (verify current enforcement schedule before acting).

### Risk Classification

- [ai-act-checklist](https://github.com/AlgorithmWatch/ai-act-checklist) — German open-source checklist tool from AlgorithmWatch for mapping AI systems to EU AI Act risk categories, useful as a practical first pass before legal review or formal governance work. `[Open-source]`

### Monitoring / Audit

- [COMPL-AI](https://compl-ai.org/) — ETH Zurich benchmark framework for evaluating LLM compliance with the EU AI Act, functioning as a useful litmus test for trustworthy model behavior rather than just a documentation exercise. `[Open-source]` `[Academic]`
- [LNE AI Process Certification](https://www.lne.fr/en/service/certification/certification-processes-ai) — French national metrology lab certification covering design, development, evaluation, and maintenance processes aligned with EU AI Act trust requirements, notable because it brings institutional rigor to process-level AI assurance. `[Free]`
- [Z-Examen](https://z-examen.de/en/) — German research project developing a standardized testing and certification procedure for AI system quality and safety, reflecting Europe's push toward repeatable technical evaluation rather than ad hoc claims. `[Open-source]`
- [Saidot](https://www.saidot.ai/) — Finnish AI governance and transparency platform for managing risks and documentation, aimed at teams that need to turn policy obligations into repeatable operating workflows. `[Proprietary]`
- [Enzai](https://www.enzai.ai/) — Northern Ireland-based AI governance platform for compliance and regulatory risk management, with a strong emphasis on documentation, controls, and enterprise readiness. `[Proprietary]`
- [Holistic AI](https://www.holisticai.com/) — AI governance, risk, and compliance platform with a strong auditing and transparency focus, useful for organizations that want technical oversight and board-level governance in one place. `[Proprietary]`

### Conformity Assessment Prep

- [ALTAI Self-Assessment](https://altai.insight-centre.org/) — Assessment List for Trustworthy AI from the EU High-Level Expert Group, a foundational self-assessment tool that still helps teams structure early trustworthy-AI reviews before more formal audits. `[Free]`

### Privacy-Preserving Infrastructure

- [Zama](https://zama.ai/) — French startup pioneering Fully Homomorphic Encryption (FHE) tools for running machine learning on encrypted data, making it possible to process sensitive medical or financial information without exposing raw inputs. `[Open-source]`
- [Flower Labs](https://flower.ai/) — German-built open-source framework for Federated Learning, enabling AI model training on decentralized, sensitive data such as hospital or banking systems where moving the data is often the real blocker. `[Open-source]`

## Grants & Compute

Funding and compute programs available to EU-based developers and researchers.

### EU Grants

- [Horizon Europe AI Calls](https://ec.europa.eu/info/funding-tenders/opportunities/portal/) — EU framework programme funding for AI research and innovation projects across Europe, and still the most important pan-European public funding channel for ambitious AI collaborations (verify current enforcement schedule before acting). `[EU-funded]`
- [Digital Europe Programme](https://digital-strategy.ec.europa.eu/en/activities/digital-programme) — EU funding programme for deploying AI, cybersecurity, and advanced digital skills capacities, aimed less at pure research and more at ecosystem rollout and operational capacity building. `[EU-funded]`

### National Programs

- [France 2030 — AI National Strategy](https://www.gouvernement.fr/france-2030) — French national programme funding AI research labs, compute infrastructure, and startups, and one of the clearest examples of Europe backing AI as a long-term industrial priority. `[National]`
- [German BMWK AI Programs](https://www.bmwk.de/Redaktion/EN/Dossier/artificial-intelligence.html) — German Federal Ministry for Economic Affairs funding for applied AI projects and SMEs, especially relevant for companies translating research into industrial deployment. `[National]`
- [NL AIC — Netherlands AI Coalition](https://nlaic.com/) — Dutch public-private partnership coordinating national AI funding and strategy, useful as both a funding signal and a map of the Dutch AI ecosystem. `[National]`
- [Innosuisse AI Funding](https://www.innosuisse.ch/inno/en/home/start-your-innovation-project/innovation-projects.html) — Swiss federal innovation funding for AI startups, applied research, and industry partnerships, often acting as the bridge between strong Swiss research and commercialization. `[National]`

### Free Compute

- [EuroHPC JU](https://eurohpc-ju.europa.eu/) — Joint Undertaking providing access to European pre-exascale and petascale supercomputers for AI research, and the main umbrella through which Europe turns sovereign compute policy into real machine time. `[EU-funded]` `[Free for researchers]`
- [CINECA](https://www.cineca.it/en) — Italian interuniversity computing center offering HPC resources including the Leonardo supercomputer, a major access point for Italian and European large-scale research workloads. `[Academic]`
- [LUMI Supercomputer](https://www.lumi-supercomputer.eu/) — One of Europe's fastest supercomputers in Finland, open to EU researchers for large-scale AI workloads and often central to Nordic and pan-European model work. `[EU-funded]` `[Academic]`
- [Meluxina (LuxProvide)](https://luxprovide.lu/) — Luxembourg EuroHPC-class supercomputer offering AI research compute for European researchers, especially relevant for teams that need serious infrastructure but not hyperscaler complexity. `[EU-funded]` `[Free for researchers]`
- [MareNostrum 5 (BSC)](https://www.bsc.es/marenostrum/marenostrum-5) — Barcelona supercomputer with a dedicated AI accelerator partition for EU research workloads, giving Southern Europe a flagship anchor for large-scale training and simulation. `[EU-funded]` `[Academic]`
- [JUPITER (FZJ)](https://www.fz-juelich.de/en/ias/jsc/jupiter) — Europe's first exascale supercomputer, designed for foundation-model training and large-scale AI research as a hardware foundation for the next generation of European models. `[EU-funded]` `[Academic]`

### Accelerators

- [ELLIS PhD Program](https://ellis.eu/phd-postdoc) — Pan-European network offering funded PhD positions in machine learning and AI across top labs, and one of the strongest talent pipelines into the European research ecosystem. `[Academic]`
- [EIT Digital Accelerator](https://www.eitdigital.eu/accelerator/) — EU-backed accelerator supporting AI and deep-tech startups with market access and funding, useful when a technically strong team needs help crossing into commercial scale. `[EU-funded]`

### Research Funding

- [SNSF BRIDGE](https://www.bridge.ch/en/) — Swiss programme helping research projects transition into innovation and commercialization, particularly useful when strong academic work is ready to leave the lab. `[National]`
- [FNR (Luxembourg National Research Fund)](https://www.fnr.lu/) — Luxembourg's main public research funder, including AI- and data-related calls that help a smaller ecosystem punch above its size. `[National]`
- [FFG — Austrian Research Promotion Agency](https://www.ffg.at/en) — Austrian national funding agency for R&D projects including AI, providing a practical route for applied innovation and industry collaboration. `[National]`
- [Innovation Fund Serbia](https://www.innovationfund.rs/en) — Serbian innovation funding agency, relevant for early-stage and growth-stage technology projects in South-East Europe. `[National]`
- [HRZZ — Croatian Science Foundation](https://www.hrzz.hr/) — Croatian national science funding body, supporting the research layer that underpins a still-growing Croatian AI ecosystem. `[National]`
- [NKFIH — Hungarian National Research, Development and Innovation Office](https://nkfih.gov.hu/english) — Hungarian national funding body for research and innovation, including programs that can support local AI capability building. `[National]`
- [FCT — Foundation for Science and Technology](https://www.fct.pt/en/) — Principal national research funding agency in Portugal, and a key anchor for university-led AI research and long-horizon technical work. `[National]`
- [LMT — Research Council of Lithuania](https://www.lmt.lt/en) — Lithuanian national research funding agency, important for sustaining Baltic AI research capacity and cross-border collaboration. `[National]`
- [LZP — Latvian Council of Science](https://www.lzp.lv/en) — Latvian national science funding body, helping maintain local research depth in a smaller but strategically relevant ecosystem. `[National]`

## Models

Open model releases and model families useful for researchers and builders in Europe.

### Swiss & Alpine

- [SwissBERT](https://huggingface.co/ZurichNLP/swissbert) — ZurichNLP multilingual encoder for Switzerland's national languages, trained on large-scale Swiss news corpora and useful when local linguistic nuance matters more than generic European coverage. `[Open weights]` `CC-BY-NC-4.0`
- [Meditron (EPFL)](https://huggingface.co/epfl-llm/meditron-70b) — EPFL open medical LLM suite adapted from Llama 2 for clinical and biomedical use cases, showing how European labs are pushing domain-specific models beyond general chat. `[Open weights]` `Llama 2 Community License`

### Germanic (DE, NL, SV, DA, NO, IS, FO)

- [German BERT](https://huggingface.co/dbmdz/bert-base-german-cased) — BERT model pre-trained on German text by the Bavarian State Library, still a practical baseline for many German NLP tasks where smaller encoders outperform generic frontier models on cost and latency. `[Open weights]` `MIT`
- [RobBERT](https://huggingface.co/pdelobelle/robbert-v2-dutch-base) — Dutch RoBERTa model trained on the OSCAR Dutch corpus, and one of the enduring defaults for serious Dutch-language NLP work. `[Open weights]` `MIT`
- [KB-BERT](https://huggingface.co/KB/bert-base-swedish-cased) — Swedish BERT model pre-trained by the National Library of Sweden, valuable because it pairs language quality with institutional stewardship. `[Open weights]` `CC-BY-4.0`
- [LeoLM](https://huggingface.co/LeoLM) — German-optimised LLMs fine-tuned from Llama 2 and Mistral by Hessian AI and LAION, giving the German-speaking ecosystem an openly available instruct-tuned family with strong local relevance. `[Open weights]` `Apache 2.0`
- [Danish BERT](https://huggingface.co/Maltehb/danish-bert-botxo) — Danish BERT model trained on the Danish Gigaword corpus, useful as a reliable baseline for Danish classification, search, and language understanding. `[Open weights]` `CC-BY-4.0`
- [ScandiBERT](https://huggingface.co/vesteinn/ScandiBERT) — North Germanic language model covering Danish, Norwegian, Swedish, Icelandic, and Faroese, helping smaller Nordic-language projects share one capable multilingual base. `[Open weights]` `AGPL-3.0`
- [GPT-SW3](https://huggingface.co/AI-Sweden-Models/gpt-sw3-20b-instruct) — Large-scale generative LLM for Nordic languages developed by AI Sweden, representing one of the clearest Nordic efforts to build regionally grounded generative models. `[Open weights]` `Apache 2.0`
- [Poro](https://huggingface.co/LumiOpen/Poro-34B) — Multilingual LLM for Finnish and English developed through the LumiOpen collaboration, notable because it ties regional model development directly to European supercomputing capacity. `[Open weights]` `Apache 2.0`
- [NorLM / NORA.LLM](https://huggingface.co/norallm) — Community collection of Norwegian language models coordinated by the University of Oslo ecosystem, giving builders a living hub rather than a single isolated checkpoint. `[Open weights]`

### Romance (FR, ES, IT, PT, RO, CA)

- [CamemBERT](https://huggingface.co/camembert-base) — French language model based on RoBERTa, trained on French subcorpus of OSCAR and still one of the most recognizable open baselines in French NLP. `[Open weights]` `MIT`
- [FlauBERT](https://huggingface.co/flaubert/flaubert_base_cased) — French BERT model trained on a diverse French corpus, useful when builders want a French-native encoder with long-standing academic adoption. `[Open weights]` `MIT`
- [Projecte AINA (Catalan Models)](https://huggingface.co/projecte-aina) — Catalan model collection from the Barcelona Supercomputing Center and Projecte AINA ecosystem, showing how a regional language strategy can become a full AI stack rather than a token translation effort. `[Open weights]`
- [MarIA](https://huggingface.co/PlanTL-GOB-ES/roberta-base-bne) — Massive Spanish language model from Spain's National Library and PlanTL, and a flagship example of institution-backed Spanish language infrastructure. `[Open weights]` `Apache 2.0`
- [CroissantLLM](https://huggingface.co/croissantllm) — French-English LLM from a European research team, with balanced pretraining and open weights designed to keep francophone usage visible in frontier-style model work. `[Open weights]`
- [UmBERTo](https://huggingface.co/Musixmatch/umberto-commoncrawl-cased-v1) — Italian RoBERTa-based model from Musixmatch in Italy, trained on a large-scale web corpus and widely referenced for Italian-language benchmarks. `[Open weights]` `Apache 2.0`
- [Romanian BERT](https://huggingface.co/dumitrescustefan/bert-base-romanian-cased-v1) — Romanian BERT model pre-trained on a large Romanian corpus, giving an important local baseline in a language often overlooked by broader multilingual models. `[Open weights]` `MIT`
- [TowerLLM](https://huggingface.co/Unbabel/TowerBase-7B-v0.1) — Translation-specialized LLM for Portuguese, English, German, French, and more, reflecting Unbabel's long-standing focus on multilingual production systems rather than pure demo models. `[Open weights]` `CC-BY-NC-4.0`

### Slavic (PL, CS, SK, SL, HR, BG)

- [Polish RoBERTa](https://huggingface.co/sdadas/polish-roberta-base-v2) — RoBERTa model trained on a large Polish corpus, offering a dependable baseline for one of Europe's biggest underrepresented language markets. `[Open weights]`
- [Bielik](https://huggingface.co/speakleash/Bielik-11B-v3.0-Instruct) — Polish-centered multilingual LLM from SpeakLeash, trained on large-scale European corpora and increasingly important as a regional open alternative for Central Europe. `[Open weights]` `Apache 2.0`
- [RobeCzech](https://huggingface.co/ufal/robeczech-base) — Monolingual Czech RoBERTa model developed by Charles University, widely useful for Czech NLP where general multilingual encoders often underperform. `[Open weights]` `CC-BY-NC-SA-4.0`
- [SlovakBERT](https://huggingface.co/gerulata/slovakbert) — Specialized RoBERTa-based model for the Slovak language, valuable because Slovak still sees far less model attention than larger European languages. `[Open weights]` `Apache 2.0`
- [SloBERTa](https://huggingface.co/EMBEDDIA/sloberta) — Slovenian language model trained by the EMBEDDIA project, giving a compact but important foundation for Slovenian NLP tasks. `[Open weights]` `MIT`
- [BERTic](https://huggingface.co/classla/bcms-bertic) — Transformer language model for Bosnian, Croatian, Montenegrin, and Serbian, especially useful because it addresses a linguistically connected region often underserved by mainstream AI tooling. `[Open weights]` `Apache 2.0`

### Uralic & Baltic (FI, ET, HU, LV, LT)

- [FinBERT](https://huggingface.co/TurkuNLP/bert-base-finnish-cased-v1) — Finnish BERT model from the TurkuNLP group, one of the most established starting points for high-quality Finnish-language NLP. `[Open weights]` `Apache 2.0`
- [EstBERT](https://huggingface.co/tartuNLP/EstBERT) — Monolingual BERT model for Estonian by University of Tartu researchers, giving Estonia a strong local-language base model rather than full dependence on broad multilingual checkpoints. `[Open weights]` `Apache 2.0`
- [Latvian BERT](https://huggingface.co/AiLab-IMCS-UL/lvbert) — BERT base model pre-trained on Latvian corpora from the University of Latvia ecosystem, important for keeping Baltic NLP accessible to smaller research and product teams. `[Open weights]` `Apache 2.0`
- [Lithuanian BERT](https://huggingface.co/HPLT/hplt_bert_base_lt) — Monolingual Lithuanian BERT released through the High Performance Language Technologies project, highlighting how European public language initiatives help smaller-language model quality catch up. `[Open weights]` `Apache 2.0`

### Smaller & Minority Languages

- [IceBERT](https://huggingface.co/mideind/icebert) — RoBERTa-based language model for Icelandic, developed by Miðeind as part of keeping a smaller national language visible in modern NLP tooling. `[Open weights]` `Apache 2.0`
- [LuxemBERT](https://huggingface.co/lothritz/LuxemBERT) — Monolingual BERT model for Luxembourgish, notable because even modest open checkpoints can make a major difference for smaller-language ecosystems. `[Open weights]`
- [BERTu](https://huggingface.co/MLRS/BERTu) — Monolingual BERT model trained on Korpus Malti for Maltese NLP tasks, giving Maltese-language work a real local baseline rather than a multilingual compromise. `[Open weights]` `CC-BY-NC-SA-4.0`
- [Faroese BERT](https://huggingface.co/egilron/faroese-roberta-base) — RoBERTa-based model trained on Faroese language data, representing the kind of targeted effort needed for Europe's smallest language communities. `[Open weights]` `MIT`
- [Techiaith Welsh Models](https://huggingface.co/techiaith) — Active collection of Welsh language models from Bangor University's Language Technologies Unit, useful for showing what sustained minority-language model stewardship looks like in practice. `[Open weights]`

### Hellenic & Other

- [Greek BERT](https://huggingface.co/nlpaueb/bert-base-greek-uncased-v1) — BERT model specifically for Modern Greek by AUEB NLP Group, and a dependable foundation for Greek-language understanding tasks. `[Open weights]` `Apache 2.0`
- [CeltBERT](https://huggingface.co/Geotrend/bert-base-celtic-langs) — BERT models for Celtic languages including Breton, Irish, Welsh, Manx, and Scottish Gaelic, helping smaller language communities stay represented in modern transformer tooling. `[Open weights]` `MIT` / `Apache 2.0`
- [Basque BERT](https://huggingface.co/ixa-ehu/berteus-base-cased) — High-quality transformer model for the Basque language (Euskara), often cited as a strong example of serious work for a non-state European language. `[Open weights]` `Apache 2.0`
- [HiTZ Basque MT Models](https://huggingface.co/HiTZ/mt-hitz-eu-es) — Open machine translation models for Basque developed by the HiTZ Center and IXA, giving the Basque ecosystem real translation infrastructure rather than symbolic support. `[Open weights]` `Apache 2.0`

### Multimodal & Domain-Specific

- [FLUX (Black Forest Labs)](https://bfl.ai/) — Open-weight frontier image-generation model family from Germany, setting a new bar for open visual generation and proving Europe can still lead in generative media research. `[Open weights]`
- [Moshi (Kyutai)](https://kyutai.org/blog/2024-07-03-meet-moshi) — Real-time speech-text foundation model from Kyutai, showing that high-end voice assistant research can be published openly rather than hidden behind closed consumer products. `[Open weights]`
- [Bioptimus (H-optimus)](https://huggingface.co/bioptimus/H-optimus-0) — Open-source foundation model for pathology trained on millions of images by a French AI lab, making a strong case that biology and medicine deserve their own frontier-grade model efforts. `[Open weights]` `Apache 2.0`

### Multilingual / Cross-lingual

- [Helsinki-NLP / OPUS-MT](https://huggingface.co/Helsinki-NLP) — University of Helsinki collection of open neural machine translation models for European language pairs, and one of the most practical bridges between academic MT and real multilingual product work. `[Open weights]` `Apache 2.0`
- [EuroLLM](https://huggingface.co/utter-project) — European multilingual LLM initiative for EU languages as part of the UTTER project, reflecting the wider push to keep European language coverage central in foundation-model development. `[Open weights]`
- [EuroBERT](https://huggingface.co/EuroBERT) — Pan-European multilingual encoder for 15 European languages, aimed at giving Europe a strong open encoder layer for retrieval, classification, and downstream NLP systems. `[Open weights]` `Apache 2.0`
- [OpenEuroLLM](https://openeurollm.eu/) — EU-funded pan-European family of open language models for all official EU languages, notable as a coordinated public-interest alternative to English-centric model roadmaps. `[Open weights]`
- [Occiglot](https://occiglot.eu/) — Pan-European initiative building open foundation models for all 24 official EU languages, explicitly pushing back on the idea that the future of AI should be English-centric by default. `[Open weights]` `Apache 2.0`

## AI Companies & Products

Flagship European AI companies and products shaping the builder ecosystem.

- [ElevenLabs](https://elevenlabs.io/about) — London-based AI audio company building voice models, developer APIs, and ElevenAgents for conversational voice and chat agents, and arguably the most visible European player in AI voice. `[Proprietary]`
- [Synthesia](https://www.synthesia.io/about) — UK AI video platform for enterprise training and communication, showing how Europe has produced one of the category-defining companies in AI-generated media. `[Proprietary]`
- [Stability AI](https://stability.ai/) — UK generative AI company behind the Stable Diffusion ecosystem and open model releases across image, video, audio, and language, with outsized influence on the open model movement. `[Open weights]`
- [H Company](https://www.hcompany.ai/) — French startup focusing on action models and software-executing systems rather than pure chat interfaces, making it one of Europe's most visible bets on autonomous multi-step reasoning. `[Proprietary]`

## Deep Tech AI & Frontier Applications

Resources for European AI companies working on autonomy, robotics, chips, scientific AI, and other hard-tech applications where AI is tightly coupled to hardware, industry, or frontier science.

- [Graphcore](https://www.graphcore.ai/) — UK chip company behind the IPU architecture, long viewed as Europe's strongest attempt to build AI-first compute hardware rather than relying entirely on US GPU ecosystems. `[Proprietary]`
- [Prophesee](https://www.prophesee.ai/) — French deep-tech company building neuromorphic vision sensors and event-based AI systems inspired by human vision, with strong relevance for robotics, mobility, and high-speed industrial perception. `[Proprietary]`
- [Helsing](https://helsing.ai/company) — European defence AI company building AI-enabled autonomous systems and software for democratic governments, and one of the clearest examples of strategic European AI sovereignty in practice. `[Proprietary]`
- [Wayve](https://wayve.ai/company/) — London-headquartered embodied AI company building autonomous driving systems and world-model-style vehicle intelligence, pushing Europe into the frontier conversation on real-world autonomous agents. `[Proprietary]`
- [ANYbotics](https://www.anybotics.com/) — Swiss robotics company building autonomous legged robots for industrial inspection, showing how European AI is extending from models and software into real-world autonomy in harsh operating environments. `[Proprietary]`
- [RobCo](https://www.robco.de/en/product-services/robot-as-a-service) — German automation company combining modular robots, AI-powered vision, and no-code orchestration to make factory robotics more software-defined and deployable for SMEs. `[Proprietary]`
- [Agile Robots](https://www.agile-robots.com/) — Munich-based robotics company developing AI-driven automation systems for manufacturing, electronics, healthcare, and service robotics, with a strong physical-AI positioning. `[Proprietary]`
- [BenevolentAI](https://www.benevolent.com/) — London-headquartered AI drug discovery company using proprietary AI and in-house scientific expertise to identify novel biology and accelerate therapeutic development. `[Proprietary]`
- [Causaly](https://www.causaly.com/) — London-based scientific AI platform for life sciences R&D, combining evidence retrieval, domain-specific agents, and structured biomedical reasoning to speed research decisions. `[Proprietary]`

## Multilingual Resources

Resources for non-English European languages. Dedicated model releases now live in the [Models](#models) section.

### Language Technology Projects

- [HPLT (High Performance Language Technologies)](https://hplt-project.org/) — Major EU-funded initiative providing multilingual datasets and model resources across 75+ languages, showing what Europe-scale language infrastructure looks like beyond a handful of big markets. `[EU-funded]`
- [Swiss-AL Corpus](https://www.zhaw.ch/en/linguistics/research/swiss-al/) — Large multilingual corpus covering Switzerland's national languages: German, French, Italian, and Romansh, and a good example of high-quality resources for a genuinely multilingual national context. `[Academic]`

## Research Labs & Institutes

EU-based AI research labs and institutes.

- [SDSC (Swiss Data Science Center)](https://datascience.ch/) — Switzerland. Joint ETH Zurich–EPFL initiative accelerating data science and AI adoption across research and industry, and a key bridge between top-tier Swiss academia and applied deployment. `[Academic]`
- [INRIA](https://www.inria.fr/en) — France. National research institute for digital science and technology, with major AI research teams and deep influence across European open research infrastructure. `[Academic]`
- [DFKI](https://www.dfki.de/en/web) — Germany. German Research Center for Artificial Intelligence, one of the world's largest AI research centers and a foundational institution in the European AI story. `[Academic]`
- [CWI](https://www.cwi.nl/) — Netherlands. National research institute for mathematics and computer science, with an ML research group and long-standing influence in European computing research. `[Academic]`
- [Alan Turing Institute](https://www.turing.ac.uk/) — United Kingdom. National institute for data science and AI, named after Alan Turing and central to the UK's academic AI ecosystem. `[Academic]`
- [Max Planck Institute for Intelligent Systems](https://is.mpg.de/) — Germany. Leading research on perception, learning, and intelligent systems, with global visibility across robotics, vision, and machine learning. `[Academic]`
- [ELLIS Institutes](https://ellis.eu/) — Pan-European. Network of AI research labs across Europe focused on machine learning excellence, helping Europe compete on talent and frontier research coherence. `[Academic]`
- [CLAIRE](https://claire-ai.org/) — Pan-European. Confederation of Laboratories for AI Research in Europe, connecting 400+ labs and acting as a meta-layer for European AI coordination. `[Academic]`
- [LAION](https://laion.ai/) — Germany. Non-profit providing open-source large-scale datasets and models for AI research, and a major backbone of the open generative media movement that helped power Stable Diffusion. `[Open-source]` `[Academic]`
- [Barcelona Supercomputing Center (BSC)](https://www.bsc.es/) — Spain. Operates MareNostrum 5 pre-exascale supercomputer and hosts one of the EU's seven official AI factories, making it one of Europe's most important AI infrastructure institutions. `[Academic]`
- [Fraunhofer IAIS](https://www.iais.fraunhofer.de/en.html) — Germany. Applied AI research institute near Bonn specialising in ML, NLP, and generative AI for industry, with strong industry-transfer relevance beyond pure academic publishing. `[Academic]`
- [Idiap Research Institute](https://www.idiap.ch/en) — Switzerland. Independent EPFL-affiliated institute researching speech, NLP, computer vision, and machine learning, and especially respected in multimodal and voice research. `[Academic]`
- [ETH AI Center](https://ai.ethz.ch/) — Switzerland. Central hub for AI research at ETH Zurich, with a strong focus on trustworthy AI systems and one of the clearest concentrations of Swiss AI talent. `[Academic]`
- [Jožef Stefan Institute (AI Lab)](http://ailab.ijs.si/) — Slovenia. Leading AI and ML research lab covering knowledge technologies, data mining, and language resources, and a major anchor for the Slovenian ecosystem. `[Academic]`
- [ZHAW Centre for Artificial Intelligence](https://www.zhaw.ch/en/engineering/institutes-centres/cai/) — Switzerland. Applied AI research center at ZHAW focused on trustworthy AI, vision, NLP, and industry transfer, giving Switzerland another strong applied counterpart to ETH and EPFL. `[Academic]`
- [INSAIT](https://insait.ai/) — Bulgaria. Flagship AI research institute for South-East Europe, notable for raising the regional ceiling on frontier-level AI research and talent attraction. `[Academic]`
- [Kyutai](https://kyutai.org/) — France. Non-profit open-science AI lab publishing open models including the Moshi real-time voice assistant, proving that high-end frontier research can still be done transparently. `[Academic]` `[Open-source]`
- [CYENS Centre of Excellence](https://www.cyens.org.cy/) — Cyprus. EU-funded research center for interactive media, smart systems, and AI applications, helping a smaller ecosystem build durable applied capacity. `[Academic]`
- [GATE Institute](https://gate-ai.eu/en/) — Bulgaria. Big Data for a Smart Society institute focusing on AI and data science, with an emphasis on public-interest and infrastructure-scale applications. `[Academic]`
- [LERO (The Irish Software Research Centre)](https://lero.ie/) — Ireland. National software research center with significant AI safety and ethics work, giving Ireland a meaningful role in responsible AI research conversations. `[Academic]`
- [AI Czechia](https://www.aiczechia.cz/) — Czechia. Open initiative connecting Czech AI research institutions and national capabilities, useful as a coordination layer as much as a single lab. `[Academic]`
- [University of Tartu (NLP Group)](https://nlp.cs.ut.ee/) — Estonia. Leading research group for Estonian NLP and multilingual language models, and one of the most visible language-tech centers in the Baltics. `[Academic]`
- [ETF Belgrade (University of Belgrade)](https://www.etf.bg.ac.rs/) — Serbia. Leading engineering faculty with established AI, machine learning, and NLP research programs, anchoring a strong technical tradition in the Serbian ecosystem. `[Academic]`
- [Kaunas University of Technology (KTU)](https://en.ktu.edu/) — Lithuania. Major technical university with focused AI and machine learning research in its Computer Science faculty, contributing to Lithuania's growing AI profile. `[Academic]`
- [FEIT Skopje (Ss. Cyril and Methodius University)](https://feit.ukim.edu.mk/en/) — North Macedonia. Leading engineering faculty with AI, signal processing, and robotics-related research, serving as a core academic node for the country's AI work. `[Academic]`
- [University of Montenegro — Faculty of Electrical Engineering](https://www.ucg.ac.me/) — Montenegro. Primary engineering university in Montenegro with emerging AI and signal processing work, included to reflect the broader European research map rather than only the largest hubs. `[Academic]`
- [INESC ID](https://www.inesc-id.pt/) — Portugal. Research institute at IST/ULisboa with strong AI, NLP, and machine learning groups, and an important driver of Portuguese-language AI research. `[Academic]`
- [INESC TEC](https://www.inesctec.pt/) — Portugal. Large applied research institute in Porto with AI, robotics, and data science groups, blending academic depth with industrial collaboration. `[Academic]`
- [Austrian Institute of Technology (AIT)](https://www.ait.ac.at/) — Austria. Austria's largest research institute, with AI safety, digital systems, and responsible AI focus, giving Austria a strong applied-research pillar. `[Academic]`
- [TU Wien — Informatics](https://www.tuwien.at/en/) — Austria. Austria's leading technical university with AI, knowledge representation, and computer vision research, and a long-standing reputation in symbolic and visual AI. `[Academic]`
- [Eötvös Loránd University (ELTE)](https://www.elte.hu/en) — Hungary. Budapest's flagship university with strong CS and AI research groups in NLP and machine learning, representing one of Hungary's most visible academic AI anchors. `[Academic]`

## Communities & Events

Communities, forums, and events for EU AI builders.

### Online Communities

- [LAION Discord](https://discord.gg/laion) — Active community around open-source datasets and AI research, with a strong European contributor base and unusually direct ties to the open generative media ecosystem.

### Conferences (EU-based)

- [ECML-PKDD](https://ecmlpkdd.org/) — European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases, one of the continent's long-running anchor conferences for serious ML research.
- [AI4EU Summit](https://www.ai4europe.eu/) — Annual conference of the EU-funded AI-on-Demand Platform bringing together European AI stakeholders across research, industry, and policy.

### Newsletters & Media

- [Yannic Kilcher](https://www.youtube.com/@YannicKilcher) — Swiss-based AI researcher producing in-depth ML paper reviews and discussions, and one of the most recognizable European voices in open technical AI commentary.

### National Associations

- [Swiss AI Association](https://swissai.ch/) — Switzerland's primary AI ecosystem body connecting researchers, businesses, and policy makers, and a useful barometer for Swiss ecosystem maturity.
- [Swiss NLP](https://swissnlp.org/) — Association connecting NLP researchers and practitioners across Switzerland, especially important in a country where multilingual language tech has outsized relevance.
- [AI Estonia (AIRE)](https://aire-edih.eu/en/) — Estonian Digital Innovation Hub for AI, supporting SMEs and industry adoption and helping convert Estonia's digital-government strengths into applied AI capacity.
- [Serbian AI Society](https://serbianaisociety.org/) — Professional AI society in Serbia promoting research, collaboration, and ecosystem building, giving local practitioners a stronger national coordination point.
- [Croatian AI Association](https://croai.org/) — Croatian AI community connecting researchers and industry, helping a smaller national market build continuity instead of one-off initiatives.
- [APPIA](https://www.appia.pt/) — Portuguese Association for Artificial Intelligence, connecting researchers and practitioners across Portugal and sustaining a long-running national AI network.
- [Lithuanian AI Association](https://lithuania.ai/en/about) — National AI association connecting Lithuania's AI ecosystem across research, business, and policy, reflecting the Baltics' increasingly organized AI posture.
- [Malta AI Association](https://malta-ai.org/) — AI community in Malta, included because smaller ecosystems still benefit from visible coordination and community infrastructure.
- [Cyprus AI Initiative](https://cyprusai.org/) — AI community in Cyprus, helping local builders, startups, and researchers find a shared ecosystem layer.
- [Slovakia.ai](https://slovakia.ai/en/) — Association for the development and application of artificial intelligence in Slovakia, useful as a national entry point for a fast-evolving ecosystem.
- [Hellenic AI Society (EETN)](https://www.eetn.gr/) — Greek professional association for researchers and practitioners in AI, linking academic depth with the broader Greek technology community.
- [AI Poland](https://aipoland.org/) — Foundation promoting the Polish AI ecosystem through collaboration and policy, and important given Poland's growing weight in European AI.
- [AI4Belgium](https://www.ai4belgium.be/) — National community and ecosystem builder for AI adoption in Belgium, useful for connecting public-sector, academic, and enterprise actors.
- [AI Ireland](https://aiireland.ie/) — Irish community hub promoting AI development through awards, networking, and education, with strong visibility in the local business ecosystem.
- [AppliedAI Initiative](https://www.appliedai.de/en/) — Germany's leading initiative for applied AI and ecosystem building, especially relevant for translating German enterprise interest into deployable AI projects.
- [Austrian AI Association (AAIA)](https://www.ai-austria.com/) — Non-profit connecting the Austrian AI ecosystem, giving founders, researchers, and practitioners a shared national coordination layer.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding resources.

## Scope & Disclaimer

This list curates resources for building AI systems in Europe. It is **not** a compliance checker, legal advisor, or endorsement of any product. References to the EU AI Act, GDPR, or other regulations are pointers to tools that help with those topics — they do not constitute legal advice. Always verify current enforcement schedules and consult qualified professionals before acting on regulatory information.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
