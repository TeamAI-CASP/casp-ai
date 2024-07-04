## Configuration: handwritten

### General Information
- **Partition Key:** cas-todt
- **Row Key:** handwritten
- **Configuration Name:** handwritten
- **Dashboard ID:** ba1ddeba-50f4-2827-ed22-3566a4c0aa5d
- **Dashboard URL:** [Dashboard Link](https://your-kibana-instance/app/kibana#/dashboard/ba1ddeba-50f4-2827-ed22-3566a4c0aa5d)
- **Resource:** cas-todt
- **Template:** ''

### Keyword Configuration (kw_conf)
- **CL Model:** []
- **CL Quantize:** true
- **Diversity:** 0.7
- **Keypair Model:** Azure
- **Keyword Model:** 
  - `sentence-transformers/all-MiniLM-L6-v2`
- **KV Model:** []
- **KV Quantize:** true
- **KW Limit:** 30
- **Layout Model:** PaddleGPU
- **Ngrams:** 2
- **OB Model:** 
  - `facebook/detr-resnet-50`
- **OB Quantize:** true
- **OCR Selection:** 
  - Tesseract
  - Paddle
  - doctr
  - easyocr
  - AzureFormParser
  - GoogleDocumentAI
- **Quantize:** false
- **SP Model:** []
- **SP Quantize:** true
- **SP Sampling:** 16000
- **Table Selection:**
  - Paddle
  - Camelot
  - AzureFormParser
  - GoogleDocumentAI
  - EnsembleModel
- **Translator Selection:** []
- **Use MMR:** true
- **ZS Model:** []
- **ZS Quantize:** true

### Marqo Configuration (marqo_conf)
- **Image Model:** ViT-L/14
- **Normalize Image:** true

### Mount Configuration (mount_conf)
- **DB Name:** marqo_images
- **Document Types:** 
  - images
  - documents
- **Environment:** qna
- **File Scan:** true
- **Folder Depth:** 6
- **Folders:**
  - `/mnt/documents/jnj`
  - `/mnt/documents/zf`
- **Force Scan:** false
- **Key Vault:** true
- **Machine Password:** bot
- **Mount Script:** cds-mount-script
- **Mount Type:** AzureFileshare
- **NER Model:** 
  - `en_core_web_eg`

### Schedule Configuration (schedule_conf)
- **Hour:** 0
- **Interval:** Interval.Month
- **Minutes:** 0
- **Trigger Status:** TriggerStatus.Active
- **Trigger Type:** TriggerType.Scheduled
- **UTC:** UtcTimezone.UTC
- **Weekday:** Weekday.Monday

### Text Configuration (text_conf)
- **CL Sample:** 10
- **Clean Empty Lines:** true
- **Clean Header Footer:** true
- **Clean Whitespace:** true
- **Page Limit:** 5
- **Sample Text:** 
- **Split By:** word
- **Split Length:** 50
- **Split Overlap:** 20
- **Split Respect Sentence Boundary:** true
