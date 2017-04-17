# Creating a Segment
Segments allow you to group you Marketing Campaigns contacts together in logical email groups based on data that you have stored on that contact. For example, you can use segments and custom contact fields to dynamically send a marketing promotion to all of the females or males on your list, to everyone in a certain city or region, or based on how they’ve engaged with their emails previously.  

> You can create up to 100 segments.

## Before you begin

Set up (custom fields)[ https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/custom_fields.html]  in your contacts for the categories that you want to organize your segments. 

## Creating a basic segment

To set up a segment to try to lure back customers who have been active in the past, but haven’t interacted with an Email Marketing Campaign lately:

1. In Contacts, click the **Add List or Segment** button, and select the **New Segment** option
2. Select the **Segmentation** tab. From the first drop-down, select an existing list of contacts to segment, and in the second field, give your new segment a name.
3. Choose the condition: _Last Opened_ and the criteria: _is before_, and select a date that you want to use as your base for customers who haven’t interacted in a while.
4. Click “Save”

## Creating a custom segment

To create an email segment to fit your own needs:

1.    Repeat steps 1 and 2 from above. 
2.    Select one of the conditions based on default contact fields (_First Name_, Last Name_, _Email_, _Date Added_, _Last Updated_, _Last Emailed_, _Last Clicked_, _Last Opened_, _Engagement: Opens_, or _Engagement: Clicks_), or select a condition based on one of your custom fields.
3.    Based on the selected condition, choose operators to narrow your segment further. Different operators show up based on the condition you select.
- Text field operators - Preset text field conditions include First Name, Last Name, and email. Custom text field conditions could include things like Location, Region, Past Items Ordered, and Order Frequency. Frequent text operators are is, is not, and contains word. Examples:
    - Location is Denver – target people in a specific location
    - Order Frequency is not often – target people with different order frequency
    - Past Items Ordered contains word dumbbell – target people who have bought a specific item before
- Date field operators – Preset date fields include Last Updated, Last Emailed, Last Clicked, and Last Opened. Custom date fields could include Date Joined, or Last Ordered. Frequent date operators are is, is not, is before, is after, and is within. Examples:
    - Last Opened is before 01/01/2017 – target people who haven’t looked at your emails in a while
    - Date Joined is before 01/01/2015 – reward longtime customers
- Number field operators – There are no preset number fields. Custom number fields could be Age, Number of Orders, or Amount Spent. Frequent number operators are <, >, or =. Examples:
    - Age < 30 – target people who are a particular age, or older or younger than a specific age
    - Amount spent > 500 – target low or high spenders
    - Number of Orders < 100 – target people with different past order thresholds 
- Engagement field operators – These are preset fields that you can use to sort by how people engage with your previous Marketing Campaigns. The preset fields are Engagement: Opens, and Engagement: Clicks. The possible operators are Clicked and Not Clicked, and Opened and Not Opened. Examples:
    - Engagement: Opens Not Opened – try to lure people who are not opening previous emails, or reward individuals who are opening previous emails
    - Engagement: Clicks Clicked – try to lure people who are not clicking in  your previous emails, or reward individuals who are frequent clickers
4.    Optionally, select additional conditions to add to the segment. As you add conditions, you will be able to select AND or OR as options, where AND indicates both conditions are required and OR indicates either condition will work.
5.    Click “Save”.

> You can add up to 15 different conditions per segment.
