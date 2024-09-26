






### Uber End-to-End Data Engineering Project: Leveraging Airflow and Python for Seamless Data Orchestration  
  Technologies Used: GCP Cloud Storage, Google Colab, Python, AWS EC2, Airflow, AWS S3, Tableau

This project focuses on building a fully automated data pipeline for Uber’s data using various tools and cloud platforms. The goal was to efficiently extract, transform, and load data, while ensuring smooth workflow orchestration and seamless integration with data visualization tools for insights.

Data Extraction from GCP Cloud Storage: Initiated the data pipeline by extracting raw data stored on Google Cloud Platform (GCP). The data, hosted on GCP Storage, was retrieved in its native format, preparing it for the next phase of transformation.
  
Data Transformation with Python: Utilized Python for preprocessing and transforming the extracted data. This involved cleaning, normalizing, and reshaping the data into a more structured format, ensuring it was ready for downstream processes. Python’s powerful libraries were leveraged to handle complex data manipulations efficiently.

Workflow Orchestration with Airflow on AWS EC2: Deployed the entire data pipeline on an AWS EC2 instance, orchestrated using Airflow. This ensured that the tasks were scheduled, managed, and monitored in a well-defined sequence. Airflow’s workflow orchestration capabilities facilitated the seamless automation of data extraction, transformation, and loading processes, providing a scalable and flexible solution.

Data Loading into AWS S3: After processing, the transformed data was securely loaded into an Amazon S3 bucket. S3 was chosen for its durability and scalability, ensuring that the data was readily accessible for further analysis and visualization while maintaining data integrity.

- Integration with Tableau for Visualization: Established a direct connection between the AWS S3 bucket and Tableau. This enabled the visualization of key insights from the transformed Uber data, providing actionable insights into various performance metrics. Tableau was used to build interactive dashboards, allowing stakeholders to explore trends, patterns, and analytics in real-time.

Inspired from:  
- Twitter Data Pipeline using Airflow for Beginners:  (https://www.youtube.com/watch?v=q8q3OFFfY6c)
- Uber Data Analytics: (https://www.youtube.com/watch?v=WpQECq5Hx9g)

