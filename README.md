
## Usage Example and Guide

For practical applications and detailed examples of utilizing the SCRQD dataset, please refer to the [Example Usage Notebook](./ExampleUsage.ipynb) included in this repository. The notebook provides step-by-step guides and examples that demonstrate how to effectively work with and analyze the data from each table in the SCRQD dataset.

Additionally, for a deeper understanding of our proposed model implementations and to see them in action, please explore the following detailed notebooks:

- **STL Model Notebook**: [STL Model for Element Extraction](./stl-model-notebook) - This notebook provides insights into using the Single Task Learning (STL) model specifically for Element Extraction tasks within the SCRQD dataset. The STL Element Extraction model breaks down into three primary tasks: Entity Extraction, Aspect Extraction, and Constraint Extraction. This notebook focuses on demonstrating the methodology for Element Extraction. The approaches for the other two tasks (Aspect and Constraint Extraction) can be applied similarly, with adjustments made only to the input data as necessary.
- **MTL Model Notebook**: [MTL Model for Element Extraction](./mtl-model-notebook) - Explore how our Multi-Task Learning (MTL) model addresses multiple extraction tasks simultaneously.
- **MTL + Adapter Model Notebook**: [MTL + Adapter Model for Element Extraction](./mtl-adapter-model-notebook) - This notebook details the enhancements made by incorporating an adapter into the MTL model to further boost performance.
- **CEI Model Notebook**: [CEI Model for Compared Elements Identification](./cei-model-notebook) - A comprehensive guide on identifying roles and establishing valid comparative relations within the dataset.
- **CPC Model Notebook**: [CPC Model for Comparative Preference Classification](/cpc-model-notebook) - Demonstrates how comparative preferences are classified in our CPC model.

Each specialized notebook is designed to provide an in-depth look at the respective methodologies and their application to the SCRQD dataset.


