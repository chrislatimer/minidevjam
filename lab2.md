# Lab 2 - Traffic Management and Basic Security

This lab builds upon the work we did in [lab 1](lab1.md). In this lab, we will take the pass-through API Proxy that we created in lab 1 and add two new capabilities: a Spike Arrest to throttle traffic and an API Key validation for a very basic layer of security.

Start by opening up the API Proxy editor by clicking on the develop tab:

![Image](images/orders-proxy-trace-tab-4.png)

Once in the API Proxy editor, you can click on the *+Step* button to add a new policy to your API Proxy:

![Image](images/orders-proxy-editor.png)

This will launch a dialog box that you can use to add a number of policies to your API Proxy. In this case, you're going to select the Spike Arrest policy from the list and click on *Add* to attach the poicy to the request pipeline of your API Proxy:

![Image](images/orders-proxy-editor-policies.png)