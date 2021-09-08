### Addendum to AWS Systems Manager [Workshop](https://mng.workshop.aws/ssm.html)


Under each section below, there are corrections to the workshop. Most of these tips are navigational in nature, that is, changes in the names of menu items. This addendum is current as of September 8, 2021.

## [Inventory and Patch Management](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management.html) 
#### [Event Engine Access](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/event_engine.html)
   >as is
#### [Intro](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/intro.html) 
   >as is
#### [Setup](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/setup.html)   
   >1.3 The Key Pair may save automatically to your downloads
  
#### [Inventory](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/inventory.html)

**3.1 Setting Up Systems Manager**

   > 3.2 Choose **Fleet Manager** (not Managed Instances) from the navigation bar.
   
   > 4.2 Select the first instance and then choose **Actions**, **Security**, and **Modify IAM Role**.
   
   > 4.3 Under **Modify IAM Role**, select **ManagedInstancesRole** from the drop down list and choose **Apply**.
   
   > 5.0 Return to the Systems Manager console and choose **Fleet Manager** (not Managed Instances) from the navigation bar. Periodically *refresh* Managed Instances (using the circle arrrow button) until your instances begin to appear in the list. Over the next couple of minutes your instances will populate into the list as managed instances. If the instance does not register after several minutes, you can reboot the EC2 instance by selecting the instances and using the menu **Actions**, **Manage Instance State**. Then select the **Reboot** radio control and press the **Change State** button.

**3.3 Using System Manager Inventory to Track Your Instances**

   > 1.0 Under **Node Management** in the AWS Systems Manager navigation bar, choose Inventory.
   
   > 3.0 In the Setup Inventory screen, define targets for inventory:  Select **Selecting all managed instances in this account**
   
   > 6.0 It is not necessary to select an S3 bucket for the workshop

#### [State Manager](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/statemgr.html) 

**3.4 Review Association Status**
   > 1.0 Under **Node Management** in the navigation bar, select State Manager. At this point, the Status may show that the inventory activity has not yet completed. 
   
   * There is an option to specify **Output options**.
   > 1.0 Navigate to **Fleet Manager** under **Node Management** in the navigation bar. An Association Status has been established for the inventoried instances under management.

   >  3.0 Navigate to **Compliance** under **Node Management** in the navigation bar. Here you can view the overall compliance status of your managed instances in the Compliance resources summary and the individual compliance status of systems in the Details overview for resources section below.
  

#### [Patch Manager](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/patch.html) 

**[4.1 Create a Patch Baseline](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/patch.html#41-create-a-patch-baseline)**
   > 1.0 Under **Node Management** in the AWS Systems Manager navigation bar, choose Patch Manager.

   > 2.0 Click the **Patch Baselines** tab.


**[4.4 Scan Your Instances with AWS-RunPatchBaseline via Run Command](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/patch.html#44-scan-your-instances-with-aws-runpatchbaseline-via-run-command)
   > 1.0 Under **Node Management** in the AWS Systems Manager navigation bar, choose Run Command. In the Run Command dashboard, you will see any currently executing commands. You can also select the Command history tab to view previously executed commands including the execution of AWS-RefreshAssociation, which was performed when you set up inventory.

   >  6.0 (No correction - just note that SMS target need not be specified for training)

   > 10, 11, and 12 - (No correction - the order of steps may be different). 

**[4.5 Review Initial Patch Compliance](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/patch.html#45-review-initial-patch-compliance)**
   > 1.0  Under **Node Managment** in the the AWS Systems Manager navigation bar, choose Compliance.


   > 3.0 (Optionally) Select the radio button of a Non-Compliant resources for the Patch compliance type to show the Compliance rule resources list. Next, filter the list of complaince rules using the drop down list to select "non-compliant". Now, scroll down to see a list of updates that the specific instance is missing.
  
  

#### [Maintenance Window](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/maintwindow.html) 
   > as is


## [Configuration Management](https://mng.workshop.aws/ssm/use-case-labs/configmanagement.html)

## [Complance Management](https://mng.workshop.aws/ssm/use-case-labs/configurationcompliance.html)


## [Capability Hands-On Labs](https://mng.workshop.aws/ssm/capability_hands-on_labs.html)

### [Lab Setup](https://mng.workshop.aws/ssm/capability_hands-on_labs/setup.html)

### [Resource Groups](https://mng.workshop.aws/ssm/capability_hands-on_labs/resourcegroups_tags.html)

### [Documents](https://mng.workshop.aws/ssm/capability_hands-on_labs/documents.html)

### [Run Command](https://mng.workshop.aws/ssm/capability_hands-on_labs/runcommand.html)

### [Parameter Store](https://mng.workshop.aws/ssm/capability_hands-on_labs/parameterstore.html)






For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

