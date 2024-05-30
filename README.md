## End to End ML-Project with DVC, Docker, MLflow Integration and Modular Coding

This repository demonstrates an end-to-end Machine Learning project lifecycle, showcasing modular coding practices with classes and inheritance. It includes the integration of Data Version Control(DVC) for data tracking, MLflow for experiment tracking, and model management, Docker for delivey via images/containerization, airflow for continuous training and organizes the project into a structured folder system for better maintainability and scalability.

### ML project lifecycle
- `Data preparation`: Collection of data, cleaning, Exploring, Feature engineering and transformation.
- `Model training`: Finding suitable machine learning algorithm and training the model. Also, Hyperparameters tuning.
- `Model evaluation`: Evaluation of performance of the model.
- `Deployement`: Deployement of approved model for production.
- `Monitoring and Maintenance`: Regular monitoring and mainteance of the deployed model.
- `Retiring and replacing models`: Replacing existing model if better model comes.

### Project Structure

The project is organized into the following structured folders:

- `src/components`: Contains ml model building methods namely data ingestion, data transformation, model training, and model evaluation objects of the project.
- `src/pipeline`: Contains the machine learning model training and prediction pipeline objects.
- `src/exception`: Exceptions class to track the exceptions.
- `src/logger`: Logging class to track the stages of model building.
- `src/utils`: Contains generic methods useful for model building.
- `dvc`: Data version controlling and reproducibility of experiments.
- `mlruns`: mlflow to track the model artifacts, metrics, params and tags etc.


### Further Reading

- For more information on DVC and its capabilities, refer to the [DVC documentation](https://dvc.org/doc).

- For more information on MLflow and its capabilities, refer to the [MLflow documentation](https://www.mlflow.org/docs/latest/index.html).

- For more information on Docker and its capabilities, refer to the [Docker documentation](https://docs.docker.com/guides/).

- For more information on airflow and its capabilities, refer to the [Airflow documentation](https://airflow.apache.org/docs/apache-airflow/stable/index.html).

#### Thank you



