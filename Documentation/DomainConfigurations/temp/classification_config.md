## Configuration: amnivitab_gpt

### General Information
- **Partition Key:** cas-todt
- **Row Key:** amnivitab_gpt
- **Configuration Name:** amnivitab_gpt
- **Dashboard ID:** e78494df-405f-438e-3875-c72b4e4c92dd
- **Dashboard URL:** [Dashboard Link](https://your-kibana-instance/app/kibana#/dashboard/e78494df-405f-438e-3875-c72b4e4c92dd)
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
- **Quantize:** false
- **SP Model:** []
- **SP Quantize:** true
- **SP Sampling:** 16000
- **Table Selection:** []
- **Translator Selection:** []
- **Use MMR:** true
- **ZS Model:** 
  - `facebook/bart-large`
  - `gpt-3`
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
