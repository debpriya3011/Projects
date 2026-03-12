<div align="center">

<br/>

```
 ██████╗ █████╗ ██████╗ ███████╗██╗   ██╗██╗     ███████╗
██╔════╝██╔══██╗██╔══██╗██╔════╝██║   ██║██║     ██╔════╝
██║     ███████║██████╔╝███████╗██║   ██║██║     █████╗  
██║     ██╔══██║██╔═══╝ ╚════██║██║   ██║██║     ██╔══╝  
╚██████╗██║  ██║██║     ███████║╚██████╔╝███████╗███████╗
 ╚═════╝╚═╝  ╚═╝╚═╝     ╚══════╝ ╚═════╝ ╚══════╝╚══════╝
                              L A B S
```

**Automation · Scraping · Intelligence · Delivery**



<br/>

> *Client work is confidential — this repository showcases inputs, outputs, and visual results only.*

<br/>

---

</div>

<br/>

## 📁 Repository Structure

```
capsule-labs/
├── full_scraper_based/          # Web scraping solutions
│   ├── bsp/
│   ├── epicsports/
│   ├── kieran/
│   ├── kinchrome/
│   └── thereisanaiforeverything/
│
└── tool_based/                  # Custom automation tools
    ├── bess/
    ├── encuentra24/
    ├── euro/
    ├── franchesco/
    ├── fusselbaugh/
    ├── josh_music/
    ├── labels/
    ├── marketmap/
    ├── pascal/
    ├── paul_project/
    ├── pdf_manipulation/
    └── pdf_watermark/
```

<br/>

---

<br/>

# 🕷️ Full Scraper Based Projects

> End-to-end web scraping pipelines — data extraction, transformation, and structured output delivery.

<br/>

---

## `bsp` — Multi-Site Master Scraper

**A batch scraper that aggregates data across a list of target sites into a unified master database.**

Handles multiple source URLs, normalizes inconsistent data structures, and outputs a clean consolidated dataset. Designed for resilience and repeatability across scheduled runs.

**Highlights:** Multi-URL ingestion · Data normalization · Master DB output · Fault-tolerant pipeline

<br/>

---

## `epicsports` — Sports Data Scraper

**Full scraper for the EpicSports platform, extracting structured product and category data at scale.**

| Website |
|:-------:|
| ![epicsports website](./full_scraper_based/epicsports/screenshots/website.png) |

**Highlights:** Category traversal · Pagination handling · Structured product data output

<br/>

---

## `kieran` — School Data Scraper with Bot Detection Bypass

**Scrapes school-related data with robust anti-bot handling — including Cloudflare and CAPTCHA bypass layers.**

| During Bot Detection | After Bot Detection | Target Page Sample |
|:--------------------:|:-------------------:|:------------------:|
| ![during bot detection](./full_scraper_based/kieran/screenshots/during%20bot%20detection.png) | ![after bot detection](./full_scraper_based/kieran/screenshots/after%20bot%20detection.png) | ![required page sample](./full_scraper_based/kieran/screenshots/required%20page%20sample.png) |

**Highlights:** Bot detection bypass · Session persistence · Structured school data extraction

<br/>

---

## `kinchrome` — Kincrome Product Scraper

**Dedicated scraper for the Kincrome product catalog — tools, hardware, and accessories.**

| Website |
|:-------:|
| ![kincrome website](./full_scraper_based/kinchrome/screenshots/website.png) |

**Highlights:** Product catalog traversal · SKU extraction · Image URL capture · Clean CSV/JSON output

<br/>

---

## `thereisanaiforeverything` — AI Tools Aggregator

**Dual-source scraper pulling AI tool listings from `thereisanaiforthat.com` and `toolify.ai` into one unified database.**

| There Is An AI Website | Toolify Website |
|:----------------------:|:---------------:|
| ![thereisanai website](./full_scraper_based/thereisanaiforeverything/screenshots/thereisanai%20website.png) | ![toolify website](./full_scraper_based/thereisanaiforeverything/screenshots/toolify%20website.png) |

**Highlights:** Multi-source aggregation · Deduplication · Category tagging · AI tool metadata extraction

<br/>

---
---

<br/>

# 🛠️ Tool Based Projects

> Custom-built desktop and web tools — automation UIs, data processors, and intelligent pipelines delivered to clients.

<br/>

---

## `bess` — Shortlisting & Data Processing Tool

**A streamlined tool for filtering, shortlisting, and processing large datasets based on configurable criteria.**

| Tool Interface | Shortlist View | Working State |
|:--------------:|:--------------:|:-------------:|
| ![tool](./tool_based/bess/screenshots/tool.png) | ![shortlist](./tool_based/bess/screenshots/shortlist.png) | ![working](./tool_based/bess/screenshots/working.png) |

