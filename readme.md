# Log and Issue Data

## Overview
This repository contains several CSV files that store information about log templates, issue sentences, issue reports, and their corresponding manual annotations of emotion and sentiment.

## Files
1. `Lohgbub_log_emotion_sentiment.csv`: This file contains log event data with the following columns:
   - `NO.`: Sequential number of the log event.
   - `Project`: Name of the project associated with the log event.
   - `EventId`: Identifier for the log event.
   - `EventTemplate`: Template of the log event.
   - `Manual_Emotion`: Manually annotated emotion for the log event.
   - `Manual_Sentiment`: Manually annotated sentiment for the log event.

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
   - `Filename`: Name of the file associated with the log event.
   - `Log_Level`: Level of the log event.
   - `Tools_Senti_Emo`: Tools' sentiment and emotion annotations for the log event.

5. `RQ3_critical_logs_and_its_issue_reports.csv`: This file contains data related to critical logs and their associated issue reports, with the following columns:
   - `Filename`: Name of the file associated with the log event.
   - `Log_Level`: Level of the log event.
   - `Tools_Senti_Emo`: Tools' sentiment and emotion annotations for the log event.
   - `Manual_Senti_Emo`: Manually annotated sentiment and emotion for the log event.
   - `Concerns`: Concerns associated with the log event and issue report.