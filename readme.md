# Creating Envizi PowerBI Report for Social and Governance Metrics

In this article, let us understand about how to capture Social and Governance Metrics in IBM Envizi ESG suite and create the PowerBI Report for the same.


## 1. Enable Social Metrics

To show the Social and Governance Metrics related data in the monthly data set of the Power BI report, you need to enable Social metrics in Organization Settings.

1. Enable Social metrics in Power BI Report in Organization Settings. This can be done by requesting the Product team.

<img src="images/image1.png">

## 2. Create Account Style

We need to create account styles for the Social metrics related data.

Lets create 2 account styles with the below information.

### Account Style 1 : Emp Hires

Lets create an account style called `Emp Hires`. 

This account style helps to keep the Employee Hires details of the organziation. It contains information such as Gender, Qty (Total emp count), Agewise count, Joined, relieved and fired employee count datails.

1. Goto `Admin > Account Style Wizard`

<img src="images/image20.png">

2. Create an account style with the following.

- **Scope :** Social Metrics
- **Data Type :** People - Headcount [Number]
- **Primary Column :** Qty
- **Seconday Columns :** Gender, Age-21-30,	Age-31-40,	Age-41-50,	Joining,	Leaving,	Fired

<img src="images/image21.png">
<img src="images/image22.png">


### Account Style 2 : Modern Slavery

Lets create an account style called `Modern Slavery`. 

This account style helps to keep the Modern Slavery details of the organziation. It contains information such as Forced Labour, Child Labour, Others and Country datails.

1. Create an account style with the following.

- **Scope :** Social Metrics
- **Data Type :** People - Headcount [Number]
- **Primary Column :** Forced Labour
- **Seconday Columns :** Forced Labour, Child Labour, Others and Country

2. You can create the required fields in the account style as like in the below picture.

<img src="images/image23.png">


## 3. Create Accounts

We need to create accounts with the above created Account Styles as like below.
<img src="images/image30.png">
<img src="images/image31.png">

1. Download the below sample files.

- [files/Envizi_SetupConfig_SG_Report.xlsx](./files/Envizi_SetupConfig_SG_Report.xlsx).
- [files/Account_Setup_and_Data_Load-G5-Hires.xlsx](./files/Account_Setup_and_Data_Load-G5-Hires.xlsx).
- [files/Account_Setup_and_Data_Load_G5-Slavery.xlsx](./files/Account_Setup_and_Data_Load_G5-Slavery.xlsx).

2. Make the required changes like Organization column and etc.

3. Upload the file by going to  `Manage > Data files > Upload files` screeen.

<img src="images/image32.png">


## 4. Create Power Report

Once the account styles are created, wait for day for the daily refresh to happen. So that the newly created account styles will get reflected in the Monthly Data Set of the Power BI Report.

The account styles that we have created above would reflect like this in PowerReport after a day.

<img src="images/image40.png">


1. Create Social and Goverance power report as like below.

<img src="images/image41.png">
<img src="images/image42.png">
<img src="images/image43.png">

You can refer this for detailed explanation of how to create Power Report in Envizi. https://github.com/GandhiCloudLab/envizi-create-custom-power-report