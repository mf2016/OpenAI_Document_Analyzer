## 1 DEPLOYING TO PILOT ENVIRONMENT (AZURE SUBSCRIPTION)

DEPLOYMENT AND CONFIGURATION GUIDE



|TABLE OF CONTENTS|||
|---|---|---|
|1 DEPLOYING TO PILOT ENVIRONMENT (AZURE SUBSCRIPTION)||2|
|1.1|DEPLOYMENT STEPS.|2|
|1.2|POST DEPLOYMENT STEPS|2|
|1.3|Create the AD application by running the ServicePrincipal.ps1.|3|
|1.4|Configure AD App:|5|
|1.5|SETTING UP THE WEB APPLICATION (BY A SERVICE ADMIN)|8|
|1.6|Install OMS Dashboards VIEWS.|9|
|1.7|VERIFICATION OF DEPLOYMENT|13|


DEPLOYMENT AND CONFIGURATION GUIDE

## 1.1 DEPLOYMENT STEPS

1. Create an Automation account with RunAs Service principal. Unfortunately ARM templates don't allow for creating AD service principals as yet, so this step is currently a manual.

:unselected: Refer the blog https://azure.microsoft.com/en-us/documentation/articles/automation- secconfigure-azure-runas-account/ for the steps.

:unselected: Creation of ServicePrincipal has a propensity to fail randomly. A basic verification whether it was successfully created is mandatory

2. Capture the AutomationAccount name and the resourcegroup. You will need them as parameters when you 'Deploy to Azure'

3. Deploy Arm template from this location https://github.com/AvyanConsultingCorp/azure-quickstart- templates/tree/master/azure-governancecloudwise

4. Note the URL of the Cloudwise App Service

## 1.2 POST DEPLOYMENT STEPS

Congratulations !

You have now successfully deployed the application. You will have to do a few additional steps to have the application configured

## (by a Service Admin only)

· Click open the scheduleIngestion runbook and click start to run the runbook. This step will kickstart the data ingestion to the OMS workspace specified.

DEPLOYMENT AND CONFIGURATION GUIDE

## Run books

scheduleingestion

X



||ALISADAGAR STATUL|||
|---|---|---|---|
||:selected:|||
|||||
|||:unselected:||
|||:unselected:||
|||||
||MAkte|||
|||||


Schedades

0 0

0 6

## 1.3 CREATE THE AD APPLICATION BY RUNNING THE SERVICEPRINCIPAL. PS1.

As ServicePrincipals can't yet be created in ARM json templates, one has to run this manually outside the deployment.

wwww. My do you need.this script7 ******* ** Refer article - https://azure.microsoft.com/en-us/documentation/articles/resource-group-authenticate-service-principal/

# STEPS TO MAKE THIS SCRIPT WORK FOR YOU # 1) Ensure you pass the right subscription name. Parameter SsubscriptionName # 2) Run the ARM deployment and capture the Cloudwise App Service URL. 3) when prompted, signin with a Service Admin user for the subscription +4) usually that's all you have to do

-- MANDATORY PARAVETERS. WILL Ssubscriptionhans

BE VERIFIED LATER IN THE SCRIPT AND WILL FAIL GRACIOUSLY IF NOT SUPPLIED # mare of the Azure subscription this is the Unique URL of the cloudwise app service deplayed by the ARM script

-- END HOAQUATURY PARAMETERS

Edit the serviceprincipal.ps1 (in Powershell_ise)

· You will need to supply subscriptionName and the deployed URL of the CloudWise App Service. Capture the output. You will need it in subsequent steps.

PLEASE REFER TO PARAMETER DESCRIPTIONS IF YOU NEED MORE INFORMATION ON WHAT NEEDS TO BE PROVIDED AS AN INPUT.

DEPLOYMENT AND CONFIGURATION GUIDE

---------

----- --------------

---

--------

-

DEPLOYMENT AND CONFIGURATION GUIDE

1.4 CONFIGURE AD APP:

a. In Azure Portal search for Azure Active directory. Open the "App Registrations" tab

b. Open the AD Application that you just created. It should start with the name "CloudWise - Governance Advisory Portal"

c. Configure the following permissions in the "Required Permissions" tab

d. List of Permissions

Category

Permission



