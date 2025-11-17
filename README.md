# [Dataset link]=(https://zenodo.org/records/17629015?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjZmNDdiMmJiLTZhOWEtNDNjZC04MGNmLWRlZGY0ZjBkNDk3NCIsImRhdGEiOnt9LCJyYW5kb20iOiIxN2YzYzI3YjQ2Y2Y3NWU2ZjU2ZDI3ZjRlOTMzNzU4MCJ9.S3nvpOUAC9yqpNjcozIcXVhuT5pKPEbwodzkb0CgMeGgu_SwjHQSODJsenPU1Gaev33YSCho1n2fshB8-aOrXw)

# Job Classifier Project

## Overview

This project contains three main components:
- `code/scraper.py` – Scrapes job-related data for training/testing.
- `trainer/job_classifier.py` – Trains and runs a job classification model.
- Displays all images from the `output/` folder.


<!-- ### Sample Output

![Job Classification Output](output/comprehensive_results_20250603_120511.png)
![Roberta Output](output/confusion_matrix_bert_epoch_4.png)
![bert output](output/confusion_matrix_bert_epoch_3.png) -->


### Job Categories

- Software Development / Engineering
- DevOps / Site Reliability Engineering
- AI
- Data Engineering
- Cybersecurity / InfoSec
- IT / Systems Engineering
- QA / Testing
- Product / Project Management (Technical)
- UI/UX / Design (Tech-Oriented)
- Misc / Specialized
- other

## Requirements

- Python 3.12+

### Install Dependencies

Install all required packages using `requirements.txt`:

```bash
python3.12 -m pip install -r requirements.txt
```

## Run

### Scraper

```bash
python3.12 code/scraper.py
```

### Trainer

```bash
python3.12 trainer/job_classifier.py
```
