---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Servicebus
- platforms: java
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

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-with-claims-based-authorization.git

    cd service-bus-java-manage-with-claims-based-authorization

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.