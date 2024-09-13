# Cloud Computing Projects

This repository contains three cloud computing projects that showcase the power of distributed computing and machine learning algorithms using platforms like Apache Hadoop, Apache Spark, and modern frameworks.

## Projects:
1. [Music Recommender](https://github.com/Hamid-Rezaei/Music-Recommender)
2. [Search Movie](https://github.com/Hamid-Rezaei/Search-Movie)
3. [Hadoop and Spark](https://github.com/Hamid-Rezaei/Hadoop-Spark-Project)

### 1. Music Recommender
The Music Recommender project is designed to provide personalized music recommendations using collaborative filtering algorithms. It uses cloud computing resources to handle large datasets and train machine learning models efficiently.

- **Key Features**:
  - Collaborative filtering algorithm for music recommendations.
  - Scalable architecture using cloud resources.
  - Efficient handling of user data for personalized suggestions.

- **Technologies Used**:
  - Python
  - Apache Spark
  - AWS EC2 for cloud resources
  - Jupyter Notebooks for development and visualization
  
- **How to Run**:
  1. Clone the repository:
     ```bash
     git clone https://github.com/Hamid-Rezaei/Music-Recommender.git
     ```
  2. Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```
  3. Run the Jupyter notebook or Python script to train the model:
     ```bash
     jupyter notebook Music_Recommender.ipynb
     ```

### 2. Search Movie
This project provides a cloud-based movie search engine. It leverages a distributed architecture to handle large datasets of movie information, allowing users to search for movies by title, genre, and year.

- **Key Features**:
  - Fast and efficient search functionality.
  - Cloud-based deployment for high scalability.
  - Support for various search filters (title, genre, etc.).

- **Technologies Used**:
  - Python
  - Elasticsearch for search indexing
  - Flask for the web interface
  - Docker for containerization
  - Kubernetes for orchestration

- **How to Run**:
  1. Clone the repository:
     ```bash
     git clone https://github.com/Hamid-Rezaei/Search-Movie.git
     ```
  2. Build and run the Docker container:
     ```bash
     docker-compose up
     ```
  3. Access the web app at `http://localhost:5000` and search for your favorite movies!

### 3. Hadoop and Spark Project
This project demonstrates the use of Apache Hadoop and Apache Spark for processing large-scale data. It covers tasks like data ingestion, transformation, and analysis using MapReduce and Spark’s distributed computing model.

- **Key Features**:
  - Distributed data processing using Hadoop's MapReduce.
  - In-memory data analysis using Apache Spark.
  - Integration with HDFS (Hadoop Distributed File System) for scalable storage.

- **Technologies Used**:
  - Apache Hadoop
  - Apache Spark
  - HDFS
  - Python/Scala for scripting

- **How to Run**:
  1. Clone the repository:
     ```bash
     git clone https://github.com/Hamid-Rezaei/Hadoop-Spark-Project.git
     ```
  2. Set up Hadoop and Spark locally or on cloud instances (e.g., AWS EMR):
     - Follow the instructions [here](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/ClusterSetup.html) to set up Hadoop.
     - Follow the instructions [here](https://spark.apache.org/docs/latest/cluster-overview.html) to set up Spark.
  3. Submit a job to the Hadoop or Spark cluster:
     ```bash
     spark-submit your_script.py
     ```

