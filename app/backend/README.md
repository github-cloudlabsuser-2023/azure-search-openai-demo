# Backend Application for Azure Search OpenAI Demo

This README provides an overview and setup instructions for the backend application of the Azure Search OpenAI Demo project. The backend is implemented in Python and integrates various Azure services with OpenAI to provide a rich chat experience based on enterprise data.

## Overview

The backend application serves as the core logic layer that interacts with Azure Cognitive Services, Azure Storage, and OpenAI. It handles requests from the frontend, processes them using the configured Azure services and OpenAI, and returns the responses to the user.

## Features

- Integration with Azure Cognitive Search for searching documents.
- Use of Azure Blob Storage and Azure Data Lake Storage for document storage and retrieval.
- Speech synthesis and recognition via Azure Cognitive Services.
- Authentication and authorization support for secure access.
- OpenAI integration for generating responses based on the retrieved documents.

## Prerequisites

- Python 3.8 or higher
- Azure subscription
- Azure Cognitive Services account
- Azure Storage account
- OpenAI API key

## Setup

1. **Clone the repository**:

    ```sh
    git clone https://github.com/azure/azure-search-openai-demo.git
    cd azure-search-openai-demo/app/backend
    ```

2. **Install dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

3. **Configure environment variables**:

    Copy the `.env.example` file to a new file named `.env` and fill in the values for your Azure services and OpenAI API key.

4. **Run the application**:

    ```sh
    python app.py
    ```

## Configuration

The application can be configured using environment variables. Refer to the [Environment Variables Reference](../../../../c:/Users/azureuser/azure-search-openai-demo/samples/document-security/README.md#environment-variables-reference) for details.

## Additional Documentation

For more detailed instructions on setting up the project, including configuring login and access control or setting up private endpoints, consult the [main README](../../../../c:/Users/azureuser/azure-search-openai-demo/README.md) and the [additional documentation](../../../../c:/Users/azureuser/azure-search-openai-demo/docs/README.md).

## Contributing

Contributions are welcome! Please read the [contributing guide](../../../../c:/Users/azureuser/azure-search-openai-demo/CONTRIBUTING.md) for guidelines on how to contribute to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](../../../../c:/Users/azureuser/azure-search-openai-demo/LICENSE) file for details.