# Fundamentals of Azure Exercise Answers
For this excerise you will need: 
- Azure Tenant
- Azure Active Directory 
- P2 Azure Active Directory License
## Objectives 
- Create a user in Azure Active Directory 
- Update the user's information 
- Create a dynamic security group 
- Create and test a conditional access policy 
## How to create a user in Azure Active Directory (AAD)
The first step is to navigate to your [Azure Portal](portal.azure.com) to your Azure Active Directory. 
Click here to access the User tab of AAD. 
![Image](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/AADUserSnip.JPG)
After this click on the **New user** on the top bar and fill-out the required information. 
![New User](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/AADNewUser.JPG)
### How to Add the User's City
To add a user's city or edit their information. Go back to your user page, find the user you plan on editting and click on edit. 
![Add city](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Add_City.JPG)
After editing the user information click on save. It should now save the updated information. 

## How to Create a Dynamic Group in Azure Active Directory (AAD)
Navigate back to the AAD homepage reach the Group Tab. 
![Group Tab](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Navigate_to_groups.JPG)
After navigating to the group page, click on **New Group** on the tabs on the top. 
![Create New Group](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Create_new_group.JPG)
Fill in the information regarding your security group in the boxes. Make sure to change the membership type to: **Dynamic User**
![Dynamic User](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Change_to_dynamic_group.JPG)
Next click on **Edit dynamic query**
![Dynamic Query](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Create_rule.JPG)
Create the rule by using the drop down to click the properties that you would like to apply to the dynamic security group.
![Rule syntax](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Rule_syntax.JPG)
Hit Save and navigate back to the previous page and click on **Create**. 

After a few minutes, you should see your newly created user in this Dynamic Security Group. 
![Group Membership](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/group_membership.JPG)
## How to Create and Test a Conditional Access Policy
In the search bar look up **Azure AD Conditional Access**. It should appear before you even finish typing out the words.
![Navigate to conditional access policy](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Conditional_Access.JPG)
Once we get to the conditional access page, navigate to the **Named Locations** tab. 
![Named Locations](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Named_locations.JPG)
On the top bar select **Countries Location**. Look up the **United States** in the **search countries** bar. 
![Countries Locations](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Country_locations.JPG)
![Selected Countries Locations](https://github.com/aillarionov-hsl/Fundamentals-of-Azure-Exercise-Files/blob/AzureAD/Reference_Images/Allowed_Countries.JPG)
After that click create and navigate to the policy tab on the left-hand bar. 
