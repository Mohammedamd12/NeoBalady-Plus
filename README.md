# NeoBalady-Plus

**An AI-powered municipal complaint management platform**

NeoBalady+ is graduation project, developed as an academic initiative in collaboration with Makkah Municipality. It is a multi-model proof of concept (PoC) that explores how artificial intelligence and predictive analytics can support the municipal complaint lifecycle—from receiving and understanding a report to prioritizing it, estimating resolution time, anticipating potential hotspots, and verifying completed work.

## The Problem

Municipal complaint systems often depend on manual classification, prioritization, and assignment processes. This can lead to delays and inconsistencies, make urgent cases harder to identify quickly, and limit the ability to plan proactively. Traditional workflows may also rely on static resolution deadlines and lack effective methods for forecasting complaint volumes by location, season, or major event.

NeoBalady+ was designed to investigate how a coordinated set of AI models could assist with these challenges while keeping human and institutional decision-making at the center of the process.

## Project Overview

The platform combines computer vision, natural language processing, machine learning, and deep spatio-temporal forecasting in a single AI-assisted workflow. It transforms unstructured inputs such as images and Saudi Arabic voice notes into structured information that can support citizens, municipal personnel, and field operations.

NeoBalady+ explores:

- forecasting where complaint hotspots may emerge.
- identifying potentially duplicate reports.
- estimating expected complaint-resolution timelines.
- prioritizing complaints using multimodal risk signals.
- transcribing and summarizing Saudi Arabic speech.
- comparing evidence captured before and after maintenance work.
- answering Arabic municipal-service questions through document-based retrieval.

## Evaluation

Component | Evaluation measure | Result |
| --- | --- | ---: |
| Image classification | Main-category accuracy | 76% |
| Priority assessment | Priority-level accuracy | 75% |
| Duplicate detection | Binary classification accuracy | 66% |
| Closure verification | Repair-decision accuracy | 80% |
| SLA prediction | Coefficient of determination (R²) | 0.963 |
| SLA prediction | Mean absolute error (MAE) | 0.082 |
| ConvLSTM forecasting | Top-500 grid-cell hit rate | Above 50% |
| Speech transcription | Word error rate (WER) | 36.67% |
| Speech transcription | Character error rate (CER) | 12.54% |

The 76% figure specifically represents main-category image-classification accuracy; it is not a measure of the entire platform. The SLA model's R² score was measured on a reserved portion of the synthetic dataset.
