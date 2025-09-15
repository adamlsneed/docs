---
title: "Java-Based User Interfaces"
description: "Java-Based User Interfaces"
sidebar_position: 10
---

# Java-Based User Interfaces

In the previous section called "Java Tab," we talked about the Java tab and how Endpoint Policy
Manager DesignStudio can be enabled to capture the user interface (UI) of Java-based applications.
This is done in two steps:

**Step 1 –** Installing a free utility called the Java Access Bridge

**Step 2 –** Turning off the user account control in Windows 7

The link for the installable Java Access Bridge can be hard to find. Email Endpoint Policy Manager
tech support at [support@endpointpolicymanager.com](mailto:support@endpointpolicymanager.com), and we can provide you with a
copy. Once installed, don't reboot yet, even though the Java Access Bridge installation process asks
you to.

The second step to capture the UIs of Java-based applications is to disable the user account
control. To do this, select "Change User Account Control settings" from the Start Menu, as shown in
Figure 199.

![special_applications_and_project](/images/endpointpolicymanager/applicationsettings/designstudio/applicationsprojects/special_applications_and_project.webp)

Figure 199. Disabling the user account control settings.

Then, slide the slider all the way to the bottom, as shown in Figure 200.

![special_applications_and_project_1](/images/endpointpolicymanager/applicationsettings/designstudio/applicationsprojects/special_applications_and_project_1.webp)

Figure 200. Changing the slider to "Never notify."

At this point, reboot your Endpoint Policy Manager DesignStudio machine. When you next run Endpoint
Policy Manager Application Settings Manager, the Tools|Options|Java tab will change to what's shown
in Figure 201. This will indicate that the Java Access Bridge has been loaded successfully and
remind you that UAC controls need to be off.

![using_the_grays_wizard_13](/images/endpointpolicymanager/applicationsettings/designstudio/using_the_grays_wizard_13.webp)

Figure 201.  The Java Access Bridge has been loaded successfully.

At this point, you can try to capture your application's UI if it's Java-based, like OpenOffice and
other similar applications. Note that some Java-based applications will only capture when assistive
technology is turned on. In Figure 202, OpenOffice dialogs can be captured when this checkbox is
checked first.

![special_applications_and_project_2](/images/endpointpolicymanager/applicationsettings/designstudio/applicationsprojects/special_applications_and_project_2.webp)

Figure 202.; Turning on assistive technology.

:::note
Not every Java-based UI will capture perfectly. Let us know if there's a particular
application you're having trouble with.

:::
