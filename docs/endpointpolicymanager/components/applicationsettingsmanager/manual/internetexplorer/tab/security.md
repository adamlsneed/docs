---
title: "Security Tab"
description: "Security Tab"
sidebar_position: 20
---

# Security Tab

Video: For a quick overview of how to manage the Security tab using Endpoint Policy Manager
Application Settings Manager, see the following video:
[http://www.endpointpolicymanager.com/video/endpointpolicymanager-manage-ie-security.html](http://www.endpointpolicymanager.com/video/endpointpolicymanager-manage-ie-security.html).

The Security tab lets you set levels for all four zone types. The dialog within IE can be seen in
Figure 6.

![ie_appset_tab_by_tab_2](/images/endpointpolicymanager/applicationsettings/preconfigured/internetexplorer/tab/ie_appset_tab_by_tab_2.webp)

Figure 6. Custom security settings for all four zone types.

Using the Endpoint Policy Manager IE AppSet, click on "Set Level" for the corresponding zone and
select your level (or select "Custom"). Do not set any custom settings when you select a standard
option from the drop-down menu, such as Medium, Medium High, etc.

![ie_appset_tab_by_tab_3](/images/endpointpolicymanager/applicationsettings/preconfigured/internetexplorer/tab/ie_appset_tab_by_tab_3.webp)

Figure 7. Custom settings for the local intranet zone.

Internet Explorer has a rich way of adding site to zone assignments, as shown in Figure 8.

![ie_appset_tab_by_tab_4](/images/endpointpolicymanager/applicationsettings/preconfigured/internetexplorer/tab/ie_appset_tab_by_tab_4.webp)

Figure 8. Adding site to zone assignments in Internet Explorer.

The IE AppSet Security tab Site to Zone Assignment is shown in Figure 9.

![ie_appset_tab_by_tab_5](/images/endpointpolicymanager/applicationsettings/preconfigured/internetexplorer/tab/ie_appset_tab_by_tab_5.webp)

Figure 9. Setting site to zone assignments in the IE Pak.

On the first line, you can specify `MODE=REPLACE` or `MODE=MERGE`. If you don't specify, the default
is `MODE=MERGE`. All other lines should take the form of`http://`or` https://` followed by a comma
and one of the following words:

- intranet
- internet
- trusted
- untrusted
- remove

This will deliver the web page into the corresponding zone or remove the web page from any zone if
"remove" is specified.