**Highlights:** Rule-based filtering · Shortlist generation · Real-time processing feedback

<br/>

---

## `encuentra24` — Encuentra24 Interaction Tool

**Automation tool for interacting with the Encuentra24 classifieds platform — browsing, filtering, and data extraction.**

| Website | Tool |
|:-------:|:----:|
| ![website](./tool_based/encuentra24/screenshots/website.png) | ![tool](./tool_based/encuentra24/screenshots/tool.png) |

**Highlights:** Listings interaction · Category-based filtering · Structured data export

<br/>

---

## `euro` — Data Processing Pipeline Tool

**A multi-stage data transformation tool handling ingestion, cleaning, and structured output across several processing steps.**

| Stage 1 | Stage 2 | Stage 3 | Source |
|:-------:|:-------:|:-------:|:------:|
| ![data process 1](./tool_based/euro/screenshots/data%20process%201.png) | ![data process 2](./tool_based/euro/screenshots/data%20process%202.png) | ![data process 3](./tool_based/euro/screenshots/data%20process%203.png) | ![website](./tool_based/euro/screenshots/website.png) |

**Highlights:** Multi-step pipeline · Data validation · Staged processing with visual feedback

<br/>

---

## `franchesco` — Vendor Search & Management Tool

**Full-featured vendor database tool with real-time search, shortlisting, and winner selection workflows.**

| Start Page | Config | Real-Time Search & DB |
|:----------:|:------:|:---------------------:|
| ![start page](./tool_based/franchesco/screenshots/start%20page.png) | ![config](./tool_based/franchesco/screenshots/config.png) | ![data search in real time and from db](./tool_based/franchesco/screenshots/data%20search%20in%20real%20time%20and%20from%20db.png) |

| Vendors in DB | Short List | Winner List |
|:-------------:|:----------:|:-----------:|
| ![vendors data in db](./tool_based/franchesco/screenshots/vendors%20data%20in%20db.png) | ![short list](./tool_based/franchesco/screenshots/short%20list.png) | ![winner list](./tool_based/franchesco/screenshots/winner%20list.png) |

**Highlights:** Real-time + DB hybrid search · Vendor shortlisting · Winner selection workflow · Full config system

<br/>

---

## `fusselbaugh` — PDF Data Extraction Tool

**Automated PDF extraction tool with multi-stage processing — from initial parse to structured final output.**

| Initial | Intermediate | Extraction | Tool |
|:-------:|:------------:|:----------:|:----:|
| ![initial](./tool_based/fusselbaugh/screenshots/initial.png) | ![intermediate](./tool_based/fusselbaugh/screenshots/intermediate.png) | ![extraction](./tool_based/fusselbaugh/screenshots/extraction.png) | ![tool](./tool_based/fusselbaugh/screenshots/tool.png) |

**Highlights:** PDF parsing · Staged extraction pipeline · Structured data output

<br/>

---

## `josh_music` — Music Analysis & Graph Visualization Tool

**An advanced music analysis platform with interactive graph visualization, parameter tuning, and result export.**

| Upload Page | Config |
|:-----------:|:------:|
| ![upload folder page](./tool_based/josh_music/screenshots/upload%20folder%20page.png) | ![config change](./tool_based/josh_music/screenshots/config%20change.png) |

| Graph Analysis | With Extra Parameters | With Changing Values | Results |
|:--------------:|:--------------------:|:--------------------:|:-------:|
| ![graph analysis](./tool_based/josh_music/screenshots/graph%20analysis.png) | ![graph analysis with extra parameters](./tool_based/josh_music/screenshots/graph%20analysis%20with%20extra%20parameters.png) | ![graph analysis with changing values](./tool_based/josh_music/screenshots/graph%20analysis%20with%20changing%20values.png) | ![results](./tool_based/josh_music/screenshots/results.png) |

**Highlights:** Audio file batch processing · Interactive graph output · Dynamic parameter control · Result export

<br/>

---

## `labels` — Label Processing & Verification Tool

**Automated label checking tool that runs validation processes and flags issues across label batches.**

| Tool | Process Run | Checking |
|:----:|:-----------:|:--------:|
| ![tool](./tool_based/labels/screenshots/tool.png) | ![process run](./tool_based/labels/screenshots/process%20run.png) | ![checking](./tool_based/labels/screenshots/checking.png) |

**Highlights:** Label validation · Batch processing · Pass/fail reporting · Visual verification

<br/>

---

## `marketmap` — Gemini-Powered Image Analysis Tool

