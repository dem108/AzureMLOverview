# AzureMLOverview
- 4 hour overview of Azure Machine Learning
- Target audience: working knowledge of statistics, machine learning, and Python REQUIRED
- Includes a quick start hands-on lab

## Pre-requisite
- Create personal Microsoft account ([create one here](https://outlook.live.com/owa/?nlp=1&signup=1)), and gain access to an Azure subscription by doing the following:
    - (Option 1) Login [Azure Portal](https://portal.azure.com/) with that account, and continue registration for free credit. You will need to register your credit card to continue. This is good if you want to continue using the resources you've created.
    - (Option 2) Share your account (email address) with the instructor. The instructor will add you in an existing subscription for your temporary usage during the session.

- Get familiar with the basic [Azure AI platform overview](https://azure.microsoft.com/en-us/overview/ai-platform/).

## Agenda
- 13:00-13:50 What is Azure, and Azure AI Platform. Pre-built AI demos (Intelligent Kiosk and [site](https://azure.microsoft.com/en-us/services/cognitive-services/)).
- 14:00-14:50 Microsoft approach to Custom AI
    - Solution portfolio and [reference architecture](https://github.com/dem108/AMLWorkshop-IotEdge-DevOps/blob/master/doc/decks/Microsoft%20AI%20Architecture%20one-slider-EN-v20190513.pdf).
    - Sample case using Pre-built AI and Custom AI together: [MCW-Cognitive-services-and-deep-learning](https://github.com/microsoft/MCW-Cognitive-services-and-deep-learning)
      - More samples at [MCW](https://microsoftcloudworkshop.com/)
    - Real world case studies
- 15:00-16:50 Experience Azure AI: Azure Machine Learning service
    - Check hands-on environment
      - Choose right directory/tenant, subscription, confirm permission
      - Under the assigned resource group, create Azure ML service Workspace `aml-service-project-xx`
    - Concepts ([Level 200](https://github.com/dem108/AzureMLOverview/blob/master/doc/decks/Azure%20Machine%20Learning%20service%20-%20L200%20v20181205.pdf), [Level 300](https://github.com/dem108/AzureMLOverview/blob/master/doc/decks/Azure%20Machine%20Learning%20service%20-%20L300%20v20181205.pdf))
    - Hands-on: Use [Azure Notebooks](https://notebooks.azure.com/) for free, import [Sample](https://github.com/Azure/MachineLearningNotebooks/), and train some models
        - Authenticate, run and track the experiments using Jupyter Widget or Portal
    - Automated machine learning
        - [Concept](https://docs.microsoft.com/en-us/azure/machine-learning/service/concept-automated-ml)
        - Demo: sample run seen from Portal
        - Hands-on: Automated ML with [Portal](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-create-portal-experiments) (use Azure ML Compute, NYC Taxi tip regression sample)
        - Hands-on: Automated ML with [SDK](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-configure-auto-train)
    - Demo: Deploying the services
    - Demo: [MLOps](https://docs.microsoft.com/en-us/azure/machine-learning/service/concept-model-management-and-deployment)
- Questions and answers

## Instructor guide
- Receive attendees' Microsoft accounts
- Create a blob storage/container, upload a sample data (leverage public dataset if needed) to the container, add attendees to the access control (needed for Portal based automated machine learning lab)
    - For example, you can use NYC Taxi data like [this](https://docs.microsoft.com/en-us/azure/open-datasets/tutorial-opendatasets-automl).

