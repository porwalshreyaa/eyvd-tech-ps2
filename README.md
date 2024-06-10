# Diabetes Too
## Potential Implementation with Azure ML and Power Apps

### Azure Machine Learning

If Azure ML were available, the project would involve the following steps:

1. **Model Training and Deployment:**
   - Train the machine learning models locally and then deploy them to Azure ML.
   - Use Azure ML's model management capabilities to handle versioning and deployment.
   - Expose the trained models as REST APIs using Azure ML's web service feature.

2. **Data Storage and Access:**
   - Store the dataset in Azure Blob Storage.
   - Access the dataset in Azure ML using Azure Blob Storage's integration with Azure ML workspaces.

3. **Automated Machine Learning:**
   - Utilize Azure's Automated Machine Learning (AutoML) to experiment with different models and hyperparameters efficiently.

### Power Apps Integration

If Power Apps were available, the project would involve creating an interactive application:

1. **Custom Connector:**
   - Create a custom connector in Power Apps to connect to the Azure ML REST API.
   - Use the connector to send user input data to the deployed model and retrieve predictions.

2. **App Design:**
   - Design a user-friendly interface in Power Apps for users to input their health data.
   - Display the predicted personas and related insights using Power Apps' visualization components.

3. **Interactive Dashboard:**
   - Build an interactive dashboard in Power Apps to visualize the personas and provide actionable insights.
   - Use Power Apps to create personalized recommendations and health tips based on the predicted personas.

### Running the Project Locally

To run this project locally, follow the instructions provided in the main sections of this README. Ensure you have all dependencies installed and the dataset downloaded.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/porwalshreyaa/eyvd-tech-ps2.git
   cd eyvd-tech-ps2