**AI-powered market map tool using Google Gemini to analyze and extract structured data from images.**

| Initial Step | Before Gemini | Partial Analysis | After Gemini |
|:------------:|:-------------:|:----------------:|:------------:|
| ![initial step](./tool_based/marketmap/screenshots/initial%20step.png) | ![before gemini process](./tool_based/marketmap/screenshots/before%20gemini%20process.png) | ![partial gemini analysis step](./tool_based/marketmap/screenshots/partial%20gemini%20analysis%20step.png) | ![after gemini process](./tool_based/marketmap/screenshots/after%20gemini%20process.png) |

**Highlights:** Gemini Vision API integration · Image-to-data extraction · Step-by-step processing with progress visibility

<br/>

---

## `pascal` — Lumber Product Scraper & Analysis Tool

**Two-phase tool for scraping lumber product data and performing price/availability analysis with flagging.**

#### Initial Setup Phase

| Config | Master DB | New Results | Flagged Results | Analysis |
|:------:|:---------:|:-----------:|:---------------:|:--------:|
| ![config](./tool_based/pascal/screenshots/initial%20step/config.png) | ![masterdb](./tool_based/pascal/screenshots/initial%20step/masterdb.png) | ![new results](./tool_based/pascal/screenshots/initial%20step/new%20results.png) | ![flagged results](./tool_based/pascal/screenshots/initial%20step/flagged%20results.png) | ![analysis](./tool_based/pascal/screenshots/initial%20step/analysis.png) |

#### Working Phase

| Master DB | Search | Scrape Analysis |
|:---------:|:------:|:---------------:|
| ![masterdb](./tool_based/pascal/screenshots/working%20step/masterdb.png) | ![search](./tool_based/pascal/screenshots/working%20step/search.png) | ![single time scrape analysis](./tool_based/pascal/screenshots/working%20step/single%20time%20scrape%20analysis.png) |

**Highlights:** Two-phase workflow · Price flag detection · Master DB management · On-demand single scrape mode

<br/>

---

## `paul_project` — PDF Extraction with Manual Crop

**PDF data extraction tool supporting both automatic parsing and manual region-select cropping for precise data capture.**

#### Initial Extraction Phase

| Automatic Extraction | Manual Crop |
|:--------------------:|:-----------:|
| ![automatic extraction](./tool_based/paul_project/screenshots/initial%20step/automatic%20extraction.png) | ![manual crop](./tool_based/paul_project/screenshots/initial%20step/manual%20crop.png) |

#### Working Process

| After Loading PDF | Click on Image | Cropping Process | Manual Crop Result |
|:-----------------:|:--------------:|:----------------:|:------------------:|
| ![after loading pdf](./tool_based/paul_project/screenshots/working%20process/after%20loading%20pdf.png) | ![click on image](./tool_based/paul_project/screenshots/working%20process/click%20on%20image.png) | ![cropping process](./tool_based/paul_project/screenshots/working%20process/cropping%20process.png) | ![manual crop](./tool_based/paul_project/screenshots/working%20process/manual%20crop.png) |

**Highlights:** Auto + manual extraction modes · Interactive crop UI · Precise region selection · Structured output

<br/>

---

## `pdf_manipulation` — PDF Editor & Manipulator

**A comprehensive PDF manipulation tool supporting group editing, summary management, and page-level operations.**

| Tool | Groups Edit | Summaries Edit | Summaries Save | Overview |
|:----:|:-----------:|:--------------:|:--------------:|:--------:|
| ![tool](./tool_based/pdf_manipulation/screenshots/tool.png) | ![groups edit](./tool_based/pdf_manipulation/screenshots/groups%20edit.png) | ![summaries edit](./tool_based/pdf_manipulation/screenshots/summaries%20edit.png) | ![summaries save](./tool_based/pdf_manipulation/screenshots/summaries%20save.png) | ![overview](./tool_based/pdf_manipulation/screenshots/Screenshot%202026-03-12%20122449.png) |

**Highlights:** Group-based page management · Summary editing · Save/export workflows · Clean UI

<br/>

---

## `pdf_watermark` — PDF Watermarking Tool

**Fast, reliable tool for applying custom watermarks to PDF files with configurable placement and styling.**

| Process Step 1 | Process Step 2 |
|:--------------:|:--------------:|
| ![tool process 1](./tool_based/pdf_watermark/screenshots/tool%20process%201.png) | ![tool process 2](./tool_based/pdf_watermark/screenshots/tool%20process%202.png) |

**Highlights:** Custom watermark placement · Batch PDF support · Preview before export

<br/>

---

<div align="center">

<br/>

```
Built with precision. Delivered with results.
```



<br/>



</div>