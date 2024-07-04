## Bot Configuration

### Configuration Details

- **Configuration Name:** basebot
- **Model Type:** KeywordModel
- **Bot ID:** drawings
- **Process ID:** process2
- **Folder:** /mnt/documents/zf/PLM
- **Bot Cluster ID:** bot234
- **Master:** true
- **Limit:** 650

### Model Details

- **Model Name:** facebook/detr-resnet-50
- **Learning Rate:** 0.5
- **Backbone Learning Rate:** 0.00001
- **Weight Decay:** 0.0001
- **Batch Size:** 1
- **Train Size:** 0.75
- **Validation Size:** 0.1
- **Test Size:** 0.05
- **Max Epochs:** 10
- **Gradient Clip Value:** 0.1
- **Accumulate Grad Batches:** 8
- **Log Every N Steps:** 10
- **Keyword Model 2:** RandomForestClassifier
- **Feature Masks 2:**
  - coordinates
  - aspect_ratio
  - word_features
  - char_features
  - nearest_neighbors

### Schedule Configuration

- **Trigger Status:** Active
- **Trigger Type:** Scheduled
- **Interval:** Month
- **Weekday:** Monday
- **Hour:** 0
- **Minutes:** 0
- **UTC:** UTC (Coordinated Universal Time)
