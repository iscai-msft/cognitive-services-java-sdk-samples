---
services: cognitive-services, bing-visual-search
platforms: java
author: milismsft
---

# Bing Visual Search SDK Sample ##

Sample [code](https://github.com/Azure-Samples/cognitive-services-java-sdk-samples/blob/master/Search/BingVisualSearch/src/main/java/com/microsoft/azure/cognitiveservices/search/visualsearch/samples/BingVisualSearchSample.java) for searching images using Bing Visual Search, an Azure Cognitive Service.
- Make sure to use S9 pricing tier of Bing Search V7 API to use Visual Search API.
- Make sure to add system environment variable AZURE_BING_SAMPLES_API_KEY based on your OS, then reopen the command prompt or your IDE. If not, you may get an API key not found exception.
- Search with a binary of dog image.
- Search with a binary of dog image using crop area.
- Search with an url of dog image.
- Search with an image insights token using crop area.
- Search with an url of dog image using crop area.

## Features

This project framework provides examples for the **Bing Visual Search SDK** for the [Visual Search API](https://azure.microsoft.com/en-us/services/cognitive-services/)

## Getting Started

### Prerequisites

- A cognitive services API key with which to authenticate the SDK's calls. [Sign up here](https://azure.microsoft.com/en-us/services/cognitive-services/directory/) by navigating to the **Search** services and acquiring an API key. You can get a trial key for **free** which will expire after 30 days.
- Maven

### Quickstart

To get these samples running locally, simply get the pre-requisites above, then:

1. git clone https://github.com/Azure-Samples/cognitive-services-java-sdk-samples.git
2. cd cognitive-services-java-sdk-samples/Search/BingVisualSearch
3. set env variable AZURE_BING_SAMPLES_API_KEY to your cognitive services API key.
4. mvn compile exec:java

## More information ##

[Bing Visual Search Documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/bing-visual-search/)
[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.