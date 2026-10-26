# Awesome-Document-Generation-Conversion-API

## Top Document Generation & Conversion API Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on PDF Generation, Office Conversion & Programmatic Document Automation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Generation & Conversion APIs**. These tools enable developers to programmatically generate PDFs, convert between document formats (DOCX, ODT, PDF, Markdown, HTML), manipulate existing PDFs, and automate document workflows at scale.



**Examples** include Adobe PDF Services API, Apryse Cloud API, Foxit PDF SDK, PSPDFKit API, Docupilot, CloudConvert API, Zamzar API, iLovePDF API, PDFTron SDK, and ConvertAPI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted PDF generation engines, format conversion libraries, HTML-to-PDF services, and document manipulation toolkits — ideal for developers, SaaS builders, and enterprises building sovereign document pipelines without per-call API pricing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Adobe PDF Services API](https://developer.adobe.com/document-services/apis/pdf-services/)**  

  Cloud API for PDF creation, conversion (Office to PDF, PDF to Office), compression, OCR, and extraction, powered by Adobe's document engine.



- **[Apryse Cloud API](https://apryse.com/products/cloud-api)**  

  Cloud document processing API (formerly PDFTron) for PDF generation, conversion, editing, redaction, and digital signatures with high-fidelity rendering.



- **[Foxit PDF SDK](https://developers.foxit.com/)**  

  Developer SDK for embedding PDF viewing, editing, creation, and conversion capabilities into applications across web, mobile, and desktop platforms.



- **[PSPDFKit API](https://pspdfkit.com/api/)**  

  Cloud API for PDF generation, conversion, and manipulation, with support for HTML-to-PDF, Office-to-PDF, and document assembly workflows.



- **[Docupilot](https://www.docupilot.app/)**  

  Document automation platform with template-based PDF and DOCX generation, data merging, and API/webhook triggers for business documents.



- **[CloudConvert API](https://cloudconvert.com/api/v2)**  

  File conversion API supporting 200+ formats across documents, images, audio, video, and archives, with job orchestration and webhook support.



- **[Zamzar API](https://developers.zamzar.com/)**  

  File conversion API with support for over 1,100 format conversions, including document, image, audio, and video processing.



- **[iLovePDF API](https://developer.ilovepdf.com/)**  

  REST API for PDF processing tasks including merge, split, compress, convert (Office/PDF), watermark, and OCR.



- **[PDFTron SDK](https://www.pdftron.com/)**  

  Comprehensive PDF SDK (now under Apryse) for viewing, editing, annotating, converting, and generating PDFs across platforms.



- **[ConvertAPI](https://www.convertapi.com/)**  

  File conversion API with a wide range of document, spreadsheet, presentation, and image format conversions, plus PDF manipulation.



## Open-Source GitHub Projects



- **[AavanamKit](https://github.com/jafranjemal/aavanamkit)**  

  Full-stack open-source document generation ecosystem with a visual drag-and-drop React designer and a headless Node.js engine; generates high-quality vector PDFs and DOCX from JSON templates with auto-paginating tables, barcodes, and conditional rendering .



- **[FossPDF](https://github.com/FossPDF/FossPDF.Net)**  

  MIT-licensed .NET library for PDF generation (fork of QuestPDF's last FOSS commit); code-only approach with a comprehensive layout engine, fluent C# API, and hot-reload preview for designing PDFs with version control .



- **[pdfme](https://github.com/pdfme/pdfme)**  

  TypeScript-based PDF generation library with a React WYSIWYG template designer; works in browser and Node.js, uses simple JSON templates, and supports complex layouts, barcodes, and dynamic data binding under MIT license .



- **[CasualOffice Core](https://github.com/CasualOffice/core)**  

  Pure-Rust engine for reading, writing, and converting DOCX, ODT, PDF, Markdown, and plain text; ships as a WASM bundle (~3.3 MB gzipped) with JavaScript/TypeScript bindings and C FFI, preserving styles, tables, images, and tracked changes across round-trips .



- **[Docling](https://github.com/DS4SD/docling)**  

  MIT-licensed toolkit from IBM for converting PDF, DOCX, PPTX, images, HTML, and more into structured JSON/Markdown; features advanced layout analysis, table understanding, OCR integration, and native LangChain/LlamaIndex support for AI pipelines .



- **[PdfTurtle](https://github.com/lucas-gaitzsch/pdf-turtle)**  

  Free, self-hosted HTML-to-PDF rendering service using headless Chromium; supports modern HTML/CSS/JS, built-in template engines (Go, Django), ZIP bundle workflows for assets, and Docker deployment for stateless scaling .



- **[html2pdf](https://github.com/openwhale-labs/html2pdf)**  

  Python tool that converts HTML to a single continuous PDF page (as tall as the content) via headless Chromium, preserving selectable text, clickable links, and embedded fonts; ideal for web-page-style reports and receipts .



- **[gpdf](https://github.com/gpdf-dev/gpdf)**  

  Go library for building PDFs from JSON schemas or Go templates, with built-in invoice/report/letter constructors, digital signature support, AES-256 encryption, PDF/A conformance, and page merging capabilities .



- **[OfficeIMO](https://github.com/EvotecIT/OfficeIMO)**  

  MIT-licensed, COM-free .NET libraries for creating, reading, editing, converting, and extracting Office formats (DOCX, XLSX, PPTX), PDF, email, OneNote, and text; positioned as an Aspose alternative for .NET document automation .



- **[BentoPDF](https://github.com/alam00000/bentopdf)**  

  Client-side PDF toolbox that bundles PDFLib.js, PDFKit, PDF.js, and LibreOffice WASM for PDF editing, Office↔PDF conversion, and manipulation entirely in the browser without server uploads .



### Additional Strong Open-Source Options



- **xhtml2pdf** — Python library for converting HTML to PDF using ReportLab, suitable for server-side report generation.

- **Gotenberg** — Dockerized API for HTML-to-PDF, Office-to-PDF, and PDF manipulation via Chromium and LibreOffice, with client libraries in multiple languages.

- **WeasyPrint** — Python library for HTML/CSS to PDF rendering with strong print CSS support.

- **pdf-lib** — JavaScript library for creating and modifying PDFs in browser and Node.js.

- **PyMuPDF** — High-performance Python library for PDF manipulation, text extraction, and rendering.

- **pypdf** — Pure-Python PDF library for merging, splitting, cropping, and metadata editing.

- **LibreOffice Headless** — Command-line conversion engine for Office formats to PDF and other formats.



**Frameworks for building custom systems**: Combine **PdfTurtle** or **Gotenberg** for HTML-to-PDF rendering, **AavanamKit** or **pdfme** for visual template design and generation, **CasualOffice Core** for Office format round-tripping, **Docling** for AI-ready document extraction, and **FossPDF** or **gpdf** for code-driven PDF construction in a fully self-hosted document pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Document processing must comply with applicable regulations and licensing terms for any bundled or referenced third-party engines.

- Self-hosted open-source solutions require proper security hardening, resource planning (especially for headless browser rendering), and output quality validation.

- Verify license terms for commercial use; some projects use AGPL or GPL licenses that may require releasing derivative code if distributed.



---



**Made for developers, SaaS builders, document engineers, and automation teams.**  

Let's make document generation and conversion more open, programmable, and accessible.
