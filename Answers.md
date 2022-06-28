# Fundamentals of Azure
## Security and Compliance
## Objectives 
- [Create a management group](Answers.md#how-to-create-a-management-group)
- [Move a subscription to the management group](Answers.md#how-to-move-a-subscription-to-the-management-group) 
- [Assign an Azure Policy at the management group level](Answers.md#how-to-assign-an-azure-policy) 
- [Test the Azure policy](Answers.md#test-the-azure-policy) 
  
Message me if you are having issues accessing one. 
## Exercise:  
### How to create a management group
  Navigate to the management group page by searching **Management Groups** in the search bar: 

  ![Mg Group](Reference_images/Create_mg.png)

  Click on create: 
  ![Create MG](Reference_images/click_Create_mg.png)

  Fill in the boxes then click on submit 
  ![Create test mg](Reference_images/create_mg_test.png)

###  How to move a subscription to the management group 
While still on the management group page, click the three dots next to the subscription that you want to move:    

![Move sub](Reference_images/move_sub.png)  

![Move sub to mg](Reference_images/move_sub_to_mg.png)
Afterwards make sure the "New Parent Management group" is the newly created management group then hit save. 

![Moved sub](Reference_images/moved_sub.png) 
### How to assign an Azure Policy 
Navigate to the policy page by search **Policy** in the search bar: 

![Azure policy](Reference_images/policy.png)

Next hit **Assignments** on the left bar

![Assignments](Reference_images/Assignments.png)

Click on **Assign policy**

![assign policy](Reference_images/assign_policy.png)
Make sure the scope is assigned at the management group level
    - Click on the three dots next to scope 
  ![scope](Reference_images/scope.png)

  Next click on the three dots next to **Policy definition**. In the search bar, look for "Add a tag to resource groups" 
  ![Select Policy](Reference_images/select_policy.png)

  Click next to fill in the parameters 
  ![Parameters](Reference_images/parameters.png)

  Keep hitting next, create a non-compliance message if you'd like, then review and create. 
### Test the Azure Policy
    Test the newly created Azure policy on a resource group. You should see the newly created resource group with the parameters from the previous task. 
#### How to Create a Resource Group
  - Click on the hamburger button in the upper left-hand corner of the screen 
  
    ![Resource Group](Reference_images/Resource_Group.png)
 
  - Click on Create 
    
    ![Create](Reference_images/Create_RG.png)
  - Fill out the boxes then click create
   
   ![RG Info](Reference_images/rg_created.png)
   
  #### **DO NOT FILL OUT THE TAG TAB**  
   - Navigate back to your newly created resource group and you should see the tags
  ![Tags on rg](Reference_images/rg_test.png)
