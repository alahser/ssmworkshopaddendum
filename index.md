### Addendum to AWS Systems Manager [Workshop](https://mng.workshop.aws/ssm.html)


For each section below, there are tips for completing the labs. Most of these tips are navigational in nature, to describe navigation differencese between the previous versious of AWS Console and today. This addendum is current as of September 8, 2021.

## [Inventory and Patch Management](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management.html) 
* [Event Engine Access](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/event_engine.html) - as is
* [Intro](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/intro.html) - as is
* [Setup](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/setup.html)   
   >1.3 The Key Pair may save automatically to your downloads
  
* [Inventory](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/inventory.html)
   >3.2 Choose **Fleet Manager** (not Managed Instances) from the navigation bar.
   >4.2 Select the first instance and then choose **Actions**, **Security**, and **Modify IAM Role**.
   >4.3 Under **Modify IAM Role**, select **ManagedInstancesRole** from the drop down list and choose **Apply**.
   >5. Return to the Systems Manager console and choose **Fleet Manager** (not Managed Instances) from the navigation bar. Periodically *refresh* Managed Instances (using the circle arrrow button) until your instances begin to appear in the list. Over the next couple of minutes your instances will populate into the list as managed instances. If the instance does not register after several minutes, you can reboot the EC2 instance by selecting the instances and using the menu **Actions**, **Manage Instance State**. Then select the **Reboot** radio control and press the **Change State** button.

* [State Manager](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/statemgr.html) - as is
* [Patch Manager](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/patch.html) - as is
* [Maintenance Window](https://mng.workshop.aws/ssm/use-case-labs/inventory_patch_management/maintwindow.html) - as is


## [Configuration Management](https://mng.workshop.aws/ssm/use-case-labs/configmanagement.html)

## [Complance Management](https://mng.workshop.aws/ssm/use-case-labs/configurationcompliance.html)


## [Capability Hands-On Labs](https://mng.workshop.aws/ssm/capability_hands-on_labs.html)

### [Lab Setup](https://mng.workshop.aws/ssm/capability_hands-on_labs/setup.html)

### [Resource Groups](https://mng.workshop.aws/ssm/capability_hands-on_labs/resourcegroups_tags.html)

### [Documents](https://mng.workshop.aws/ssm/capability_hands-on_labs/documents.html)

### [Run Command](https://mng.workshop.aws/ssm/capability_hands-on_labs/runcommand.html)

### [Parameter Store](https://mng.workshop.aws/ssm/capability_hands-on_labs/parameterstore.html)






For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

