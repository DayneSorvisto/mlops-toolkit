# MLOps Toolkit
## Data science project accelerator

[![License](https://img.shields.io/badge/License-Freeware-brightgreen.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/DayneSorvisto/mlops-lifecycle-toolkit.svg)](https://github.com/DayneSorvisto/mlops-lifecycle-toolkit/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/DayneSorvisto/mlops-lifecycle-toolkit.svg)](https://github.com/DayneSorvisto/mlops-lifecycle-toolkit/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/DayneSorvisto/mlops-lifecycle-toolkit.svg)](https://github.com/DayneSorvisto/mlops-lifecycle-toolkit/pulls)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/DayneSorvisto/mlops-lifecycle-toolkit.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20this%20awesome%20MLOps%20Lifecycle%20Toolkit%20repository%20on%20GitHub:%20https://github.com/DayneSorvisto/mlops-lifecycle-toolkit)

# Project Overview

This project is both a dynamic list of open source tools for MLOps organized by category as well as an accelerator with practical examples of using these components to achieve and end-to-end workflow from data cleaning, EDA and visualization to model, feature stores, model training, serving deployment and monitoring.

## Features

- Entirely code-driven for a customizable workflow
- Supports:
  - Experiment Tracking via MLFlow
  - Feature Store ising Feast
  - Exploratory Data Analysis
  - Custom Python packages
  - Training Pipelines Examples 
  - Inference Pipelines Examples

### Getting Started

The "toolkit" itself is located in the src folder and includes a Python cookiecutter package so folder structure can be customized.

Launch the platform by running

```docker compose up```

inside the infrastructure folder.

A step-by-step approach to building the toolkit located in src is given in my book [*MLOps Lifecycle Toolkit*](https://link.springer.com/book/10.1007/978-1-4842-9642-4) (Apress, 2023) where many tools in this list were evaluated (something close to 100 open source tool). feel Free to contribute more tools, re-organize the list or add new categories.

## MLOps Tools Comprehensive List:

1. **[MLflow](https://mlflow.org/)**
   - MLflow is an open-source platform for managing the end-to-end machine learning lifecycle, including tools for tracking experiments, packaging code into reproducible runs, and sharing and deploying models.

2. **[Kubeflow](https://kubeflow.org/)**
   - Kubeflow is a Kubernetes-native platform for deploying, monitoring, and managing machine learning models at scale, providing essential components for the entire machine learning lifecycle.

3. **[TensorFlow Extended (TFX)](https://www.tensorflow.org/tfx)**
   - TFX is an end-to-end platform for deploying production-ready machine learning models, with components for data validation, transformation, model analysis, and serving.

4. **[Apache Airflow](https://airflow.apache.org/)**
   - Apache Airflow is an open-source platform for programmatically authoring, scheduling, and monitoring workflows, suitable for data engineering tasks such as ETL processes.

5. **[Apache Kafka](https://kafka.apache.org/)**
   - Apache Kafka is a distributed streaming platform widely used for building real-time data pipelines and streaming applications, designed for high throughput and fault tolerance.
  
## Data Engineering Tools:

6. **[Apache Beam](https://beam.apache.org/)**
   - Apache Beam is an open-source, unified model for defining both batch and streaming data-parallel processing pipelines, supporting multiple execution engines, including Apache Flink and Apache Spark.

7. **[DBT (Data Build Tool)](https://www.getdbt.com/)**
   - DBT is an open-source analytics engineering tool enabling data analysts and engineers to transform data in their warehouse more effectively.

8. **[Singer](https://www.singer.io/)**
   - Singer is an open-source project for building ETL pipelines, providing a standard way to ingest data into data warehouses.

9. **[Prefect](https://www.prefect.io/)**
   - Prefect is an open-source data workflow management system, automating, scheduling, and monitoring data workflows.

10. **[Dagster](https://dagster.io/)**
    - Dagster is an open-source data orchestrator for machine learning, analytics, and ETL workflows.

## Visualization Tools:

11. **[Metabase](https://www.metabase.com/)**
    - Metabase is an easy-to-use open-source business intelligence tool for data visualization, exploration, and collaboration.

12. **[Apache Superset](https://superset.apache.org/)**
    - Apache Superset is a modern, enterprise-ready business intelligence web application, enabling users to create interactive dashboards.

13. **[Redash](https://redash.io/)**
    - Redash is an open-source business intelligence and data visualization tool, connecting to various data sources and enabling collaborative data exploration.

14. **[Holoviews](http://holoviews.org/)**
    - Holoviews is an open-source Python library simplifying data visualization, making it easy to explore, understand, and communicate data.

## Analytics Database Tools:

15. **[pgAdmin](https://www.pgadmin.org/)**
    - pgAdmin is a popular open-source administration and management tool for the PostgreSQL database.

16. **[PostGIS](https://postgis.net/)**
    - PostGIS is an open-source spatial database extender for PostgreSQL, allowing geospatial objects to be stored and queried.

## Big Data Tools:

17. **[Apache Spark](https://spark.apache.org/)**
    - Apache Spark is an open-source distributed computing system providing fast data processing and analytics capabilities.

18. **[Hadoop](https://hadoop.apache.org/)**
    - Apache Hadoop is an open-source framework for distributed storage and processing of large datasets.

19. **[Flink](https://flink.apache.org/)**
    - Apache Flink is an open-source stream processing framework for big data processing and analytics.

20. **[Presto](https://prestodb.io/)**
    - Presto is an open-source distributed SQL query engine optimized for ad-hoc analysis and data exploration.

21. **[Hive](https://hive.apache.org/)**
    - Apache Hive is an open-source data warehouse software facilitating querying and managing large datasets stored in Hadoop.

22. **[Presto](https://prestodb.io/)**
    - Presto is an open-source distributed SQL query engine optimized for ad-hoc analysis and data exploration.

23. **[Hive](https://hive.apache.org/)**
    - Apache Hive is an open-source data warehouse software facilitating querying and managing large datasets stored in Hadoop.

24. **[HBase](https://hbase.apache.org/)**
    - Apache HBase is an open-source, distributed, versioned, and non-relational database modeled after Google's Bigtable.

25. **[Druid](https://druid.apache.org/)**
    - Apache Druid is an open-source, column-oriented, distributed data store for real-time analytics.

26. **[Cassandra](https://cassandra.apache.org/)**
    - Apache Cassandra is an open-source NoSQL database management system designed to handle large amounts of data across many commodity servers.

27. **[Kylin](http://kylin.apache.org/)**
    - Apache Kylin is an open-source distributed analytics engine designed for big data and supports extremely fast OLAP (Online Analytical Processing) queries.

28. **[Hudi](https://hudi.apache.org/)**
    - Apache Hudi is an open-source data lake storage system for managing and evolving large analytical datasets.

29. **[Alluxio](https://www.alluxio.io/)**
    - Alluxio is an open-source distributed storage system providing a unified data access layer for big data and machine learning workloads.

30. **[Pachyderm](https://www.pachyderm.com/)**
    - Pachyderm is an open-source data versioning, data lineage, and data pipeline system built on containerized data.

31. **[Deeplearning4j](https://deeplearning4j.org/)**
    - Deeplearning4j is an open-source, distributed deep learning library for Java and Scala.

32. **[Ray](https://ray.io/)**
    - Ray is an open-source framework for building and running distributed applications.

33. **[Kedro](https://kedro.readthedocs.io/)**
    - Kedro is an open-source development workflow framework for machine learning.

34. **[MLflow Model Registry](https://www.mlflow.org/docs/latest/model-registry.html)**
    - MLflow Model Registry is a component of MLflow managing the full lifecycle of machine learning models.

35. **[AthenaX](https://uber.github.io/athenax/)**
    - AthenaX is an open-source streaming analytics platform.

36. **[Apache Drill](https://drill.apache.org/)**
    - Apache Drill is an open-source schema-free SQL query engine for large-scale data exploration and analysis.

37. **[Apache Nifi](https://nifi.apache.org/)**
    - Apache NiFi is an open-source data integration tool providing a web-based interface for designing data flows.

38. **[Amundsen](https://www.amundsen.io/)**
    - Amundsen is an open-source data discovery and metadata platform offering a user interface for exploring and querying data.

39. **[Apache Zeppelin](https://zeppelin.apache.org/)**
    - Apache Zeppelin is an open-source notebook-based environment for interactive data analysis and visualization.

40. **[DataGrip](https://www.jetbrains.com/datagrip/)**
    - DataGrip is an open-source integrated development environment (IDE) for SQL, supporting multiple database systems.

41. **[DBeaver](https://dbeaver.io/)**
    - DBeaver is an open-source database management tool supporting various database systems and including a built-in SQL editor.

42. **[pgTap](https://pgtap.org/)**
    - pgTap is an open-source unit testing framework for PostgreSQL databases, enabling automated testing of database schemas and functions.

43. **[PostgreSQL Citus Extension](https://www.citusdata.com/)**
    - The Citus extension for PostgreSQL is an open-source extension that scales out PostgreSQL across multiple machines.
    - 
44. **[Superset](https://superset.incubator.apache.org/)**
    - Superset is an open-source business intelligence platform allowing users to explore and visualize data, create dashboards, and share insights.

45. **[Redash](https://redash.io/)**
    - Redash is an open-source business intelligence and data visualization tool connecting to various data sources and enabling collaborative data exploration.

46. **[dbt (Data Build Tool)](https://www.getdbt.com/)**
    - dbt (Data Build Tool) is an open-source analytics engineering tool helping data analysts and engineers transform their data in the data warehouse.

47. **[Airflow](https://airflow.apache.org/)**
    - Apache Airflow, as mentioned earlier, is an open-source platform for orchestrating complex data workflows, including ETL processes.

48. **[Citus](https://www.citusdata.com/)**
    - Citus, as mentioned earlier, is an open-source extension for PostgreSQL enabling horizontal scaling for large-scale data.

49. **[Greenplum Database](https://greenplum.org/)**
    - Greenplum Database is an open-source massively parallel processing (MPP) database for large-scale analytics.

## Data Science Open-Source Software:

50. **[NumPy](https://numpy.org/)**
    - NumPy is a fundamental package for scientific computing with Python, providing support for large, multi-dimensional arrays and matrices.

51. **[Pandas](https://pandas.pydata.org/)**
    - Pandas is an open-source data analysis and manipulation library for Python, providing data structures for efficiently storing and processing large datasets.

52. **[Scikit-learn](https://scikit-learn.org/)**
    - Scikit-learn is an open-source machine learning library for Python, providing simple and efficient tools for data analysis and modeling.

53. **[Matplotlib](https://matplotlib.org/)**
    - Matplotlib is an open-source plotting library for Python, enabling the creation of static, animated, and interactive visualizations.

54. **[Seaborn](https://seaborn.pydata.org/)**
    - Seaborn is an open-source data visualization library for Python, based on Matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.

55. **[Statsmodels](https://www.statsmodels.org/)**
    - Statsmodels is an open-source library for estimating and testing statistical models in Python.

56. **[Jupyter](https://jupyter.org/)**
    - Jupyter is an open-source, interactive web application allowing the creation and sharing of documents containing live code, equations, visualizations, and narrative text.

57. **[TensorFlow](https://www.tensorflow.org/)**
    - TensorFlow is an open-source machine learning framework developed by Google, providing a comprehensive ecosystem of tools, libraries, and community resources.

58. **[PyTorch](https://pytorch.org/)**
    - PyTorch is an open-source machine learning framework developed by Facebook, known for its dynamic computation graph and strong support for deep learning.

59. **[SciPy](https://www.scipy.org/)**
    - SciPy is an open-source library used for scientific and technical computing in Python, built on NumPy.

60. **[NLTK (Natural Language Toolkit)](https://www.nltk.org/)**
    - NLTK is an open-source library for working with human language data in Python, providing easy-to-use interfaces to over 50 corpora and lexical resources.
    - 
61. **[Plotly](https://plotly.com/)**
    - Plotly is an open-source Python graphing
    - 
## LLMOps Tools:

62. **[LangChang](https://example-langchang-url.com/)**
    - LangChang is an open-source tool for Large Language Model Operations, providing capabilities for managing, deploying, and monitoring large language models.
   
# MLOps Tutorials

A collection of open-source tutorials on MLOps to help you learn and implement machine learning operations best practices.

1. **MLOps with TensorFlow Extended (TFX)**
   - [GitHub Repository](https://github.com/tensorflow/tfx)

2. **MLflow: An Open Platform for the Complete Machine Learning Lifecycle**
   - [GitHub Repository](https://github.com/mlflow/mlflow)

3. **DVC: Data Version Control - Make your data science projects reproducible and shareable**
   - [GitHub Repository](https://github.com/iterative/dvc)

4. **Kubeflow: Machine Learning Toolkit for Kubernetes**
   - [GitHub Repository](https://github.com/kubeflow/kubeflow)

5. **MLOps Practical Tutorial with CI/CD, CD4ML, A/B Testing, and Canary Deployment**
   - [GitHub Repository](https://github.com/gnsya/ci-cd-for-ml)

6. **End-to-End MLOps Project with Azure Machine Learning**
   - [GitHub Repository](https://github.com/microsoft/MLOps-E2E)

7. **MLOps Examples**
   - A collection of end-to-end MLOps examples using various tools.
   - [GitHub Repository](https://github.com/visenger/awesome-mlops)

8. **Machine Learning Operations (MLOps) Workshop**
   - A workshop covering MLOps concepts and practical implementation.
   - [GitHub Repository](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp/06-production)
  

## Project Goals:

- **Open Source Adaptation:** The project serves as a fork of the MLOps Lifecycle Toolkit outlined in the book (contributions could make their way into future editions of the book and serve as documentation for beginners interested in adapting MLOps to data science). By making the toolkit open source, the goal is to encourage collaboration and contributions from the broader MLOps community.

- **Comprehensive List:** The project aims to curate and maintain a comprehensive list of open-source tools spanning various domains within the emerging data science landscape. This includes MLOps, data engineering, business intelligence, databases, big data, LLMOps (Large Language Model Operations), and scientific computing and more as they are identified.

- **Community Contributions:** Emphasizing the collaborative nature of open source, the project welcomes contributions from individuals with diverse backgrounds to build a robust and versatile toolkit that can be used across industries. 

## Contributing:

To contribute, simply fork the repository, make your changes, and submit a pull request. Refer to the [Contributing.md](Contributing.md) file for detailed information on how to contribute to this open-source project.

Let's collaborate to build a comprehensive and dynamic resource that empowers the data science community!

# Supporting the project

This repository accompanies [*MLOps Lifecycle Toolkit*](https://link.springer.com/book/10.1007/978-1-4842-9642-4) by Dayne Sorvisto (Apress, 2023).

[comment]: #cover
![Cover image](978-1-4842-9641-7.jpg)





