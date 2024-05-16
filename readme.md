# Log and Issue Data

## Overview
This repository contains several CSV files that store information about log templates, issue sentences, issue reports, and their corresponding manual annotations of emotion and sentiment.

## Files
1. `Lohgbub_log_emotion_sentiment.csv`: This file contains log templates data with the following columns:
   - `NO.`: Sequential number of the log templates.
   - `Project`: Name of the project associated with the log templates.
   - `EventId`: Identifier for the log templates.
   - `EventTemplate`: Template of the log templates.
   - `Manual_Emotion`: Manually annotated emotion for the log templates.
   - `Manual_Sentiment`: Manually annotated sentiment for the log templates.

2. `IssueData_issue_sentence_manual_emotion.csv`: This file contains issue sentence data with the following columns:
   - `Filename`: Name of the file associated with the issue sentence.
   - `Sentence`: Text of the issue sentence.
   - `manual_emotion`: Manually annotated emotion for the issue sentence.
   - `manual_sentiment`: Manually annotated sentiment for the issue sentence.

3. `IssueData_issue_description_manual_emotion.csv`: This file contains issue report data with the following columns:
   - `Filename`: Name of the file associated with the issue report.
   - `IssueReport`: Text of the issue report.
   - `ManualEmotion`: Manually annotated emotion for the issue report.
   - `manual_sentiment`: Manually annotated sentiment for the issue report.

4. `RQ3_potential_critical_logs_and_its_issue_reports.csv`: This file contains data related to potential critical logs and their associated issue reports, with the following columns:
   - `Filename`: Name of the file associated with the log templates.
   - `Log_Level`: Level of the log templates.
   - `Tools_Senti_Emo`: Tools' sentiment and emotion annotations for the log templates.

5. `RQ3_critical_logs_and_its_issue_reports.csv`: This file contains data related to critical logs and their associated issue reports, with the following columns:
   - `Filename`: Name of the file associated with the log templates.
   - `Log_Level`: Level of the log templates.
   - `Tools_Senti_Emo`: Tools' sentiment and emotion annotations for the log templates.
   - `Manual_Senti_Emo`: Manually annotated sentiment and emotion for the log templates.
   - `Concerns`: Concerns associated with the log templates and issue report.