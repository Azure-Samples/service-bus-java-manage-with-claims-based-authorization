---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Servicebus
  platforms: java
---

# Getting Started with Servicebus - Service Bus With Claim Based Authorization - in Java #


  Azure Service Bus basic scenario sample.
  - Create namespace with a queue and a topic
  - Create 2 subscriptions for topic using different methods.
  - Create send authorization rule for queue.
  - Create send and listener authorization rule for Topic.
  - Get the keys from authorization rule to connect to queue.
  - Send a "Hello" message to queue using Data plan sdk for Service Bus.
  - Send a "Hello" message to topic using Data plan sdk for Service Bus.
  - Delete namespace
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/master/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-with-claims-based-authorization.git

    cd service-bus-java-manage-with-claims-based-authorization

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.