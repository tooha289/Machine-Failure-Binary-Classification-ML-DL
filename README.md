- [Project Background](#project-background)
- [Project Objectives](#project-objectives)
- [Description of the Dataset](#description-of-the-dataset)
- [Project Source:](#project-source)
- [Dataset Description Source](#dataset-description-source)

* [[한국어 README Link]](https://github.com/tooha289/Machine-Failure-Binary-Classification-ML-DL/blob/main/README-ko.md)
# Project Background
Machine failures are a significant issue in the industrial sector, as they can lead to production disruptions, increased maintenance costs, safety concerns, and various other problems. Consequently, there is a growing need for models and systems that can predict and prevent machine failures in advance. To address these challenges, a project that utilizes machine learning and data analysis to predict machine failures and develop proactive maintenance systems is essential.

# Project Objectives
The primary goal of this project is to implement a binary classification model using the given dataset to predict machine failures. Specific objectives include:

**Machine Failure Prediction**: Develop a model that predicts whether a machine will fail based on the data, enabling the anticipation of potential machine failures and the implementation of preventive measures.

**Failure Cause Analysis**: Identify the major causes of failures (TWF, HDF, PWF, OSF, RNF) and investigate the correlations between each cause and machine sensor data. This analysis helps understand under what conditions machine failures are more likely to occur.

**Performance Optimization**: Apply various machine learning algorithms and optimize the model's performance. Improve metrics such as accuracy, recall, precision, among others, to achieve reliable failure predictions.

# Description of the Dataset
The dataset used in this project consists of information collected from various sensors on machines. It includes the following key features:

**ID**: A unique identifier assigned to each record for indexing and reference purposes.

**Product Id**: A combination of the machine type (Type) variable and an identifier number that helps identify each product.

**Type**: Represents the type of machine, aiding in understanding its operational characteristics, which may be related to the probability of failure.

The dataset classifies machines into three distinct classes:

* **L (Low Type)**: These machines are primarily used for lightweight operations or tasks with minimal load. They are expected to be relatively smaller in size and lower in complexity compared to other types.

* **M (Medium Type)**: Medium-type machines are versatile and capable of handling a wide range of tasks or moderate levels of load. They are characterized by moderate size and complexity.

* **H (High Type)**: High-type machines are designed for heavy-duty operations or tasks with substantial loads. They tend to be larger and more complex compared to low or medium types.

**Air temperature [K]**: Represents the ambient temperature around the machine, measured in Kelvin (K). Temperature can be a crucial factor as machines may behave differently under varying ambient temperatures.

**Process temperature [K]**: Represents the temperature of the process in which the machine is engaged, also measured in Kelvin (K). Certain processes can cause the machine to heat up, increasing the chances of failure.

**Rotational speed [rpm]**: Indicates the speed at which the machine operates, measured in rotations per minute (rpm). Higher speeds could potentially lead to increased wear and tear.

**Torque [Nm]**: Measures the force that causes the machine to rotate. High torque might indicate a high load on the machine, which could increase the likelihood of failure.

**Tool wear [min]**: Indicates the degree of wear and tear the machine has undergone, measured in minutes. High tool wear might indicate that the machine is due for maintenance.

**Machine failure**: A binary indicator specifying whether the machine failed (1) or not (0).

**Other Failure Modes**: The dataset includes information about other potential causes of machine failures, such as TWF, HDF, PWF, OSF, and RNF. These failure modes contribute to a more comprehensive understanding of machine failures.

Failure modes describe the potential root causes of failures within a machine or system, rather than directly indicating the occurrence of a failure. These causes are among the key factors that can lead to failures. Failures can occur based on specific causes or conditions, and sometimes, multiple causes can interact, leading to failures.

For instance, "Heat Dissipation Failure (HDF)" is one of the potential failure modes that can occur within a machine or system, and it can lead to failures. Overheating can result in component damage, which, in turn, can lead to failures. However, HDF itself does not represent a machine's failure; it is an explanation of a possible cause that can contribute to a failure or a decrease in machine performance.

Therefore, there can be a relationship between failure modes and actual failures, with causes potentially leading to specific outcomes. However, it's essential to distinguish between causes and results. Identifying the precise causes and implementing corresponding measures to manage and prevent failure modes is crucial.

The dataset provides detailed explanations for other failure modes classified under "Other Failure Modes."

* **TWF (Tool Wear Failure)**: Indicates whether the machine failed due to tool wear.

* **HDF (Heat Dissipation Failure)**: Indicates whether the machine failed due to an inability to dissipate heat.

* **PWF (Power Failure)**: Indicates whether the machine failed due to a power problem.

* **OSF (Overstrain Failure)**: Indicates whether the machine failed due to being overstrained.

* **RNF (Random Failure)**: Indicates whether the machine failed due to a random, unspecified issue.

These failure modes provide additional insights into the causes of machine failures and can aid in developing effective preventive strategies.

# Project Source:
The source of this project's dataset and competition is as follows:

**Competition Source**: [Kaggle Playground Series - S3E17](https://www.kaggle.com/competitions/playground-series-s3e17/overview)

Kaggle is a globally recognized online platform for data science and machine learning, hosting various data science competitions and challenges. The dataset for this project was provided as part of the Kaggle Playground Series "S3E17," focusing on machine failure prediction tasks.

# Dataset Description Source
The description and information about the dataset are sourced from the following:

**Dataset Description Source**: [GitHub - Binary Classification of Machine Failures](https://github.com/JMViJi/Binary-Classification-of-Machine-Failures)

Detailed information about the dataset, variable descriptions, and information about failure causes can be found in the GitHub repository "Binary Classification of Machine Failures." This repository provides comprehensive information and project-related files related to the dataset. This information served as the background knowledge required for understanding and analyzing the data.