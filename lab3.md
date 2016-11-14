# Lab 3: API Publishing and Consumption

This lab builds on the work you did in [lab 1](lab1.md) and [lab 2](lab2.md). In this lab, we will look at how you can grant access to the API you secured in lab 2 by using the Verify API Key policy.

To start, open the Publish menu in the left sidebar:

![Image](images/orders-publish-1.png)

Once that expands, select the API Products option:

![Image](images/orders-publish-2.png)

This will take you to the API Products page. If you have API Products already configured in your organization you will see a list of them here. Otherwise, you may see a page encouraging you to set one up. API Products are the mechanism within Apigee Edge that allow you to bundle APIs so that developers can consume them. To see how this works, start by selecting the *+API Product* button:

![Image](images/orders-product-1.png)

This will navigate you to a form where you can input information about your API Product. Start by specifying the Product Details as shown in the following screen capture:

![Image](images/orders-product-2.png)

Then scroll down to the Resources section and fill that out as shown:

![Image](images/orders-product-3.png)

Click on the Save button to save your API Product. Once saved, it will appear in the list of API Products:

![Image](images/orders-product-4.png)

You now have an API Product created, but no developers or applications who can use the product. To create a new developer, we'll navigate to the Developer management view by clicking on the *Developers* option in the left side nav bar:

![Image](images/orders-developer-1.png)

This will take you to the developer management page. Click on the *+Developer* button to create a new developer:

![Image](images/orders-developer-2.png)

When the new developer dialog appears, enter in your information to add yourself as a developer:

![Image](images/orders-developer-3.png)

After you save, you'll see yourself listed as a developer in your organization. In Apigee, API Keys are not assigned to a specific developer, but to a particular application which belongs to a specific developer. To obtain an API Key, we'll now need to create an application. Start by selecting the Apps option in the left side nav bar. 

![Image](images/orders-app-1.png)


