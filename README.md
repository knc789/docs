# Creating a Segment
Segments allow you to group you Marketing Campaigns contacts together in logical email groups based on data that you have stored on that contact. For example, you can use segments and custom contact fields to dynamically send a marketing promotion to all of the females or males on your list, to everyone in a certain city or region, or based on how they’ve engaged with their emails previously.  

> ### You can create up to 100 segments.

## Before you begin

Set up [custom fields](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/custom_fields.html) in your contacts for the categories that you want to organize your segments. 

## Creating a basic segment

To set up a segment to try to lure back customers who have been active in the past, but haven’t interacted with an Email Marketing Campaign lately:

1. In [Contacts](https://sendgrid.com/marketing_campaigns/contacts), click the **Add List or Segment** button, and select the **New Segment** option.  
![](https://media.giphy.com/media/FYEG95biIwIY8/giphy.gif)
2. Select the **Segmentation** tab. From the first drop-down, select an existing list of contacts to segment, and in the second field, give your new segment a name.
3. Choose the condition: _**Last Opened**_ and the criteria: _**is before**_, and select a date that you want to use as your base for customers who haven’t interacted in a while.
4. Click **Save**.  
![](https://media.giphy.com/media/t8y7Pdd5jPZq8/giphy.gif)

## Creating a custom segment

To create an email segment to fit your own needs:

1. Repeat steps 1 and 2 from above. 
2. Select one of the conditions based on default contact fields (_**First Name**_, _**Last Name**_, _**Email**_, _**Date Added**_, _**Last Updated**_, _**Last Emailed**_, _**Last Clicked**_, _**Last Opened**_, _**Engagement: Opens**_, or _**Engagement: Clicks**_), or select a condition based on one of your custom fields.
3. Based on the selected condition, choose operators to narrow your segment further. Different operators show up based on the condition you select.
  - **Text field operators** - Preset text field conditions include First Name, Last Name, and email. Custom text field conditions could include things like _**Location**_, _**Region**_, _**Past Items Ordered**_, and _**Order Frequency**_. Frequent text operators are _**is**_, _**is not**_, and _**contains word**_.
  - **Date field operators** – Preset date fields include _**Date Added**_, _**Last Updated**_, _**Last Emailed**_, _**Last Clicked**_, _**Last Opened**_. Custom date fields could include _**Last Ordered**_. Frequent date operators are _**is**_, _**is not**_, _**is before**_, _**is after**_, and _**is within**_.
  - **Number field operators** – There are no preset number fields. Custom number fields could be _**Age**_, _**Number of Orders**_, or _**Amount Spent**_. Frequent number operators are _**<**_, _**>**_, or _**=**_.
  - **Engagement field operators** – These are preset fields that you can use to sort by how people engage with your previous Marketing Campaigns. The preset fields are _**Engagement: Opens**_, and _**Engagement: Clicks**_. The possible operators are _**Clicked**_ and _**Not Clicked**_, and _**Opened**_ and _**Not Opened**_. Examples:
  
   > **Location is Denver** – target people in a specific location
  
   > **Past Items Ordered contains word dumbbell** – target people who have bought a specific item before
  
   > **Last Opened is before 01/01/2017** – target people who haven’t looked at your emails in a while
  
   > **Date Added is before 01/01/2015** – reward longtime customers
  
   > **Age < 30** – target people who are a particular age, or older or younger than a specific age
  
   > **Amount spent > 500** – target low or high spenders
   > **Engagement: Clicks Clicked** – try to lure people who are not clicking in  your previous emails, or reward individuals who are frequent clickers
4. Optionally, select additional conditions to add to the segment. As you add conditions, you will be able to select _**AND**_ or _**OR**_ as options, where _**AND**_ indicates both conditions are required and _**OR**_ indicates either condition works.
5. Click **Save**.

> ### You can add up to 15 different conditions per segment.
