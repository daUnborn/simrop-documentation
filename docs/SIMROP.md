# 1.0 Introduction

SIMROP also known as SIM Registration Operation Portal is a portal designed to manage kit assignment and other related activities. This portal can be used to manage kit assignment (map a kit to an agent), raise and resolve issues (issue log), log return B2B and approve/reject return B2B. Likewise, this portal provides stakeholders’ dashboards and reports for easy tracking and monitoring. 

> A primary goal of SIMROP is to enable flexibility of managing users and devices by Admins without coming in contact with the devices or users. Also, SIMROP ensures that most manual process are automated to ensure efficiency.

You can have visit [SIMROP](https://sraa.mtnnigeria.net/simrop) here.

The SIMROP portal has three categories of users, they are the:

- **Dealers:** These are dealers/partners with MTN Nigeria. On the SIMROP application, dealers are able to map devices to agents, log user and kit related issues, view SIMROP Dashboard, return devices to B2B and request for agent account creation.
- **Admins:** These are SIMROP admin. They receive notifications as a result of a request from dealers and get to act on the request. These group of users can view details of kit-agent mapping, act on B2B requests, resolve related issues and view Dashboard.

## 2.0 SIMROP PORTAL

### 2.1 Access to SIMROP
The new SIMROP can be accessed from http://sraa.mtnnigeria.net/ from a public network or from the MTN Domain. SIMROP can be accessed from any browser. The browser must have JavaScript enabled to enable SIMROP to run seamlessly. Below is a view of the landing page when a user visits the URL above

### 2.2 Login

Before a user is able to login to SIMROP, an account must be created for the user. Actions and operations on SIMROP are highly role based. This means that a user is able to carry out actions on SIMROP based on the role assigned to the user. 
Account creation and role assignment to account are handled by CAC Helpdesk or Seamfix support. CAC Helpdesk can be reached on cacHelpDesk@mtn.com while Seamfix Support can be reached via email also on #seamfixsupport.NG@mtn.com

For a successful login, the user is expected to;
- Enter a valid username (email address)
- Enter a valid password
- Click on the Submit button as shown in the figure above

### 2.3	Views
There are currently 3 views on SIMROP access to these views is dependent on the role assigned to the user. Below is a breakdown of the views;
- **Dealer View** – From this view, dealers are able to carry out all dealer related activities like; Agent Enrollment, Issue Log, retrieve devices, return devices to B2B and view dashboard. Note that dealers are able to view kits and carry out operations on kits assigned to them.
- **Admin View** – From this view, an Admin is able to carry out admin operations based on a request from dealers. Operations from this view include; retrieval of Agent Enrollment details, approval of Return to B2B requests, issue resolution, agent account creation, view dashboard


### 2.4	Password
SIMROP users have the ability to change their password at will. Password change or reset could be as a result of forgetting his/her password or a user wanting to change his/her password to something else.

To change a password, the user should do the following;
  - Access the login view
  - Click on the **Forgot Password** link as shown in the figure below

 
> ### Figure 2
> Image with forgot Password Link goes here

  - Enter the username/email to the account on the preceding screen as shown in Figure 3 and click on Continue
  -	If the provided username/email is not valid, an error message is returned as shown in Figure 4

 
> ### Figure 3
> Provide Username for Password change/reset
 
> ### Figure 4
> Invalid Username Error

  - Enter the OTP sent to the phone number associated with the account provided as shown in Figure 5. Note that the last 4 digits of the number that would receive the MSISDN would be displayed on the screen as highlighted in Figure 5. Also, note that the OTP sent to the user’s phone number expires after a configured amount of time
 
> ### Figure 5
> OTP validation for password change/reset

  - On successful validation of the OTP, the user would be prompted to provide a new password, confirm the provided password and click on Continue as shown in Figure 6. Note: The new password must conform to the configured password policy

 
> ### Figure 6
> Provide New Password

  - On successful validation, the new password is saved and the user is required to login with the new password

## 3.0 Dealer-Community

The dealer view is the view accessible by dealers on SIMROP. For a dealer to have access to view, the dealer must request for the creation of a dealer account and the required role assigned to the dealer account. The dealer view has the following;

### 3.1	Dashboard
The dashboard has the analytics (in form of counts, graphs and charts) of the logged in dealer’s: Kit activities, agent activities and SIMROP Operations. Also, the dashboard is the landing page for all dealers on SIMROP. Find the screenshot of the dealer dashboard Figure 1;

<!-- theme: danger --> 

> ##### Figure 1
> Dealer Dashboard 

Below is a list of analytics found on the dealer dashboard;
  - **Kit Status:** A pie chart that displays a count of kits based on their status (whitelisted/blacklisted). The dealer can view more details by clicking on a section of the pie chart. The corresponding view shows a list of the devices that make up the count on the selected section.
  - **Monthly Kit Activity:** This chart shows the count of unique devices that have carried out at least one registration from the beginning of the month till the time dashboard was loaded
  - **Total Agents:** This analytic shows a count of agents mapped to the dealer who is logged in.
  - **Today’s New Registration:** This analytic shows a count of new registration carried out by devices mapped to a logged dealer.
  - **Today’s Re-Registration:** This analytic shows a count of new registration carried out by devices mapped to a logged dealer.
  - **Today’s Registration:** This analytic shows a count of registrations carried out by devices mapped to the logged dealer. The count shown is the dealer’s gross connection for the day the Dashboard was loaded.
  - **Agent Status:** This is a pie chart that displays a distribution of active and inactive agents mapped to the logged in the dealer. 
  - **Kit Assignment Status:** A pie chart that displays a distribution of agents mapped to a device against agents that have not been mapped to a device. At a glance, the dealer is able to know the number of agents that are yet to be mapped to a device.
  - **Account Status:** A pie chart that tells a dealer the count of agents that their accounts are locked and the count of agents that their accounts are not locked. This would enable the dealer to know the number of locked out agents.
  - **B2B Request:** On the dashboard, a dealer is able to know the overall status of B2B requests on SIMROP. At a glance, a dealer is able to know the count of Approved B2B requests, pending B2B requests and approved B2B requests.
  - **Issue Log:** On the dashboard, a dealer is able to know the overall status of Issue Log requests on SIMROP. At a glance, a dealer is able to know the count of pending issues and the count of resolved issues on SIMROP
  - **Daily Kit Activity:** From this pie chart, the logged in the dealer is able to view at a glance the count of devices that are active or inactive within his/her domain for that day. The pie chart shows the count of unique active devices that are mapped to the dealer.
  - **Registration Overview: **On the dealer dashboard, the dealer is able to view the count of registrations carried out by devices mapped to him/her. The dealer has the option of generating weekly, daily, monthly or yearly registration overview from the dealer dashboard. Also, the dealer can generate daily overview within a selected date range.


### 3.2	VTU Management
VTU Management is a module that enables a dealer to carry out VTU related operations. The operations available to a dealer on the VTU Management module include;

  - VTU Agent On-Boarding Request
  - View VTU Dealer Dashboard
  - View Transaction History

VTU Management Module can be located on the menu as shown in Figure 1 below;

<!-- theme: danger --> 
> ##### Figure 2
> VTU Management Menu

#### **3.2.1		VTU On-Boarding Request**
Also, from the VTU Management module, the dealer can access the VTU On-Boarding Request view. From this view, as shown in VTU 8, a dealer is able to:

On-Board an agent for VTU on BioSmat
Deactivate an already active (and approved) agent
Activate an already inactive (and approved) agent


**3.2.1.1	On-Board Agent**
To onboard an agent for VTU (airtime/data), the dealer should;

  - Click on **VTU Management > Agent Onboarding** Request as shown in Figure 2
  - Click on the On-Board Agent button as shown in Figure 3
  - Enter the required details on the corresponding view as shown in Figure 4
  - Client on the Save button at the end of the page as shown in Figure 4.

The actions above save the record an notifies the configured users for approval

<!-- theme: danger --> 
> ##### Figure 3
> VTU Agent On-Boarding

<!-- theme: danger -->
> ##### Figure 4
> Save VTU On-Boarding Request

**3.2.1.2	Bulk Agent On-Boarding**

A dealer can choose to onboard multiple agents all at once. This feature ensures that a dealer is able to onboard several agents in a single operation. To carry out a multiple on-boarding of agents, a dealer should;

  - Access the VTU Agent On-Boarding view and click on Bulk Upload as shown in Figure 3
  - Click on the Download Template link (as shown in Figure 5) to download an complete the excel template
  - Upload the completed excel template
  - Click on the Upload button as shown in Figure 5

<!-- theme: danger --> 
> ##### Figure 5
> Bulk Agent On-Boarding

**3.2.1.3	View Agent On-Boarding Details**

A dealer can view the details of an already created agent on-boarding request. To view details of an agent on-boarding request, the dealer should
Access the VTU On-Boarding Request view as shown in Figure 3
Click on the Action button on the desired record
Click on View Details as shown in Figure 6 which displays the details of the agent on-boarding request as shown in Figure 7

<!-- theme: danger --> 
> ##### Figure 6
> Agent On-Boarding (View Details)
<!-- theme: danger --> 
> ##### Figure 7
> Agent On-Boarding Details

**3.2.1.4	Activate/Deactivate an Agent**
To activate/deactivate an agent, the dealer should;
  - Access the VTU On-Boarding Request view as shown in Figure 3
  - Click on the action button on the desired record to be activated/deactivated
  - Click on Activate or Deactivate to either activate or deactivate the agent as shown in Figure 8
  - Click on View Details to confirm the Activation Status of an Agent On-boarding request

<!-- theme: danger --> 
> ##### Figure 8
> Activate/Deactivate VTU

<!-- theme: danger --> 
> ##### Figure 9
> Agent Onboarind Activation Status

#### 3.2.2		VTU Dealer Dashboard
There is a VTU dealer dashboard that is available to dealers on SIMROP. This dashboard has an overview of all vending done by dealer’s agents. The dashboard comes with charts, counts and table. See a sample of the dealer VTU dashboard in Figure 10
<!-- theme: danger --> 
> ##### Figure 10
> VTU Dealer Dashboard

The dealer dashboard has the following chart with their descriptions;
  - **Total Airtime Amount** – The total airtime amount vend by agents mapped to the dealer
  - **Total Data Amount** – The total data amount vend by agents mapped to the dealer
  - **Successful Transactions** – Count of successful transactions carried out by agents mapped to the dealer
  - **Failed Transactions** – Count of failed transactions carried out by agents mapped to the dealer
  - **Transaction Distribution Airtime & Data** – A bar chart showing a distribution of failed and successful airtime and data vend by agents mapped to the dealer
  - **Transaction Distribution for Data Bundles** – Distribution showing the count of the data types vend by the agents mapped to the dealer
  - **Vending Distribution** – A distribution trend showing transaction of airtime and data in the past one week.

#### 3.2.3		Transaction History
The transaction history enables a dealer to have a visibility of all vending transactions carried out by agents mapped to the dealer. The history is irrespective of if the transaction is failed or successful. The VTU Transaction History for airtime is shown in Figure 11 while Transaction History for data is shown in Figure 12
<!-- theme: danger --> 
> ##### Figure 11
> Airtime transaction History

<!-- theme: danger --> 
> ##### Figure 12
> Data Transaction History

#### 3.2.4		View Details
To view the details of a Transaction History, the dealer should do the following
  - Click on Actions from the Transaction History view
  - Click on View Details as shown in Figure 12
  - The action above displays the details as shown in Figure 13

<!-- theme: danger --> 
> ##### Figure 13
> Transaction History View Details

<!-- theme: danger --> 
> ##### Figure 14
> View Details

### 3.3	Agent Enrollment
From this view, a dealer is able to assign or map an existing agent or a non-existing agent to a device. During this device-agent mapping operation, the dealer is required to provide other supporting details such as:

  - Dealer Details
  - Outlet details
  - Agent details including AYA, VTU number and ID card
  - Outlet Picture

As stated above, a dealer can enrol an existing agent or a non-existing agent. 

To access the Agent Enrollment view, the dealer should, on successful login, click on the Agent Enrollment menu item on the SIMROP menu as shown in Figure 1 below. This action navigates the dealer to Agent Enrollment landing page as shown in Figure 2 below

<!-- theme: danger --> 
> ##### Figure 1
> Agent Enrolment Menu

<!-- theme: danger -->
> ##### Figure 1
> Agent Enrollment View (Landing Page)

From the Agent Enrollment landing page as shown in Figure 2 above, the dealer is able to know if:

  - The kit is blacklisted or whitelisted
  - If a device marked as damaged, stolen or return
  - If an Agent Enrollment has been approved 

This operation enables the dealers and Admins to maintain a holistic database of devices and the agents that use them. From the device mapping view the dealer can;

  - Create a new Device-Agent mapping (Existing Agents)
  - Create a new Device-Agent mapping (Non-Existing Agents)
  - Search for an existing mapping
  - View Mapping
  - Retrieve Device
  - Make a B2B return request

#### 3.3.1	Create a new Device-Agent mapping (Existing Agents)

To create a new device-agent mapping, a dealer should;

  - Click on the New Kit Assignment button as shown in Figure 2 above
  - Select the Kit to be mapped from the Select Kit drop-down from the Device Tab as shown in Figure 3
  - Select other details as required
  - Click on Next to proceed to the next view
  - Enter the required dealer information as required from the Dealer Tab as shown in Figure 4
  - Click on Next to proceed to the Agent Information Tab
  - Select the agent to be mapped to the device from the Username drop-down as shown in Figure 5
  - Click on Submit to submit information to Admin as shown in Figure 5
  - If there is an existing agent enrollment request that is pending approval for the selected device, the user is notified as shown in the AVE 6.
  - Click on Proceed to proceed or Cancel to stop the Agent Enrollment Request process
  - On successful submission after clicking the Proceed button, the dealer gets a success message as shown in Figure 7

<!-- theme: danger -->
> ##### Figure 3
> Device Information for Mapping

<!-- theme: danger -->
> ##### Figure 4
> Dealer Information for Mapping

<!-- theme: danger -->
> ##### Figure 5
> Agent/Outlet Information for Mapping

<!-- theme: danger -->
> ##### Figure 6
> Agent Enrollment Confirmation Message

<!-- theme: danger -->
> ##### Figure 7
> Agent Enrollment Success Message


#### 3.3.2	Create a new Device-Agent mapping (Non-Existing Agents)

To create a new device-agent mapping for a non-existing agent, a dealer should;

  - Click on the **New Kit Assignment** button on the landing page as shown in Figure 2 above
  - Select the Kit to be mapped from the **Select Kit** drop-down on the **Device Tab** as shown in Figure 3
  - Select other details as required
  - Click on **Next** to proceed to the next view
  - Enter the required dealer information as required from the Dealer Tab as shown in Figure 4
  - Click on Next to proceed to the **Agent Information** view
  - Check the **New User?** Checkbox as shown in Figure 8

The actions above does the following as shown in Figure 9;
  - Disables the username field
  - Enables the following fields: First Name, Surname, Phone Number fields
  - Displays the Gender Field

<!-- theme: success -->
> **Note:** When the dealer enters the agent’s first name and surname, SIMROP Automatically generates a username in the format firstname.lastname@mtnagent.com for the dealer. If the generated name already exists, SIMROP adds a number to the generated username.

  - Enter the other information as required
  - Click on **Submit** to submit information to Admin as shown in Figure 5

    - _If there is an existing agent enrollment request that is pending approval for the selected device, the dealer is notified as shown in the Figure 6._
    - _If the phone number has been used to create an account for an existing agent, the dealer is notified as shown in Figure 10_
- Click on **Proceed** to proceed or **Cancel** to stop the Agent Enrollment Request process
- On successful submission after clicking the **Proceed** button, the dealer gets a success message as shown in Figure 7.

<!-- theme: success -->
> **Note**: After successful creation of Agent Enrollment Request for Non-Existing Agent, Admins are notified for Approval. The account is created after the admins have approved

 
<!-- theme: danger -->
> ##### Figure 8
> Initiate Enrollment for New Users


<!-- theme: danger -->
> ##### Figure 9
> Information for new Agent

 
<!-- theme: danger -->
> ##### Figure 10
> Existing Phone Number notification


#### 3.3.3	Search for existing Agent Enrollment
To search for existing Agent Enrollment, 

- Visit the Agent Enrollment landing page
- Enter the **Kit Tag** or **Device ID** as shown in Figure 11.
- Click on the **Search** button as shown in Figure 11 to display the result of the search based on the search details provided
Or
- Click on **More…** button which displays the list of searches as shown in Figure 11
- Select the desired search criteria from the listed drop-downs as shown in Figure 12
- Click on the **Search** button as shown in Figure 12 to display the result of the search based on the search criteria selected

 
<!-- theme: danger -->
> ##### Figure 11
>Search – Agent Enrolment

 
<!-- theme: danger -->
> ##### Figure 12
>More Search – Agent Enrollment


#### 3.3.4	View Mapping

To view Agent Enrollment, the dealer should;

- Search for the required kit (Refer to 3.3.3)
- Click on the **Actions** button as shown in Figure 13
- Click on **View Details** as shown in Figure 13
- The actions above display the corresponding details of the kits as shown in Figure 14

 
<!-- theme: danger -->
> ##### Figure 13
> – Agent Enrolment – View Details Menu Item

 
<!-- theme: danger -->
> ##### Figure 13
> Agent Enrolment – View Details



#### 3.3.4	Retrieve Device
A dealer is able to retrieve a device from an agent. A retrieved device is automatically blacklisted and cannot be re-assigned to another agent until the device has been whitelisted. To retrieve a device, the dealer should

- Search for the required kit (Refer to 3.3.3)
- Click on the **Actions** Button as shown in Figure 15
- Click on **Retrieve Kit** as shown in Figure 15
- Select the retrieval reason from the **Retrieval Reason** dropdown as shown in Figure 16
- Click on **Retrieve Kit** as shown in Figure 16
- On successful retrieval, the status of the device changes from ***Whitelisted*** to ***Blacklisted***.

<!-- theme: success -->
> **Note:** *Dealer must make sure the device is retrieved from the agent physically before carrying out the retrieval action on SIMROP.*

 
<!-- theme: danger -->
> ##### Figure 15
> Agent Enrolment – Retrieve Kit Menu Item

 
<!-- theme: danger -->
> ##### Figure 16
> Kit Retrieval Dialog


#### 3.3.4	Make a B2B return request
A dealer can also return devices to B2B on SIMROP. When a device is returned to a B2B location, the dealer should notify Admin by making a return to B2B request. To make a return to B2B request on SIMROP, the dealer should

- Search for the required kit (Refer to 3.3.3)
- Click on the **Actions** Button as shown in Figure 17
- Click on **Return to B2B** as shown in Figure 17.
- Select and enter the required details from the **Return to B2B dialog** box
- Enter the **Reason** why the device was returned to B2B as shown in Figure 18 below
- Upload device image 
- Click on the **Send** button

 
<!-- theme: danger -->
> ##### Figure 17
>  Agent Enrollment – Return to B2B Menu Item

 
<!-- theme: danger -->
> ##### Figure 18
> B2B Location, Reason and Image Upload

The action above triggers an email notification to the approvers (based on the roles) who verifies that the device was actually returned to B2B before approving. Approving B2B requests passes through an approval workflow. This means that more than one person can approve based on the approval configuration

Note that devices approved by Admin Helpdesk as returned to B2B are automatically blacklisted and are removed from the list of kits mapped to that dealer.



### 3.4	Issue Log View

On SIMROP, dealers are now able to log all kit and user related issues on SIMROP. This is to enable the seamless tracking of issues to ensure tracking and subsequent closure. All user and kit related issues are assigned an issue ID which can be used for tracking status of an issue. Issues can be logged from 2 separate views;

#### 3.4.1	Kit Related Issues

To log a kit related issues, a dealer is expected to 
- Login successfully to SIMROP
- Click on **Log Issues** menu item. This action would drop down the sub-menu items
- Click on **Kit Issue Log** as shown in Figure 1. This action would bring up the **Kit Issues** landing page as shown in Figure 1

 
<!-- theme: danger -->
> ##### Figure 1
> Kit Issue Log Menu

 
<!-- theme: danger -->
> ##### Figure 2
> Kit Issues Landing Page

From the kit issues landing page, a dealer can carry out the following activities;

- Log Kit Issue
- Search for an existing kit issue
- View Details


**3.4.1.1	Log Kit Issue**

To log a new kit issue, the dealer should;

- Click on Log **Kit Issue** button as shown in Figure 2
- Select the affected kit from the **Kit Tag** drop-down as shown in Figure 3
- Select the issue summary from the **Issue Summary** drop-down as shown in Figure 3
- Enter the description of the issue in the ***Description fiel*d** as shown in figure Figure 3
- Click on **Send**.

The actions above alert the Admin Helpdesk via email for issue resolution


 
<!-- theme: danger -->
> ##### Figure 3
> Log Kit Related Issue

**3.4.1.2	Search for an existing kit issue**
To search for an existing kit issue, a dealer should do either of the following as shown in Figure 2;
- Enter an **Issue ID** or **Kit Tag** and click on Search
- Select an **Issue Summary** and click on **Search**
- Select an **Issue Status**, then, click on **Search**
- Fill in all the fields with desired search criteria, then click on search in order to narrow down the search result

**3.4.1.3	View Details**
On SIMROP, dealers can view details of an already created Kit Issue Log by;

- Searching for an issue as described in 
- Click on the **Action** menu as shown in Figure 4
- Click on **View Details** as shown in Figure 4

 
<!-- theme: danger -->
> ##### Figure 4
> View Details (Issue Log)

The actions above displays the details of the issue logged, resolution message,who resolved the issue and resolution date if the issues have been resolved by Admin Helpdesk. See an example of a resolved kit issue log in Figure 5

 
<!-- theme: danger -->
> ##### Figure 5
> View Logged Issues with Resolution Details

#### 3.4.2	User Related Issues

To log a user related issue, a dealer is expected to 
- Login successfully to SIMROP
- Click on **Log Issues** menu item. This action would drop down the sub-menu items
- Click on **User Issue Log** as shown in Figure 6. This action would bring up the **User Issues** landing page as shown in Figure 7.

 
<!-- theme: danger -->
> ##### Figure 6
> User Issue Log

 
<!-- theme: danger -->
> ##### Figure 7
> User Issues Landing Page

From the user issues landing page, a dealer can carry out the following activities;

1. Log User Issue
2. Search for existing User issue
3. View Details

**3.4.2.1	Log User Issue**

To log a new User issue, the dealer should;

- Click on **Log User Issue** button as shown in Figure 7
- Select the affected user from the **Username** drop-down as shown in Figure 8
- Select the issue summary from the **Issue Summary** drop-down as shown in Figure 8
- Enter the description of the issue in the **Description field** as shown in Figure 8
- Click on **Send**.

The actions above alert the Admin Helpdesk via email for issue resolution


 
<!-- theme: danger -->
> ##### Figure 8
> Log User Related Issue

**3.4.2.2	Search for an existing kit issu**e
To search for an existing user issue, a dealer should do either of the following as shown in figure 7;
•	Enter an **Issue ID** or **Username** and click on **Search**
•	Select an **Issue Summary** and click on **Search**
•	Select an **Issue Status**, then, click on **Search**
•	Fill in all the fields with desired search criteria, then click on search in order to narrow down the search result

**3.4.2.3	View Details**
On SIMROP, dealers can view details of an already created User Issue Log by;

•	Searching for an issue as described in 
•	Click on the Action menu as shown in Figure 9
•	Click on View Details as shown in Figure 9

 
<!-- theme: danger -->
> ##### Figure 9
> View Details (User Issue Log)

The actions above displays the details of the issue logged, resolution message,who resolved the issue and resolution date if the issues have been resolved by Admin Helpdesk. See an example of a resolved user issue log in Figure 10

 
<!-- theme: danger -->
> ##### Figure 10
> View Logged User Issues with Resolution Details

### 3.6	Device Requisition
From this module, a dealer can make a device requisition request. The dealer can only request a specific count of devices to be deployed to a defined area. 

From the module, a dealer can;
- Make a device requisition request
- Edit a requisition request
- View Request

#### 3.6.1		Device Requisition Request
To make a Device Requisition Request, a dealer should;
- Access the Device Requisition Landing page as shown in Figure 1
- Click on the New Device Requisition button
- Complete the form the comes after the action above 
- Click on the Send button as shown in Figure 2

 
<!-- theme: danger -->
> ##### Figure 1
>  Device Requisition Landing Page


 
<!-- theme: danger -->
> ##### Figure 2
> New Requisition Form

#### 3.6.2		View a Request
To view the details of an existing request, the dealer should;
- Navigate to the landing page as shown in Figure 1
- Click on the Action button
- Click on View Details as shown in Figure 3. 
- This action displays the details of the selected device requisition request as shown in Figure 4

<!-- theme: success -->
> **Note**: *The Requisition Details view has other details like the approver’s feedback*

 
<!-- theme: danger -->
> ##### Figure 3
> View Details Action

 
<!-- theme: danger -->
> ##### Figure 4
> Requisition Details View


# CAC Admin Community

The CAC Admin view is a view accessible by CAC Admin or whoever that has the CAC Admin role on SIMROP. For a user to have access to the CAC Admin view, the user must request an account creation and the required role assigned to the user’s account. The dealer view has the following

## Dashboard

The dashboard has the analytics (in the form of graphs and charts) of all the dealer SIM registration and SIMROP activities. By default, the dashboard loads the analytics of all the dealers on SIMROP. However, each dealer’s analytics can be viewed by selecting the dealer from the KYC Dealer drop-down as shown in figure 26. The analytics on the dashboard includes; Kit activities, agent activities, registrations and SIMROP Operations. Also, the dashboard is the landing page for all users with CAC Admin role on SIMROP. Find the screenshot of the dealer dashboard in figure below:

<!-- theme: danger -->
> ##### Figure 1
> CAC Admin Dashboard

Below is a list of analytics found on the dealer dashboard;
- **Kit Status:** A pie chart that displays a count of kits based on their status (whitelisted/blacklisted). CAC Admin can view more details by clicking on a section of the pie chart. The corresponding view shows a list of the devices that make up the count on the selected section.
-	**Monthly Kit Activity:** This chart shows the count of unique devices that have carried out at least one registration from the beginning of the month till the time dashboard was loaded.
-	**Total Agents:** This analytic shows a count of agents on KYC. However, when a dealer is selected from the KYC Dealer drop-down as shown in figure 26, the total agents would be that of the dealer selected from the drop-down.
- **Today’s Registration:** This analytic shows a count of registrations carried all the devices on the KYC ecosystem irrespective of the dealer. To get the count for registrations for a particular dealer, the user is expected to select the desired dealer from the KYC Dealer drop-down. The count shown is the total gross connection for the day the Dashboard was loaded.
-	**Today’s New Registration:** This analytic shows a count of new registration carried out by all the dealers or the selected dealer from the dealer dropdown
-	**Today’s Re-Registration:** This analytic shows a count of new registration carried out by all the dealers or the selected dealer from the dealer dropdown.
-	**Agent Status:** This is a pie chart that displays a distribution of active and inactive agents.
-	**Kit Assignment Status:** A pie chart that displays a distribution of all the agents mapped to a device against agents that have not been mapped to a device cumulatively. At a glance, a CAC admin is able to know the number of agents that are yet to be mapped to a device.
-	**Account Status:** A pie chart that tells a CAC Admin user the count of agents that accounts are locked and the count of agents that their accounts are not locked. This would enable the CAC Admin user to know the number of locked out agents at any given time.
-	**B2B Request:** On the dashboard, a dealer is able to know the overall status of B2B requests on SIMROP. At a glance, a CAC Admin user is able to know the count of Approved B2B requests, pending B2B requests and approved B2B requests.
-	**Issue Log:** On the dashboard, a CAC Admin user is able to know the overall status of Issue Log requests on SIMROP. At a glance, a CAC Admin is able to know the count of pending issues and the count of resolved issues on SIMROP
-	**Kit Activity Overview:** From this pie chart, a CAC Admin is able to view at a glance the count of devices that are active or inactive within his/her domain.
-	**Registration Overview:** On the dealer dashboard, the dealer is able to view the count of registrations carried out by devices mapped to him/her. The CAC Admin user has the option of generating weekly, daily, monthly or yearly registration overview from the CAC Admin dashboard. Also, the CAC Admin user can generate daily overview within a selected date range.
-	**Other Analytics:** A CAC Admin user can also see the following, they allow a CAC Admin user know the high and low performing dealers at a glance: 
    - Top 5 dealers 
    - Top 5 Users 
    - Least 5 Dealers 
    - Least 5 agents 

## Agent Enrollment Approval

From this view, a CAC Admin user is able to view details of Agent Enrollment (for new and existing agents) done by a dealer from the dealer’s view. CAC Admin users are alerted once a user maps a kit.

> ***Note:** Agent Enrollment Approval happens immediately a dealer is able to enrol an agent successfully.*
> *Also, note that there is an approval workflow for Agent Enrollment Request for Non-Existing Agents/Users*

To access the Agent Enrollment view, the CAC Admin User should, on successful login, click on the Agent Enrollment menu item on the SIMROP menu as shown in AGE 1. This action navigates the dealer to Agent Enrollment landing page as shown in AGE 2 below:

<!-- theme: danger -->
> ##### AGE 1
> CAC Admin Menu (Agent Enrollment)

<!-- theme: danger -->
> ##### AGE 2
> CAC Agent Enrollment View (Landing Page)

***Note:** When there is an agent enrollment request from a dealer, the request is automatically approved by the system.*

### Search for existing Agent Enrollment

To search for existing Agent Enrollment, 

Visit the Agent Enrollment landing page
  -	Enter either the device tag of the enrolled device as shown in AGE 3
  -	Click on the Search button as shown in AGE 3 to display the result of the search based on the search details provided

Or
  -	Click on More button as shown in AGE 3
  -	Select the desired search criteria from the listed drop-downs (CAC Admin user can select a dealer from the dealer drop-down)
  -	Click on the Search button as shown in AGE 3 to display the result of the search based on the search criteria selected

<!-- theme: success -->
> ##### AGE 3
> CAC Search & Advanced Search

### View Mapping

To view Agent Enrollment, the dealer should;

-	Search for the required kit (Refer to 4.2.1)
-	Click on the Actions Button as shown in AGE 4
-	Click on View Mapping Details as shown in AGE 4

The actions above display the corresponding details of the kits as shown in AGE 5 below;

<!-- theme: success -->
> ##### AGE 4
> View Mapping Details

<!-- theme: success -->
> ##### AGE 5
> View Mapping Details View

### Approve Agent Enrolment (Non-Existing Agents)

To approve an Agent Enrolment request for non-existing agents, the admin is expected to do the following;

-	Search for the required kit (Refer to 4.2.1)
-	Click on the Actions Button as shown in AGE 4
-	Click on View Mapping Details as shown in AGE 5
-	The action above would display the view as shown in AGE 6
-	Enter the approval reason as shown in AGE 6
-	Click on the APPROVE button as shown AGE 6

If the request is approved, an account is created for the non-existing agent and the new agent account is mapped to the user. Also, a password is sent to the user on successful account creation.

<!-- theme: success -->
> ##### AGE 6
> View Mapping Details view with Approval Panel

## Issue Log View

On SIMROP, CAC Admins are able to resolve all issues logged by a dealer. When an issue is resolved, the dealer is alerted via email. Issue resolution can be done from 2 separate views;

### Kit Related Issues

To access the list of kit related issues logged by a dealer, a CAC Admin is expected to 
-	Login successfully to SIMROP
-	Click on Log Issues menu item. This action would drop down the sub-menu items
-	Click on Kit Issue Log as shown in ILA 1. This action would bring up the Kit Issues landing page as shown in ILA 2.

<!-- theme: success -->
> ##### ILA 1
> Kit Issue Log (CAC Admin)

<!-- theme: success -->
> ##### ILA 2
> Kit Issues Resolution Landing Page

From the kit issues landing page, a CAC Admin user can carry out the following activities;

-	Search for an existing kit issue
-	View Details

#### Search for an existing kit issue

To search for an issue log sent in by a dealer, a CAC Admin user should do either of the following as shown in ILA 2;
-	Enter an Issue ID or Kit Tag and click on Search
-	Select an Issue Summary and click on Search
-	Select an Issue Status, then, click on Search
-	Fill in all the fields with desired search criteria, then click on Search in order to narrow down the search result

#### View Details

On SIMROP, a CAC Admin user can view details an issue logged by a dealer;

•	Searching for an issue as described in 4.3.1.1
•	Click on the Action menu as shown in ILA 3
•	Click on View Details as shown in ILA 3

<!-- theme: success -->
> ##### ILA 3
> View details (Issue Resolution)

The actions above display the details of the issue logged by a dealer as shown in ILA 4.

<!-- theme: success -->
> ##### ILA 4
> Resolve Kit Issue View

#### Resolve Logged Issue

On SIMROP, a CAC Admin user can view details an issue logged by a dealer;

-	Follow the steps in 4.3.1.2
-	Enter Resolution Feedback as shown in ILA 4 
-	Click on Resolve as shown in ILA 4


### User Related Issues (CAC Admin View)

To access the list of user related issues logged by a dealer, a CAC Admin is expected to 
-	Login successfully to SIMROP
-	Click on Log Issues menu item. This action would drop down the sub-menu items
-	Click on User Issue Log as shown in ILA 5. This action would bring up the User Issues landing page as shown in ILA 6

<!-- theme: success -->
> ##### ILA 5
> User Issue Log (CAC Admin)

<!-- theme: success -->
> ##### ILA 6
> User Issues Resolution Landing Page

From the user issues landing page, a CAC Admin user can carry out the following activities;
- Search for existing user issue
-	View Details

#### Search for existing user issue

To search for an issue log sent in by a dealer, a CAC Admin user should do either of the following as shown in ILA 7;
-	Enter an Issue ID or User Tag and click on Search
-	Select an Issue Summary and click on Search
-	Select an Issue Status, then, click on Search
-	Fill in all the fields with desired search criteria, then click on search in order to narrow down the search result

#### View Details

On SIMROP, a CAC Admin user can view details an issue logged by a dealer;
-	Searching for an issue as described in 4.3.2.1
-	Click on the Action menu as shown in ILA 7
-	Click on View Details as shown in ILA 7

<!-- theme: success -->
> ##### ILA 7
> View Details (User Issue Resolution)

<!-- theme: success -->
> ##### ILA 8
> View details (Issue Resolution)

The actions above display the details of the issue logged by a dealer as shown in ILA 9.

<!-- theme: success -->
> ##### ILA 9
> Resolve User Issue View

#### Resolve Logged Issue

On SIMROP, a CAC Admin user can view details an issue logged by a dealer;
-	Follow the steps in 4.3.2.2
-	Enter **Resolution Feedback** as shown in ILA 9 
-	Click on **Resolve** as shown in ILA 9

## B2B Request

From this view, a CAC Admin user is able to attend to B2B request. A CAC Admin user has to verify that the device logged as returned to B2B was actually returned to B2B before approval. However, a CAC Admin can choose not to approve a return to B2B request.

### B2B Request Landing Page

To visit a B2B Request landing page, a CAC Admin user is should;
-	Login successfully to SIMROP
-	Click on **B2B Request** from the SIMROP menu as shown in B2B 1

The actions above navigate the CAC Admin user to the B2B Request landing page as shown in B2B 2

<!-- theme: success -->
> ##### B2B 1
> B2B Request

<!-- theme: success -->
> ##### B2B 2
> B2B Request Landing Page

### Search B2B Requests

To search for a B2B Request sent in by a dealer, a CAC Admin user should do the following as shown in B2B 2;
-	Enter a **Kit Tag** then click on Search
-	Select a **Status**, then, click on Search

The actions above retrieve the B2B requests based on the search done as shown in B2B 3

### View Details

On SIMROP, a CAC Admin user can view details an issue logged by a dealer;
-	Searching for an issue as described in 4.4.1
-	Click on the Action menu as shown in B2B 3
-	Click on View Details as shown in B2B 3

The actions above displays the details of the B2B request as logged by the dealer as shown in B2B 4

<!-- theme: success -->
> ##### B2B 3
> View B2B Request Details

### Resolve B2B Request

On SIMROP, for a B2B request to be complete, an admin user must approve the request. Approval of B2B requests goes through a workflow (i.e. more than 1 admin can approve based on configuration). To approve a B2B request, an admin should;
 
-	Follow the steps in 4.4.1
-	Enter **Resolution Feedback** as shown in B2B 4
-	Click on **APPROVE** as shown in B2B 4

The dealer is alerted via email when a B2B request has been approved or rejected by a CAC Admin user.

Note that when the last approver approves, the device becomes blacklisted and is unmapped from the existing dealer. The unmapped device is automatically mapped to a virtual dealer called ‘Return to B2B’.

Also, if a request is rejected, the dealer is notified and the device would still be mapped to the already assigned dealer.

<!-- theme: success -->
> ##### B2B 4
> B2B Request Resolution View

## Device Management
The Device Management module is used to carry out all device related activities on SIMROP. Operations that can be carried out from the Device Management Module range from Tagging and Tagging Approval, Device requisition and Blacklist.

The Device Management view can be accessed from the SIMROP menu as shown in DMGT 1 below

<!-- theme: success -->
> ##### DMGT 1
> Device Management Menu

### Blacklist View
The Blacklist view is used to manage device status (blacklist and whitelist). Also, from the view, a user can see the count of the following in the SIM Registration ecosystem as shown in DMGT 2;
-	Total Kits
-	Blacklisted Kits
-	Whitelisted Kits

From Blacklist view, an admin can do the following;
-	Blacklist a Device
-	Whitelist a Device
-	View Kit Details

#### Blacklist a Device 
To blacklist a device, the admin should do the following
-	Click on **Blacklist** from **Device Management** on SIMROP menu to access the Blacklist landing page as shown in DMGT 3
-	Search for the desired devices by entering the device **Kit Tag** or **Mac Address** as shown in DMGT 2 
-	Click on the **Action** button as shown in DMGT 3
-	Click on **Blacklist**. 
-	Clicking on the Blacklist displays a modal that allows the user to enter the **Blacklist Approver** and the **Blacklist Reason** from the dropdown as shown in DMGT 4
-	Enter any other feedback as required
-	Click on the **Save** button. 
-	Clicking on the Save button displays a success message as shown in DMGT 5

<!-- theme: success -->
> ##### DMGT 2
> Search Operation 

<!-- theme: success -->
> ##### DMGT 3
> Device Count & Blacklist Action

<!-- theme: success -->
> ##### DMGT 4
> Blacklist Approver & Reason

<!-- theme: success -->
> ##### DMGT 5
> Message of Successful Blacklist

#### Whitelist a Device 
To whitelist a device, the admin should do the following
•	Click on **Whitelist** from **Device Management** on SIMROP menu to access the Whitelist landing page as shown in DMGT 6
•	Search for the desired devices by entering the device **Kit Tag** or M**ac Address** as shown in DMGT 2 
•	Click on the **Action** button as shown in DMGT 6
•	Click on **Whitelist**. 
•	Clicking on the Whitelist displays a modal that allows the user enter the **Whitelist Approver** and the **Whitelist Reason** from the Whitelist Reason dropdown as shown in DMGT 7
•	Enter the optional feedback on the feedback field
•	Click on the **Save** button. 
•	Clicking on the Save button displays a success message as shown in DMGT 6

<!-- theme: success -->
> ##### DMGT 6
> Whitelist Action

<!-- theme: success -->
> ##### DMGT 7
> Whitelist Approver & Reason

#### View Kit Details 

From the Blacklist View, a user can view kit details. The kit details have all the kit information as listed below;
-	Mobile Device Information
-	Device Location Information
-	Blacklist/Whitelist History
-	Device Location History
-	Kit Agents
-	Client Activity Summary
-	Registration Summary

The listed can be seen in DMGT 8

<!-- theme: success -->
> ##### DMGT 8
> View Kit Details view

To view the View Kit Details view, a user should do the following;

Navigate to the landing page as shown in DMGT 2
-	Click on the Action button as shown in DMGT 3 or 6
-	Click on View Details

The action above navigates the user to the View Kit Details view as shown in DMGT 8

#### Bulk Blacklist/Whitelist
A user can choose to blacklist/whitelist multiple kits all at once. This feature ensures that a user is able to whitelist/blacklist several kits in a single operation. To carry out a bulk device whitelist/backlist, a user should;
- Access the Blacklist view and click on Bulk Upload as shown in DMGT 9
-	Click on the Download Template link (as shown in DMGT 10) to download an complete the excel template
-	Upload the completed excel template
-	Click on the Upload button as shown in DMGT 10

<!-- theme: success -->
> ##### DMGT 9
> Bulk Whitelist/Blacklist

<!-- theme: success -->
> ##### DMGT 10
> Template download & Upload

### Tagging Request View

The Tagging Request view gives user visibility of all tagging request from devices. When a tagging request is made, the device details become visible to enable the user to tag the device on SIMROP. 

Actions that can be carried out from a Tagging Request view include
-	Search for Tagging Requests
-	Assign Devices
-	Re-Assign Devices
-	View Tag History
-	View Details

#### Search of Tagging Requests 
A user can search for a tagging request using the following parameters;
-	Device ID/Kit Tag
-	Dealers
-	Status
-	Start Date
-	End Date

***Note:** Some of the search parameters are hidden and can become visible by clicking the **More…** button as shown in DMGT 11*

<!-- theme: success -->
> ##### DMGT 11
> Tagging Request View

To search for a device tagging request, the user should do the following;
-	Navigate to the Tagging Request View from Device Management on the menu
-	Enter the Device ID/Kit tag of the desired device. Click on More… button to show more search options
-	Click on the Search button as shown in DMGT 11

The action above displays the result based on the search criteria if there is a result of the search operation

#### Assign Device
Assigning of devices which are also known as device tagged can be done from the Tagging Request view. To assign a device;
-	Search for the desired device (refer to 4.5.2.1)
-	Click on the Action
-	Click on Assign as shown in DMGT 12 to display a form containing kit tagging information
-	Select the desired parameters as shown in DMGT 13
-	Click on Assign

The actions above create a tag for the selected device. However, the tagging request needs to be approved. See Tagging Approval for more details

<!-- theme: success -->
> ##### DMGT 12
> Assign/View Details Menu Item

<!-- theme: success -->
> ##### DMGT 13
> Device Assignment

#### Re-Assign Device
A user can choose to Re-Assign an already assigned and approved device on SIMROP. Re-assigning occurs when the user wants to assign an already assigned kit to another dealer or another state. Re-assigning can be done from the Tagging Request view. To re-assign a device;

-	Search for the desired device (refer to 4.5.2.1)
-	Click on the Action
-	Click on Re-Assign as shown in DMGT 14 to display a form containing kit tagging information. Note: Re-Assign menu item is only available to already assigned/tagged devices that their status is Approved on SIMROP.
-	Select the desired parameters as shown in DMGT 15
-	Click on Re-Assign

The actions above create a tag for the selected device. However, the tagging request needs to be approved. See Tagging Approval for more details

<!-- theme: success -->
> ##### DMGT 14
> Re-Assign/View Tag History/View Details

<!-- theme: success -->
> ##### DMGT 15
> Device Re-Assignment

#### View Tag History
To View Tag History, a user should
-	Navigate to the Tagging Request landing page
-	Click on the Action menu 
-	Click on View Tag History 

The action above displays all the tag history of the device as shown in DMGT 16 below

<!-- theme: success -->
> ##### DMGT 16
> View Tag History

#### View Details

To view Tagging Request details, a user should
-	Navigate to the Tagging Request landing page
-	Click on the Action menu 
-	Click on View Details 

The action above displays the details of the device as shown in DMGT 17 below

<!-- theme: success -->
> ##### DMGT 17
> View tagging Request Details

### Tagging Approval View
The Tagging Approval view gives a user visibility of all tagging approval requests from devices. The approval of tagged devices is controlled by an approval chain called workflow. Refer to the Workflow Management section 

Actions that can be carried out from a Tagging Approval view include
-	Search for Tagging Approval Requests
-	View Details
-	View Tag History

#### Search of Tagging Approval Requests 
A user can search for a tagging approval request using the following parameters;
-	Device ID/Kit Tag
-	Dealers
-	Status
-	Start Date
-	End Date

**Note:** Some of the search parameters are hidden and can become visible by clicking the More… button as shown in DMGT 18

<!-- theme: success -->
> ##### DMGT 18
> Tagging approval view

To search for a device tagging approval, the user should do the following;
-	Navigate to the Tagging Approval view from Device Management on the menu
-	Enter the Device ID/Kit tag of the desired device. Click on More… button to show more search options
-	Click on the Search button as shown in DMGT 18

The action above displays the result based on the search criteria if there is a result of the search operation

#### View Details
A user can view details of a tagging approval request and can also approve from the same view. Approval is configurable. This means that there could be more than 1 approver at a time based on configuration.

To Tagging Request details, a user should
-	Navigate to the Tagging Request Approval landing page
-	Click on the Action menu as shown in DMGT 19
-	Click on View Details 

The action above displays the details of the device as shown in DMGT 20 below

<!-- theme: success -->
> ##### DMGT 19
> View Details Action

<!-- theme: success -->
> ##### DMGT 20
> Tagging Details

#### View Tag History
To View Tag History, a user should
-	Navigate to the Tagging Request landing page
-	Click on the Action menu 
-	Click on View Tag History 

The action above displays all the tag history of the device as shown in DMGT 21 below

<!-- theme: success -->
> ##### DMGT 21
> View Tag History

## User Management Module
The User Management Module allows a user to manage other users and dealers on SIMROP. A user with access to the User Management Module 

### Access to the User Management Module
To access the user management module, do the following;
-	Login with a valid username and password
-	Click on User Management and click Account Creation as shown in the UMGT below

<!-- theme: success -->
> ##### UMGT 1
> User Management Access

-	The action above navigates the user to the view shown below

<!-- theme: success -->
> ##### UMGT 2
> User Manager Landing Page

### Account Creation 
To create an account on the User Management Module,
-	Access the User Management Module
-	Click on Add User as shown in UMGT 3 below
-	Click on User Creation. This action navigates the user to the account creation view as shown in UMGT 4
-	Enter the desired details in the form as shown in UMGT 4
-	Click on Save

<!-- theme: success -->
> ##### UMGT 3
> Add User

<!-- theme: success -->
> ##### UMGT 4
> User Creation Form

**Note:** 
-	*When creating an account, use a unique email address. If an email already exists, a second account can’t be created using the same email address*
-	*All fields marked * must be completed to successfully create a user account.*
-	*Also, when creating user accounts, a unique phone number must be provided. A phone number that is mapped to an existing user is not unique and cannot be used to create the account*
-	*There are 2 types of users: Admin User and Agent User.*
-	*Admin users are users that are assigned administrative privileges and more than one dealer*
-	*An Agent user is assigned to just one dealer at a time.*

### Search, View and Edit
To search and view details of an existing user;
-	Enter the user’s name, email or phone number or status or Role as shown in the UMGT above
-	Click on Search as shown in the UMGT above
-	The action above bring up related results as shown below

<!-- theme: success -->
> ##### UMGT 5
> User Account Search Result

-	Click on the Actions menu and select the View Details  menu item as shown below to view the details of the selected record

<!-- theme: success -->
> ##### UMGT 6
> User Account Edit Menu Item

-	Click on the Pencil icon to edit user detail

<!-- theme: success -->
> ##### UMGT 7
> User Account Update View

-	Update the desired field as shown in the UMGT 7 above and click on Update

### Account Activation/Deactivation
When an account is deactivated, the user is unable to use any component of BioSmart or SIMROP that requires account login. To deactivate an account,
-	Access the User Management Module
-	Search for the account to be deactivated using user’s email, phone number or name
-	Click on the Actions menu and select Deactivate as shown in the UMGT 8 below

<!-- theme: success -->
> ##### UMGT 8
> User Account Deactivation Menu Item

-	Enter the approver of the Deactivation request on the Approval Email field
-	Enter Reason for deactivating account from the Approval Reason dropdown as shown in the UMGT 9 below
-	Enter any other feedback as required

<!-- theme: success -->
> ##### UMGT 9
> Deactivation Reason View

-	Click on Deactivate to complete the deactivation process

To activate a deactivated account;
-	Access the User Management Module
-	Search for the account to be deactivated using user’s email, phone number or name
-	Click on the Actions menu and select Activate as shown in the UMGT 10 below

<!-- theme: success -->
> ##### UMGT 10
> User Account Activation View
	
- Enter the approver of the activation request on the Approval Email field
-	Enter Reason for activating the account from the Approval Reason dropdown as shown in the UMGT 11 below
-	Enter any other feedback as required

<!-- theme: success -->
> ##### UMGT 11
> Activation Reasons View

- Click on Activate to complete the deactivation process

### Password Reset
To reset an account;
-	Enter the user’s name, email or phone number and also select a status or Role from the user management landing page
-	Click on Search 
-	Click on the Actions menu on the selected record from the landing page
-	Click on Reset Password as shown in the UMGT 12 below

<!-- theme: success -->
> ##### UMGT 12
> Reset Password

The user gets a new password as an SMS to user’s phone number

### Account Unlocking
 Accounts are usually blocked, due to security reasons, when a user enters the wrong password a defined number of times consecutively. To unlock a locked account;
-	Enter the user’s name, email or phone number and also select a status or Role from the User Management landing page
-	Click on Search 
-	Click on the Actions menu and select the Unlock Account menu item as shown below to view the details of the selected record 

<!-- theme: success -->
> ##### UMGT 13
> Unblock User

### Bulk User Creation
An admin can create user accounts in bulk. To carry out a bulk account creation, the admin should
-	Access the User Management landing page
-	Click on the Add User > Bulk User Creation as shown below

<!-- theme: success -->
> ##### UMGT 14
> Bulk User Creation

-	Click on Download Template as shown in the UMGT 15 below
-	Complete the downloaded template as required
-	Locate the file on the download path
-	Click on Upload as shown in the UMGT 15 below

<!-- theme: success -->
> ##### UMGT 15
> Bulk User Creation Upload

**Note:** On successful upload, a status report showing the state of each of the record is downloaded

### Bulk Activation/Deactivation
An admin can activate or deactivate user accounts in bulk. To carry out a bulk account activation/deactivation, the admin should
-	Access the User Management landing page
-	Click on the Add User > Bulk Activation/Deactivation as shown below

<!-- theme: success -->
> ##### UMGT 16
> Bulk Activation / Deactivation

-	Click on Download Activation Template  or Download Deactivation Template as shown in the UMGT 17 below (the choice of the template depends on the type of operation to be performed)
-	Complete the downloaded template as required
-	Locate the file on the download path (or where the document is saved)
-	Click on Upload as shown in the UMGT 17 below

<!-- theme: success -->
> ##### UMGT 17
> Bulk Activation/Deactivation Upload

**Note:** On successful upload, a status report showing the state of each of the record is downloaded

### Bulk Password Reset
An admin can activate or deactivate user accounts in bulk. To carry out a bulk account activation/deactivation, the admin should
-	Access the User Management landing page
-	Click on the Add User > Bulk Password Reset as shown below

<!-- theme: success -->
> ##### UMGT 18
> Bulk Password Reset

-	Click on Download Template as shown in the UMGT 19 below
-	Complete the downloaded template as required
-	Locate the file on the download path
-	Click on Upload as shown in the UMGT 19 below

<!-- theme: success -->
> ##### UMGT 19
> Bulk Password Reset Upload

**Note:** On successful upload, a status report showing the state of each of the record is downloaded

### Dealer Creation
An admin can also create dealers on SIMROP via the User Management Module. To create a dealer, an admin should do the following;

-	Access the User Management Module
-	Click on the Dealer button as shown in the UMGT 20 below
-	Click on the Add Dealer button as shown in the UMGT 20 below

<!-- theme: success -->
> ##### UMGT 20
> Dealer Landing Page

- Enter the required details in the preceding form as shown in the UMGT 21 below
- Click on Save to create dealer account as shown in the UMGT 21 below

<!-- theme: success -->
> ##### UMGT 21
> Account Creation Form

### Search, View and Edit
To search and view details of an existing dealer account;
-	Enter the dealer’s name, email or phone number or status as shown in the UMGT 22 below
-	Click on Search as shown in the UMGT 22 below
-	The action above bring up related results as shown below

<!-- theme: success -->
> ##### UMGT 22
> Dealer Account Search Result

-	Click on the Actions menu and select the View Details  menu item as shown below to view the details of the selected record

<!-- theme: success -->
> ##### UMGT 23
> Dealer Account View Details

-	Update the desired field as shown in the UMGT  24 below and click on Update

<!-- theme: success -->
> ##### UMGT 24
> Dealer Account Update

### Dealer Account Activation/Deactivation
To deactivate a dealer account,
-	Access the User Management Module
-	Search for the account to be deactivated using dealer’s email, phone number or name
-	Click on the Actions menu and select Deactivate as shown in the UMGT below; 

<!-- theme: success -->
> ##### UMGT 25
> Dealer Account Deactivation Menu Item

-	Enter the approver of the Deactivation request and the Reason for deactivating account as shown in the UMGT 26 below

<!-- theme: success -->
> ##### UMGT 26
> Dealer Account Deactivation Reason View

-	Click on Deactivate to complete the deactivation process
**Note:** The Deactivation Count (number of times the dealer has been deactivated can be viewed while deactivating an active dealer

To activate a deactivated account;
-	Access the User Management Module
-	Search for the account to be deactivated using dealer’s email, phone number or name
-	Click on the Actions menu and select Activate as shown in the UMGT 27 below

<!-- theme: success -->
> ##### UMGT 27
> Dealer Account Activation View

-	Enter the approver of the activation request and the Reason for deactivating account as shown in the UMGT below

<!-- theme: success -->
> ##### UMGT 28
> Dealer Account Activation Reasons View

-	Click on Activate to complete the deactivation process

### Dealer Account Password Reset
To reset the password to a dealer’s account;
-	Enter the dealer’s name, email or phone number and also select a status from the user management landing page
-	Click on Search 
-	Click on the Actions menu on the selected record from the landing page
-	Click on Reset Password as shown in the UMGT 29 below

<!-- theme: success -->
> ##### UMGT 29
> Dealer Reset Password

The user gets a new password as an SMS to the user’s phone number with a notification on SIMROP.

### Dealer/User Account History

An admin is able to view either the user or dealer account activation history on SIMROP. To do this, the admin should;
-	Access the User Management Module
-	Access the User or Dealer sub-view as required
-	Search for the dealer or user from the selected view
-	Click on the Actions menu and select Activate as shown in the UMGT 30 below 
-	The action  below displays the activation/deactivation history of the user or dealer as shown in UMGT 31 below

<!-- theme: success -->
> ##### UMGT 30
> Activation History (From Action Menu)

<!-- theme: success -->
> ##### UMGT 31
> Activation History

## License Request Management
License request from kits can be managed from the license request management module. 

### Access License Request
-	Login with a valid username and password
-	Click on License Management from the menu and select FM License Management as shown in the Figure below

<!-- theme: success -->
> ##### FMLA 1
> Access License Request Manager

-	The action above navigates the user to the FM License Management view as shown in the Figure below 

<!-- theme: success -->
> ##### FMLA 2
> License Request Landing Page

### Approve/Reject a License Request
-	Access the License Management view
-	Search for a license request by entering the Kit tag, mac address or email of the requesting agent in the search box as shown in the Figure below 

<!-- theme: success -->
> ##### FMLA 3
> Search License Request

- Click on Approve or Reject as shown in the Figure below 

<!-- theme: success -->
> ##### FMLA 4
> Approve/Reject License Request

OR
-	Click on the checkboxes by the license requests for approval or rejection as shown in the Figure below 

<!-- theme: success -->
> ##### FMLA 5
> Multiple License Approval

-	Click on Bulk License Approval button to approve all checked licenses.

OR
-	Click on the Download/Upload License Approval as shown in the Figure above
-	Download the License Approval Template by clicking on the Download Template button
-	Complete the template and upload

<!-- theme: success -->
> ##### FMLA 6
> Bulk License Upload

**Note:** A status report is downloaded showing the status of bulk license approval/rejection request.

## Role Management
This module is used to manage roles assigned to users on SIMROP. Roles on SIMROP are assigned privileges which determines the type of activity a user can carry out SIMROP.

###	Access to Role Manager
-	Login with a valid username and password
-	Go to the SIMROP menu and select Role Manager as shown in the figure below

<!-- theme: success -->
> ##### RM 1
> Access Role Manager

-	The action above navigates the user to Role Management view as shown in the figure below 

<!-- theme: success -->
> ##### RM 2
> Role Manager Landing Page

### Add Role
Follow the steps below to add a new role
-	Access the landing page of the Role Management view as shown in the view above
-	Click on the Add Role button as shown in the figure below 

<!-- theme: success -->
> ##### RM 3
> Add New Role

-	Complete the form with the required details and click on Save as shown on the figure below 

<!-- theme: success -->
> ##### RM 4
> Role Creation Form

### View & Edit Role
-	Access the Role Management view
-	Enter the role name in the search field and click on the Search button as shown in the figure below 

<!-- theme: success -->
> ##### RM 5
> Search Existing Role

-	Click on Actions and select View Details as shown in the view below 

<!-- theme: success -->
> ##### RM 6
> Edit Existing Role

-	Click on Edit as shown in the figure below 

<!-- theme: success -->
> ##### RM 7
> Role Manager View Details

-	Enter the required details and click on the Update button as shown in the figure below 

<!-- theme: success -->
> ##### RM 8
> Role Manager Update Details

## Subscribers Module
The Subscriber allows a user with access to it to view details of any duly registered customer. 

### Access to Subscriber Module
-	Login successfully to SIMROP using the correct username and password
-	Go to the SIMROP Menu > Subscribers > Subscribers Info as shown in the figure below

<!-- theme: success -->
> ##### BIO 45
> Subscriber Info Menu

-	The action above navigates the user to the Biodata Manager view as shown below 

<!-- theme: success -->
> ##### BIO 46
> Bio Data Search

### Search Subscriber Details
-	The user can search for a subscriber’s details as shown in the figure above by using either of the following;
    -	Subscriber’s Names (surname, first name or both)
    -	Subscriber’s phone number
    -	Subscriber’s registration unique ID or Serial number
-	Click on the Search button as shown in the figure above to spool a list of all registrations associated with the search criteria used as shown in the figure below

<!-- theme: success -->
> ##### BIO 47
> Bio Data Search Result View

-	Click on Action > View Details of choice record to view the details associated with the registration as shown in the figure below

<!-- theme: success -->
> ##### BIO 48
> View Details

<!-- theme: success -->
> ##### BIO 49
> Bio Details View

-	Click on New Search as shown in the figure above to go back to the previous view to carry out a new search
-	Click on Print as shown in the figure above to print or export details to PDF

## VTU Management
VTU Management is a module that enables any admin with the required privilege to carry out VTU related management operations. The operations available to an admin on the VTU Management module include;

-	VTU Agent On-Boarding Request Approval
-	View VTU Dealer Dashboard
-	View Transaction History

VTU Management Module can be located on the menu as shown in VTUM 1 below;

<!-- theme: success -->
> ##### VTUM 1
> VTU Management Menu

### VTU On-Boarding Request Approval
Also, from the VTU Management module, the user can access the VTU On-Boarding Request Approval view. From this view, as shown in VTUM 8, a user is able to:
-	View & Approve Agent On-Boarding Request

#### View & Approve Agent On-Boarding Request
To view and approve an agent on-boarding request, the user should;
-	Click on VTU Management > VTU Onboarding Approval as shown in VTUM 1
-	Click on the Action > View Details button as shown in VTUM 2
-	The corresponding view shows the details of the Agent On-boarding request from the dealer as shown in VTUM 3
-	Enter the approval/rejection feedback and click on Approve/ Reject as shown in VTUM 3.

<!-- theme: success -->
> ##### VTUM 2
> Agent Approval View Details

<!-- theme: success -->
> ##### VTUM 3
> Approve VTU On-Boarding Request

#### Multiple Approval/Rejection
A user can choose to carry out multiple approval or rejection of Agent On-Boarding request. This feature ensures that a user is able to approve/reject several agents in a single operation. To carry out multiple approvals of agent on-boarding, a user should;
-	Access the VTU On-Boarding Approval view
-	Select the required requests by checking their respective check as shown in VTUM 4
-	Click on Approve Selected  or Approve Rejected as shown in VTU 4
-	Enter the Approval or Rejection Feedback in the corresponding view as shown in figure 5
-	Click on Approve or Reject to approve or reject the onboarding approval request.

<!-- theme: success -->
> ##### VTUM 4
> Multiple Approval / Rejection

<!-- theme: success -->
> ##### VTUM 5
> Multiple Approval/Rejection Reason

### VTU Dealer Dashboard
There is a VTU dashboard that is available to Admin Users on SIMROP. This dashboard has an overview of all vending carried out on BioSmart irrespective of the dealer. The dashboard comes with charts, counts and table. See a sample of the admin user VTU dashboard in VTUM 6

<!-- theme: success -->
> ##### VTUM 6
> VTU Admin Dashboard

The dealer dashboard has the following chart with their descriptions;
-	Total Airtime Amount – The total airtime amount of all the vends across all dealers
-	Total Data Amount – The total data amount of all the vends across all dealers
-	Successful Transactions – Total amount of successful transactions across all dealers
-	Failed Transactions – Total amount of failed transactions across all dealers
-	Transaction Distribution Airtime & Data – A bar chart showing a distribution of failed and successful airtime and data vend 
-	Transaction Distribution for Data Bundles – Distribution showing the count of the data types 

### Transaction History
The transaction history enables an admin user to have a visibility of all vending transactions carried out by agents mapped to dealers. The history is irrespective of if the transaction is failed or successful. The VTU Transaction History for airtime is shown in VTUM 7 while Transaction History for data is shown in VTUM 8.

<!-- theme: success -->
> ##### VTUM 7
> Admin Airtime transaction History

<!-- theme: success -->
> ##### VTUM 8
> Admin Data Transaction History

## Notifications
The notification feature is used to send messages or notifications to users in the field. Notifications can be either device targeted, user-targeted or global. A message targeted to a device can be viewed by any user that logs in to that device while a user targeted message can be viewed by only the user irrespective of the device they logged in to.
Below is a view of the Notifications landing page. 

<!-- theme: success -->
> ##### NOT 1
> Notifications Landing Page

The following actions can be carried out from the notification landing page;
-	Search for existing notifications
-	Send New Notification
-	View Notification Details

### Search for Existing Notifications
To search for existing notifications, the admin should do the following;
-	Click on Notifications from the Actions menu
-	Enter the desired search parameter
-	Click on the Search button as shown in NOT 2

<!-- theme: success -->
> ##### NOT 2
> Notifications page with Search Field

### Send New Notification
There are 2 methods of sending new notifications on SIMROP 
-	Single Notification
-	Bulk Notification

#### Single Notification
To send a single notification to a specified user or device, an admin is expected to do the following;
1.	Navigate to the landing page as shown in NOT 1
2.	Click on the Notification button and select Single Notification button as shown in NOT 3
3.	The action above displays the New Notifications dialog as shown in NOT 4
4.	Select the target group from the Select Target Group dropdown as shown in NOT 5
5.	Select the Dealer, the Kit/User (depending on the target group), enter the message and click on the Save button as shown in NOT 6
6.	Proceed with Notification Creation and notification is displayed indicating that the notification sending was either successful or failed as shown in NOT 7


<!-- theme: success -->
> ##### NOT 3
> New Notification (Single)

<!-- theme: success -->
> ##### NOT 4
> Single Notification Dialog

<!-- theme: success -->
> ##### NOT 5
> Single Notification Target Group

<!-- theme: success -->
> ##### NOT 6
> Save and Send Notification

<!-- theme: success -->
> ##### NOT 7
> Success Message

To send a Global Message, select Global from the Select Target Group dropdown and enter the message as shown in NOT 8. Click on the Save button. This action sends a message to all the kits on the BioSmart ecosystem.


<!-- theme: success -->
> ##### NOT 8
> Global Notification 

#### Bulk Notification
Bulk notification can be used to send to several users or kits at a time. This can be done by downloading a template and uploading the complete template. On successful upload, a status report is downloaded automatically. The status report shows the notification items that were successful or not successful

To send a bulk notification, the admin should do the following;

1.	Navigate to the landing page as shown in NOT 1
2.	Click on the Notification button and select Bulk Notification button as shown in NOT 9
3.	The action above displays the Notifications Notifications dialog as shown in NOT 10
4.	Download the required template depending on the target group (devices or users) by clicking on the links as shown in NOT 11
5.	Complete the downloaded template
6.	Select the completed and saved the template from the download location
7.	Click on the upload button as shown in figure 11.
8.	A status report is downloaded showing successful and failed notifications from the bulk notification operation.

<!-- theme: success -->
> ##### NOT 9
> New Notification (Bulk)

<!-- theme: success -->
> ##### NOT 10
> Bulk Notification Dialog Box

<!-- theme: success -->
> ##### NOT 11
> Bulk Notification Template download and upload

### View Notification

An admin can also view details of a sent notification. To view notification details, an admin should do the following;
-	Access the Notification Module’s landing page
-	Search for the desired notification
-	Click on the Action button and select View Details as shown in NOT 12
-	The action above displays the details of the selected notification as shown in NOT 13

## Kit Retrieval

This module enables an admin to have visibility of devices that have been retrieved from agents/users from their respect dealers. The admin does not carry out any action on this module. To view the details of a retrieved device, an admin should do the following;
-	Access the Kit Retrieval Module from the SIMROP menu
-	Search for the desired Kit Retrieval details
-	Click on View Details from the actions menu as shown in KITR 1 
-	The action above displays the details of the Kit Retrieval action performed by the dealer

<!-- theme: success -->
> ##### KITR 1
> Action Menu

<!-- theme: success -->
> ##### KITR 2
> View details

## Other SIMROP Actions

### Export Functionality
All SIMROP modules and views with tables have an export functionality. This means that the data available can be exported to either excel or pdf as desired. 

To export a report to excel, click on the excel icon in green as shown in the figure below and to export a report to pdf, click on the pdf icon in red as shown in the figure below.

**Note:** The export action only exports data visible to the admin at that time. i.e. the result on the screen is 50 of 500, only the 50 that is visible to the admin can be downloaded

<!-- theme: success -->
> ##### EF 1
> Export Functionality

### Column Visibility

Also, the number of columns visible to the admin on SIMROP can be controlled. This comes handy when there are too many columns for a given table and the admin wants to concentrate on a few columns. To select visible columns
-	On the view that has a table of results, click on the Select Visible Columns button as shown in COLV 1
-	Deselect the column name you want to be invisible and select the column you want to be visible as shown in COLV 2
-	The action above automatically removes the deselected columns as shown in COLV 3

<!-- theme: success -->
> ##### COLV 1
> Select Visible Column

<!-- theme: success -->
> ##### COLV 2
> Select/Deselect Visible Column

## Help Center

The help centre has a list of frequently asked questions on SIMROP. This gives first-hand information about solutions to frequently reoccurring issues on SIMROP.

The help centre can be accessed even without logging in to SIMROP. This means that it is accessible if a user is logged in or not. 

To access the help centre, click on the Help Center link at the top right corner of the SIMROP page (logged in or not) as shown in the figure below. The action navigates the user to the corresponding page as shown in the subsequent figure below;

<!-- theme: success -->
> ##### HC 1
> Help Center View

<!-- theme: success -->
> ##### HC 2
> Frequently Asked Questions