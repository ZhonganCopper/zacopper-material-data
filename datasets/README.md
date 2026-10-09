# Datasets

Datasets are the machine-readable counterpart to published technical documents. Use CSV for tabular data and JSON for structured records; include a companion metadata file when metadata is not embedded.

Each dataset must state:

- product and grade, where applicable;
- source type: instrument export, laboratory report, calculation, digitized chart, or representative example;
- sample identity or an anonymized sample description;
- test date, testing unit, instrument, method, and units where available;
- revision, publication date, and known limitations.

Do not publish values with unknown units or provenance. Use [`templates/dataset-metadata.json`](../templates/dataset-metadata.json) and validate against [`schemas/dataset-metadata.schema.json`](../schemas/dataset-metadata.schema.json).