|Windows||APPLICATION PERMISSIONS
:unselected:|:unselected:||
|---|---|---|---|---|
|Service||No application permowvores avilable|||
|Management||DELEGATED PERMISSIONS
:unselected:|MECUIBES ALAN
:unselected:||
|API||Access Azure Service Management as org zation users (preview]|||
||||||
|Microsoft.Azure. Active Directory|||||
|||Enable Access|X||
|||APFIXATION PERMISSIONS|REDUIRIS ADMIN
:unselected: :unselected: :unselected:||
|||Road directory data
:selected:|:unselected:||
|||Read and write domains|Yes
:unselected:||
|||:selected: Read and write directory data|Ves
:unselected:||
|||Read and write devices|:unselected:||
|||DELEGATED PERMISSIONS|REQUIRES ADMIN||
|||Access the directory as the signed-in user
:selected:|:selected:||
|||Road directory data
:selected:|:unselected: Yes||
|||Read and write directory data|ves
:unselected:||
|||Read and welte all groups|:unselected: Yes||
|||Read all groups
:selected:|:unselected: Ves||
|||Read af users" full profiles|:unselected:||
|||Read all users' basic profiles|No
:unselected:||
|||Sign in and read user profile|:unselected:||
||||||


DEPLOYMENT AND CONFIGURATION GUIDE

Enable Access Microsoft Graph - PREVIEW

X

Microsoft Graph - PREVIEW
F. Save Delete

APPLICATION PERMISSIONS

REQUIRES ADMIN

Read all hidden memberships

Yes
:selected:

Read and write files in all site collections (preview)

Yes
:selected:

:selected: Read files in all site collections (preview)

Yes
:selected:

Read mail in all mailboxes

Yes
:unselected:

Read and write mail in all mailboxes

Yes
:selected:

Send mail as any user

Yes
:selected:

Read calendars in all mailboxes

Yes
:selected:

Read and write calendars in all mailboxes

:selected: Yes

Read contacts in all mailboxes

Yes
:selected:

Read and write contacts in all mailboxes

Yes
:selected:

:selected: V Read all groups

Yes
:selected:

Read and write all groups

Yes
:selected:

:selected: V Read directory data

Yes
:unselected:

:selected: V Read and write directory data

Yes
:selected:

Read and write devices

:selected: Yes

:selected: Read all users' full profiles

Yes
:selected:

Read and write all users' full profiles

Yes
:unselected:

:unselected: Read and write all user mailbox settings (preview)

Yes
:selected:

:selected: Read all identity risk event information

Yes
:selected:

Delegated Permissions

DEPLOYMENT AND CONFIGURATION GUIDE



|DELEGATED PERMISSIONS|REQUIRES ADMIN|
|---|---|
|Edit or delete items in all site collections|No
:selected:|
|Read and write user and shared tasks|= No
:selected:|
|Read user and shared tasks|No
:selected:|
|Read and write user and shared contacts|No
:unselected:|
|Read user and shared contacts|No
:unselected:|
|Read and write user and shared calendars|No
:selected:|
|Read user and shared calendars|No
:unselected:|
|Send mail on behalf of others|No
:selected:|
|Read and write user and shared mail|No
:selected:|
|Read user and shared mail|No
:unselected:|
|V Sign in and read user profile
:selected:|No
:selected:|
|Read and write access to user profile|No
:selected:|
|:selected: V Read all users' basic profiles|No
:selected:|
|:selected: V Read all users' full profiles|Yes
:unselected:|
|Read and write all users' full profiles|Yes
:unselected:|
|:selected: V Read all groups|Yes
:unselected:|
|Read and write all groups|Yes
:selected:|
|V Read directory data
:selected:|Yes
:unselected:|
|V Read and write directory data
:selected:|Yes
:unselected:|
|V Access directory as the signed in user
:selected:|:selected: Yes|
|||


DEPLOYMENT AND CONFIGURATION GUIDE



