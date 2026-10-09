# ZA Copper Material Data

Public technical-reference library for copper materials supplied by **Guixi Zhongan Copper Co., Ltd.**

**Official website: [www.zacopper.com](https://www.zacopper.com/)**<br>
For product enquiries, quotations, samples, and the current commercial specification, visit **[www.zacopper.com](https://www.zacopper.com/)**.

This repository publishes selected technical documents and machine-readable material data to make product information easier to inspect, cite, and reuse. It is **not** the website source code, a sales contract, or a substitute for a product-specific certificate of analysis (COA), safety data sheet (SDS), or written quotation.

[中文说明](README.zh-CN.md)

## Contents

| Area | What it contains | Status |
| --- | --- | --- |
| [`products/`](products/) | Product-specific data, COA samples, SDS files, test reports, and application notes | Structure ready |
| [`datasets/`](datasets/) | Machine-readable CSV/JSON data released with provenance and versioning | Structure ready |
| [`methods/`](methods/) | Test methods, sampling context, terms, and metric definitions | Structure ready |
| [`schemas/`](schemas/) | Reusable JSON schemas for data and document metadata | Structure ready |
| [`templates/`](templates/) | Required templates for new products, datasets, and documents | Ready to use |
| [`governance/`](governance/) | Publication, correction, and versioning policy | Ready to use |

## Product index

The following sections are prepared for publication. A product directory is not a claim that every grade, specification, or document is currently available.

| Product family | Repository location | Official product information |
| --- | --- | --- |
| Electronic-grade copper oxide powder | [`products/copper-oxide-powder/`](products/copper-oxide-powder/) | [zacopper.com](https://www.zacopper.com/) |
| Phosphorized copper anodes / balls | [`products/phosphorized-copper-anodes/`](products/phosphorized-copper-anodes/) | [zacopper.com](https://www.zacopper.com/) |
| Oxygen-free copper rod | [`products/oxygen-free-copper-rod/`](products/oxygen-free-copper-rod/) | [zacopper.com](https://www.zacopper.com/) |
| Copper anode plate | [`products/copper-anode-plate/`](products/copper-anode-plate/) | [zacopper.com](https://www.zacopper.com/) |

## How to use this repository

1. Start with the relevant product directory and read its `README.md`.
2. Check each file's `source`, `sample`, `test method`, `revision`, and `publishedAt` fields before using a value.
3. Use the linked COA/SDS or request current, lot-specific documentation through [www.zacopper.com](https://www.zacopper.com/) when making a purchasing, safety, process, or compliance decision.
4. Cite the exact file and commit/tag you used. Do not cite a directory as if it were a test result.

## Data principles

- **Traceable:** Each published dataset or document must identify its source type, product, unit, method where applicable, and release date.
- **Qualified:** Example, representative, digitized, calculated, and lot-specific data are labelled as such; they are not interchangeable.
- **Versioned:** Corrections and material changes are recorded in [`CHANGELOG.md`](CHANGELOG.md).
- **Safe to interpret:** SDS and product-safety information must be used in their complete, current form. A data point in this repository is not safety advice.

See [`governance/data-policy.md`](governance/data-policy.md) for the full policy.

## Important limitations

Values may vary by grade, production lot, test method, sample preparation, and measurement conditions. Unless a file explicitly says otherwise, information here is for technical reference only and does not establish a contractual product specification, warranty, or regulatory determination.

For the current authoritative commercial and contact information, use **[www.zacopper.com](https://www.zacopper.com/)**.

## Contributing and corrections

This is a maintained publisher repository. Please open an issue or contact us through [www.zacopper.com](https://www.zacopper.com/) to report an error, request clarification, or propose a public technical resource. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Reuse and licensing

No reuse licence has been selected yet. Do not assume that repository contents may be redistributed, modified, or used commercially. A licence will be added before third-party reuse is invited.
