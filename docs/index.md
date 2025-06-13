# AI Software Template GitOps

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template execution. The associated source component is available for reference in the **Overview** tab. You can find an example of this reference in the following image.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources

A deployment with the below characteristics was made based on input from the AI Software Template.

## Model & Model Server

A [llama.cpp]( https://github.com/redhat-ai-dev/developer-images/tree/main/model-servers/llamacpp_python/0.3.8) model server was deployed to serve the [ibm-granite/granite-3.1-8b-instruct](https://huggingface.co/ibm-granite/granite-3.1-8b-instruct) model.

!!! info

    This model server is available on port 8001!

# Application

The AI Software Template that was executed comes with a sample application. This application will be built from https://github.com/jdubrick-ai/june13-test-2 and stored in [quay.io/jdubrick-ai/june13-test-2](https://quay.io/jdubrick-ai/june13-test-2) and deployed through ArgoCD. 

This sample application is accessible through port 8501.