# Exploration of the Subjective Comparative Relation Quintuples Dataset (SCRQD)

## Introduction to the SCRQD Dataset
The Subjective Comparative Relation Quintuples Dataset (SCRQD) is a comprehensive dataset designed specifically for the analysis of subjective comparative questions in the smartphone domain. Distinguished by its detailed structure, the SCRQD dataset is instrumental in advancing the field of Automatic Subjective Question Answering (ASQA) systems.


## Overview of the SCRQD Dataset
Comprising 1,275 meticulously annotated questions, SCRQD serves as a rich resource for examining the complexities inherent in subjective comparisons. This dataset is unique for its organization into five distinct tables, each focusing on a specific aspect of question analysis:

1. **Questions Table**: This table contains the text of each subjective comparative question.
2. **Relations Table**: It details the relationships and dynamics between the entities within the questions.
3. **Element Extraction Table**: This table focuses on extracting and identifying key elements from the questions.
4. **Entity Role Identification Table**: It categorizes the roles of different entities, defining how they are positioned within each question.
5. **Comparative Preference Classification Table**: This table classifies the types of preferences expressed in the questions.

Together, these tables provide a granular view of question subjectivity, making SCRQD an invaluable asset for researchers and developers in the ASQA domain.


## Main Classification Task in SCRQD
The primary task within SCRQD is the extraction and classification of Subjective Comparative Relation Quintuples, encompassing:

- Subject Entity
- Object Entity
- Compared Aspect
- Constraint
- Preference

These elements collectively offer a comprehensive perspective on the nature of comparisons in questions, facilitating a deeper understanding of user preferences and inquiries within the smartphone domain.

## Diving Deeper: Exploring the Subtasks in SCRQD
The dataset includes several vital subtasks, each contributing to a thorough understanding of the questions:

1. **Element Extraction (EE)**: Identifying key components of the questions, such as entities, aspects, and constraints.
2. **Entity Role Identification (ERI)**: Categorizing the roles of entities as subjects or objects in the comparative narrative.
3. **Comparative Preference Classification (CPC)**: Classifying the type of preference expressed in the questions.


## Sample Data from SCRQD

Below is a sample from one of the five tables in the SCRQD dataset to illustrate its structure and content. Please note that this is just a glimpse into one aspect of the dataset:

| ID | Example | Subject Entity | Object Entity | Compared Aspect | Constraint | Preference |
| -- | ------- | -------------- | ------------- | --------------- | ---------- | ---------- |
| 6 | I want a smartphone . I like that the Samsung Galaxy A 11 has a large screen , but I don t know if it will be as reliable as iPhone 8 ? | Samsung Galaxy A11 | reliable  | iPhone 8  | None | E |
| 99 | Are the camera functions on the IQOO 7 worse than Oneplus 8 T ? | IQOO 7 | camera functions  | OnePlus 8T | None | W |
| 102 | Are Lenovo smartphones better than Xiaomi phones , in the same price category , in general in terms of overall performance ? | Lenovo smartphones | overall performance | Xiaomi phones   | in the same price category | B |
| 212 | Why do a lot of K pop idols prefer an iPhone over Samsung ? | iPhone | All | Samsung | a lot of K pop idols | B |
| 219 | What are the major disadvantages of the Samsung note 20 over Samsung note 21 ? | Samsung note 20 | All | Samsung note 21 | major disadvantages | SW |
| 497 |I am crazy about taking photos . I want to buy the best smartphone with an excellent camera and battery life . Which is the best for 600 dollar ?   | X | camera | All | for 600 dollar | SB |
| 497 |I am crazy about taking photos . I want to buy the best smartphone with an excellent camera and battery life . Which is the best for 600 dollar ?   | X | battery life | All | for 600 dollar | SB |


This sample represents only a fraction of the comprehensive data available within the SCRQD dataset. For an in-depth exploration of data from all five tables and practical applications of the dataset, please refer to the [Example Usage Notebook](./ExampleUsage.ipynb) included in this repository.



## Usage Example and Guide

For practical applications and detailed examples of utilizing the SCRQD dataset, please refer to the [Example Usage Notebook](./ExampleUsage.ipynb) included in this repository. The notebook provides step-by-step guides and examples that demonstrate how to effectively work with and analyze the data from each table in the SCRQD dataset.

Additionally, for a deeper understanding of our proposed model implementations and to see them in action, please explore the following detailed notebooks:

- **STL Model Notebook**: [STL Model for Element Extraction](https://link-to-your-notebook.com/stl-model-notebook) - This notebook provides insights into using the Single Task Learning (STL) model specifically for element extraction tasks within the SCRQD dataset.
- **MTL Model Notebook**: [MTL Model for Element Extraction](https://link-to-your-notebook.com/mtl-model-notebook) - Explore how our Multi-Task Learning (MTL) model addresses multiple extraction tasks simultaneously.
- **MTL + Adapter Model Notebook**: [MTL + Adapter Model for Element Extraction](https://link-to-your-notebook.com/mtl-adapter-model-notebook) - This notebook details the enhancements made by incorporating an adapter into the MTL model to further boost performance.
- **CEI Model Notebook**: [CEI Model for Compared Elements Identification](https://link-to-your-notebook.com/cei-model-notebook) - A comprehensive guide on identifying roles and establishing valid comparative relations within the dataset.
- **CPC Model Notebook**: [CPC Model for Comparative Preference Classification](https://link-to-your-notebook.com/cpc-model-notebook) - Demonstrates how comparative preferences are classified in our CPC model.

Each specialized notebook is designed to provide an in-depth look at the respective methodologies and their application to the SCRQD dataset.


Each notebook provides step-by-step guides and examples that demonstrate how to effectively work with and analyze the data from each table in the SCRQD dataset, tailored to the specific modeling approach.


## Benchmarking SCRQD
SCRQD has been benchmarked against other prominent datasets in the field, demonstrating its superiority in capturing the nuances of subjective comparative questions with its unique structure and comprehensive annotations.

## Usage & Guidelines
We encourage researchers and practitioners to delve into the linguistic and structural details of the SCRQD dataset for optimal use in ASQA systems development and research.

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
