## Test Your Application


### 1. Create Event Subscription

1. Log in to your SAP S/4HANA as the business user and create a Purchase Requisition.   
    
    <p><img src="./images/01.png"></p>

2. Choose **Manage Purchase Requisitions**.
    
    <p><img src="./images/02.png"></p>

3. Choose **Create** to create Purchase Requisition.

    <p><img src="./images/03.png"></p>

4. Enter all the required information and choose **Create**.

    <p><img src="./images/04.png"></p>

    Purchase Requisition is created.
    
    <p><img src="./images/05.png"></p>

    This purchase requisition event from SAP S/4HANA is published to SAP Event Mesh and then to Azure Event Grid. With the integration setup and deployment of the Azure function, you will receive email notification as shown below.

    <p><img src="./images/06.png"></p>

Congratulations! You have completed the end-to-end event based integration SAP S/4HANA.