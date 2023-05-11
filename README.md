# Investigating the Versatility of SPECTER: Data Integration, Temporal Classification, and Domain Transferability

Welcome to our GitHub repository, where we aim to enhance the SPECTER model with several extensions. Our work focuses on incorporating additional data sources, performing temporal paper classification, and exploring the use of SPECTER on other types of texts.

## Project Overview

SPECTER is a powerful tool designed for scientific documents, leveraging citation information to generate document embeddings. In this project, we broaden the horizons of SPECTER by introducing additional dimensions and capabilities to its structure.

## Key Areas of Work

1. AG News Text Classification Task.py: This script is utilized for training and evaluating SPECTER on the AG News dataset, a collection of news articles from over 2,000 news sources, to investigate SPECTER's performance and generalizability in handling non-scientific texts.

2. CORD 19 Baseline: This script contains the baseline implementation of the SPECTER model on the CORD-19 (COVID-19 Open Research Dataset) corpus. It represents the starting point from which the enhancements and extensions to the model are made.

3. CORD 19: full_text: This script extends the baseline SPECTER model to include additional data from the full text of the scientific papers in the CORD-19 corpus, aiming to improve the quality of the generated document embeddings.

4. CORD19: date: This script includes the implementation of the temporal paper classification strategy. The idea is to assign higher weights to more recent papers in the document embedding generation process, providing a temporal dimension to the representations.

You can run each script independently using the Python command

## Contributing

We welcome contributions to this project. If you have a feature request, bug report, or proposal for improvement, please open an issue. If you wish to contribute code, please open a pull request.

## Contact

If you have any questions or feedback, please feel free to contact us. You can open an issue or send us an email.
