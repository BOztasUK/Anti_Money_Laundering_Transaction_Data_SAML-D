# Anti_Money_Laundering_Transaction_Data_SAML-D

Welcome to the **Anti_Money_Laundering_Transaction_Data_SAML-D** repository. This dataset was developed to support research and development in the field of anti-money laundering (AML), providing a comprehensive synthetic transaction monitoring dataset with enhanced features and typologies to improve detection capabilities.

## Citation

If you use this dataset, please reference the paper below:

**B. Oztas, D. Cetinkaya, F. Adedoyin, M. Budka, H. Dogan, and G. Aksu**, "Enhancing Anti-Money Laundering: Development of a Synthetic Transaction Monitoring Dataset," 2023 IEEE International Conference on e-Business Engineering (ICEBE), Sydney, Australia, 2023, pp. 47-54, doi: [10.1109/ICEBE59045.2023.00028](https://ieeexplore.ieee.org/document/10356193).

## Dataset Overview

Money laundering remains a significant global issue, driving the need for improved transaction monitoring methods. Current AML procedures are often inefficient due to restricted access to data caused by legal and privacy constraints, as well as a lack of diversity and true labels in existing datasets.

This repository provides the **SAML-D** dataset, which is generated using a novel AML transaction generator. The dataset aims to aid researchers in evaluating their models and developing more advanced monitoring techniques. It comprises enhanced features and typologies that were selected based on existing datasets, academic literature, and interviews with AML specialists.

### Key Features of the Dataset

- **Total Transactions**: 9,504,852
- **Suspicious Transactions**: 0.1039%
- **Features**: 12
- **Typologies**: 28 (11 normal, 17 suspicious)
- **Graphical Network Structures**: 15 graphical representations of transaction flows

The dataset includes features such as transaction time, sender and receiver details, transaction amount, payment type, locations, and more. A 'suspicious' flag is also included, allowing for clear differentiation between normal and suspicious transactions. The dataset's graphical network structures represent complex transaction flows, enhancing the challenge for detection.

### Features Description

- **Time and Date**: Essential for tracking the chronology of transactions.
- **Sender and Receiver Account Details**: Key for uncovering behavioral patterns and complex banking connections.
- **Amount**: The value of each transaction, useful for identifying anomalies.
- **Payment Type**: Includes multiple methods such as credit card, debit card, cash, ACH transfers, cross-border, and cheque.
- **Sender and Receiver Bank Location**: Highlights high-risk regions, including Mexico, Turkey, Morocco, and the UAE.
- **Payment and Receiver Currency**: Adds complexity when currency and location features do not align.
- **'Is Suspicious' Feature**: Binary indicator for suspicious vs. normal transactions.
- **Type**: Provides the classification of each typology, offering deeper insights into transaction patterns.

### Typologies

The dataset incorporates 28 typologies (11 normal and 17 suspicious) that aim to reflect real-world behaviors in transaction monitoring, helping researchers design and test AML detection models. These typologies were chosen to provide a wide range of scenarios and increase the diversity of the dataset.

## Dataset Access

You can access the SAML-D dataset here:

[**SAML-D Dataset Download**](https://www.kaggle.com/datasets/berkanoztas/synthetic-transaction-monitoring-dataset-aml)

## More Information

For more details about the dataset, including its generation methodology and typology definitions, please refer to our paper listed above. This dataset is an updated version compared to the one used in the publication.