|Read items in all site collections|No
:unselected:|
|---|---|
|V Sign users in
:selected:|No
:unselected:|
|V Access user's data anytime
:selected:|No
:selected:|
|Read users' relevant people lists (preview)|No
:selected:|
|Create pages in user notebooks (preview)|No
:selected:|
|Limited notebook access (preview)|No
:unselected:|
|Read user notebooks (preview)|No
:unselected:|
|Read and write user notebooks (preview)|No
:unselected:|
|Read all notebooks that the user can access (preview)|No
:selected:|
|Read and write notebooks that the user can access (preview)|No
:unselected:|
|Read user tasks|No
:selected:|
|Create, read, update and delete user tasks and projects (preview)|No
:unselected:|
|:selected: V View users' email address|No
:selected:|
|V :selected: View users' basic profile|No
:unselected:|
|Read and write user mailbox settings (preview)|No
:unselected:|
|:selected: V Read identity risk event information|:selected: Yes|
|||


DEPLOYMENT AND CONFIGURATION GUIDE



|||
|---|---|
|||
|Filter settings||
|GENERAL||
|Properties|A|
|Reply URLs||
|Owners|A|
|API ACCESS||
|1. Required permissions||
|Keys||


## http://localhost:62080/

...

2. Open Portal and then you get an initial screen where you need to put subscription id, Client Applicaion ID and Client secret and then press submit.

3. After submit you will be redirect to AD login page where you need to input your active directory url and then press GO.

4. After this you need to input your LiveID credentials and after successfully login you will be redirect to Rule page where you can see all rules and submit rules.

## 1.6 INSTALL OMS DASHBOARDS VIEWS.

This is currently a manual process as ARM json deploys do not yet support creation of OMS views.

(By a ServiceAdmin/Contributor role)

1. Open the resource group and click on the OMS Portal link. This will open the OMS portal in a different window

DEPLOYMENT AND CONFIGURATION GUIDE



|||||||||
|---|---|---|---|---|---|---|---|
|||||||||
|||||||||
||-||||0|||
||||-|||||
||:selected:|||||:selected:||
|||--||||||
||:selected:||-|||-||
|||-||||||
|||||||---||
||:selected:|---||||Pagine||
|||:selected:||||||
||||--|Q||:selected:||
|||:selected:||||||
||:selected:|:unselected:||||||
||||-|||-||
|O|-- -|||||||
||:selected:||- --||:selected:|||
||||||F|:selected:||
||---- :selected:|||||||
||--|||||||
|||||||||
|||||||||
|||||||||


Michieft Carattere Management Suite

Get started @

Janaph Chan

------

0%

0 8

3. Import SQL DB view by clicking on the Import button and browsing to the file (OMSAzureDashboards\OMSSQLDBAzureMonitoringSolution.omsview)

DEPLOYMENT AND CONFIGURATION GUIDE



|||||
|---|---|---|---|
|Duevine + SOL Ature Analytics"||||
|O ₮||||
|18 0 -||4||
|||0||
||||Recommended searches|
|||||
|||||
|||||
|||||
|||||
|||||
|||||
|||||
||||-|


34564



||||||
|---|---|---|---|---|
||||||
|SQL Azure SQL Analytics|1 4||0|0|
|||0|||
|SOL Vaun Monitoring made sarys Microsoft|-|-||. .|
|||||--- .|
||||||


4. Repeat the same step for the Web App Monitoring datboard. Import view OMSAzureDashboards\ OMSWebAppAzureMonitoringSolution.omsview

DEPLOYMENT AND CONFIGURATION GUIDE



|Durview . Web App Azure Monitoring Solution* 7||||
|---|---|---|---|
|0|16 0|0||
|||4||
||||Donut &c ist|
|||||


Mirmert Costtur Management faute

Duevine a Miah App Azura Monitoring Sulution

O

-----

--------

Web Apps Azure Monitoring

0

1

-

--

-

-

-

-

-

-

-

DEPLOYMENT AND CONFIGURATION GUIDE

## 1. Application Verification

a. Login to the Azure portal

b. Navigate to the App Service URL

You should be able to see the following screen

e O cloudwisep6kn5etc5dbi4 azurewebsites.net

## CloudWise

Subscription Id

Current Offer Pay As You-Go

Application Client id

Application Password

Notification Email IDs

Subsequent steps should lead you to a signin (please signin with a ServiceAdmin Credential) 0

C

CloudWise - Governance Advisory Portal (ver Sysgain- CloudTry-Dev]

------

. .

Submit

DEPLOYMENT AND CONFIGURATION GUIDE

0

GOVERNANCE BLILES

---

