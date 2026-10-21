# Credit Card Fraud Detection Using Machine Learning

## Section 1. Charter Introduction

This charter provides an initial description of the proposed credit card fraud
detection project, its intended outcomes, the principal work to be undertaken,
and the deliverables expected from the project team.

### 1.1 Document Change Control

| Version | Date | Change description | Status |
| --- | --- | --- | --- |
| 0.1 | 2026-10-21 | Initial incomplete project charter draft | Draft |

Subsequent revisions should be recorded in this table to maintain a history of
changes to the charter.

### 1.2 Executive Summary

Credit card fraud creates substantial costs for banks through unauthorized
transactions, customer reimbursements, investigations, additional security
measures, and potential legal proceedings. Fraud can also damage a bank's
reputation by reducing customer confidence in the safety of its services.

The proposed project will develop a machine learning system to identify
potentially fraudulent credit card transactions. The team will obtain historical
transaction records containing legitimate and fraudulent examples, prepare the
data for analysis, train and evaluate supervised learning models,
and investigate
whether anomaly detection methods improve detection. The selected approach will
then be integrated into a system that evaluates incoming transactions in real
time and flags potentially fraudulent activity for further handling.

The expected business outcome is improved support for fraud detection, with the
potential to reduce financial losses and strengthen customer trust. The main
deliverables are a prepared transaction dataset, reproducible data-processing
and model-training components, an evaluation report, and a real-time transaction
scoring system. Key concerns to assess during planning include access to
suitable transaction data, privacy and security obligations, class imbalance,
and the trade-off between missed fraud and false alarms. Performance targets,
project dates, and the total cost estimate have not yet been established.

### 1.3 Authorization

The following record identifies the proposed team and the outstanding approval
required before this charter can be treated as formally authorized.

| Role | Name | Authorization or acknowledgment | Date |
| --- | --- | --- | --- |
| Project sponsor | Marcel Jr | Approved | 2026-10-21 |
| Principal Investigator | Marcel Jar | Approved | 2026-10-21 |
| Data Scientist | Tony Stark | Acknowledgment pending | TBD |
| Financial Specialist | Bruce Banner | Acknowledgment pending | TBD |

## Section 2. Project Overview

The project will proceed from historical transaction data collection and
preparation through fraud-model development and evaluation to integration with
a real-time transaction assessment system.

### 2.1 Project Summary

The project's goal is to develop a system that uses machine learning to detect
potential fraud in credit card transactions. Historical records representing
both legitimate and fraudulent transactions will be collected from an
appropriately authorized source. The team will preprocess the dataset by
addressing missing values, normalizing relevant features, and managing the
imbalance between fraudulent and legitimate transactions. Apache Spark will be
used for large-scale data preprocessing.

The initial supervised learning approaches will include logistic regression and
decision trees. Models will be trained on one portion of the dataset, assessed
on held-out data, and tuned to improve predictive performance. The team will
also examine anomaly detection techniques, such as isolation forests or
one-class support vector machines, to determine whether they add value.
Implementation will use Python and relevant libraries, including pandas,
scikit-learn, and TensorFlow where appropriate.

The selected model will be incorporated into a real-time system that evaluates
incoming transactions and produces fraud-risk predictions or flags. Model
quality will be assessed using agreed performance measures that account for
both fraudulent transactions missed and legitimate transactions incorrectly
flagged. Specific acceptance thresholds, deployment arrangements, schedule,
and budget remain to be determined.

The proposed team consists of Marcel Jar (Principal Investigator), Tony Stark
(Data Scientist), and Bruce Banner (Financial Specialist).

### 2.3 Project Scope

### 2.4 Milestones

These are preliminary milestones in the expected sequence of work. Target dates
and formal approval gates will be confirmed during project planning.

| Milestone | Completion event | Target date |
| --- | --- | --- |
| M1 - Charter authorization | Project charter reviewed and formally approved | TBD |
| M2 - Dataset acquisition | Suitable historical data obtained with documented permission to use it | TBD |
| M3 - Data preparation | Cleaned and processed dataset ready for model training | TBD |
| M4 - Supervised model evaluation | Baseline models trained and evaluated on held-out data | TBD |
| M5 - Model selection | Tuning and anomaly detection assessment completed; preferred model selected | TBD |
| M6 - Real-time integration | Incoming transactions can be scored by the selected model | TBD |
| M7 - System validation | End-to-end tests and final results reviewed against agreed criteria | TBD |

### 2.5 Deliverables

The following proposed deliverables include both technical outputs and key
project management artifacts. Acceptance criteria are provisional and will need
to be approved during detailed planning.

| Deliverable | Description | Preliminary acceptance criteria |
| --- | --- | --- |
| D1 - Approved charter and project plan | Authorized charter and initial schedule of work | Charter signed by the appropriate authority; project plan reviewed |
| D2 - Transaction dataset and data description | Historical legitimate and fraudulent transaction examples, with documented features and data provenance | Data source and permitted use documented; dataset suitable for analysis |
| D3 - Data preparation pipeline | Repeatable handling of missing data, feature normalization, and class imbalance, using Spark for large-scale processing | Pipeline can be rerun and produces training-ready data |
| D4 - Trained supervised models | Logistic regression and decision tree fraud detection models | Model training is reproducible and results can be generated on held-out data |
| D5 - Model assessment and selection report | Comparison of predictive performance, tuning results, and relevant anomaly detection experiments | Metrics, false-alarm trade-offs, limitations, and model selection rationale documented |
| D6 - Real-time fraud scoring system | Integration that evaluates incoming transaction data with the chosen model | End-to-end tests demonstrate that transaction inputs generate fraud-risk outputs |
| D7 - Testing and technical documentation | Evaluation results, integration instructions, and known operational limitations | Documentation and test results reviewed against agreed acceptance criteria |

### 2.6 Project Cost Estimate

### 2.7 Dependencies

### 2.8 Project Risks, Assumptions, and Constraints

#### 2.8.1 Risks

#### 2.8.2 Assumptions

#### 2.8.3 Constraints

## Section 3. Project Organization

### 3.1 Project Governance

### 3.2 Project Team Structure

### 3.3 Roles and Responsibilities

### 3.4 Project Facilities and Resources

## Section 4. Project References

## Section 5. Glossary and Acronyms
