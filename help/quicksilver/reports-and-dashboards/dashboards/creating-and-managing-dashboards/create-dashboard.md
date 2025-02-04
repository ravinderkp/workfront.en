---
product-area: dashboards
navigation-topic: create-and-manage-dashboards
title: Create a dashboard
description: You can create dashboards to quickly access information in reports, calendars, and external pages.
author: Nolan
feature: Reports and Dashboards
---

# Create a dashboard

You can create dashboards to quickly access information in reports, calendars, and external pages.

To learn more about dashboards, see [Get started with dashboards](../../../reports-and-dashboards/dashboards/understanding-dashboards/get-started-dashboards.md).

## Access requirements

You must have the following:

<table style="table-layout:auto">
 <col> 
 </col> 
 <col> 
 </col> 
 <tbody> 
  <tr> 
   <td> <p><strong>Adobe Workfront plan*</strong></p> </td> 
   <td>Any</td> 
  </tr> 
  <tr> 
   <td> <p><strong>Adobe Workfront license*</strong></p> </td> 
   <td> <p>Plan </p> </td> 
  </tr> 
  <tr> 
   <td><strong>Access level configurations*</strong> </td> 
   <td> <p>Edit access to Reports, Dashboards, and Calendars</p> <p>Note: If you still don't have access, ask your Workfront administrator if they set additional restrictions in your access level. For information on how a Workfront administrator can change your access level, see <a href="../../../administration-and-setup/add-users/configure-and-grant-access/create-modify-access-levels.md" class="MCXref xref">Create or modify custom access levels</a>.</p> </td> 
  </tr> 
  <tr> 
   <td> <p><strong>Object permissions</strong> </p> </td> 
   <td> <p>You will obtain Manage permissions to the new dashboard</p> <p>For information on requesting additional access, see <a href="../../../workfront-basics/grant-and-request-access-to-objects/request-access.md" class="MCXref xref">Request access to objects </a>.<br>For more information on permissions for dashboards, see <a href="../../../workfront-basics/grant-and-request-access-to-objects/permissions-reports-dashboards-calendars.md" class="MCXref xref">Share reports, dashboards, and calendars </a>.</p> </td> 
  </tr> 
 </tbody> 
</table>

&#42;To find out what plan, license type, or access you have, contact your Workfront administrator.

## Prerequisites

You must create any of the following objects before you can add them to a dashboard:

* **Reports**: For information on creating reports, see [Create a custom report](../../../reports-and-dashboards/reports/creating-and-managing-reports/create-custom-report.md).

* **Calendars**: For information on creating calendars, see [Calendar reports overview](../../../reports-and-dashboards/reports/calendars/calendar-reports-overview.md).

* **External pages**: For information on creating external pages, see [Embed an external web page in a dashboard](../../../reports-and-dashboards/dashboards/creating-and-managing-dashboards/embed-external-web-page-dashboard.md).

## Create a dashboard

1. Click the Main Menu icon ![](assets/main-menu-icon.png), then click **Dashboards.** 
1. Click **New Dashboard**.  
   The New Dashboard dialog box displays.

1. Specify the following: 

   <table style="table-layout:auto">
    <col>
    <col>
    <tbody>
     <tr>
      <td role="rowheader"><strong>Name</strong></td>
      <td><p>This is the name of your dashboard.</p><p>If you do not specify a name, the name of the first report on the dashboard becomes the name of the dashboard, by default.</p></td>
     </tr>
     <tr>
      <td role="rowheader"><strong>Description (Optional)</strong></td>
      <td>This is a description of your dashboard.</td>
     </tr>
    </tbody>
   </table>

1. Select a layout by clicking the radio button corresponding to it.

   The single-column layout is the default.

   For information about report layout on dashboards, see [Understand how reports display on a dashboard](../../../reports-and-dashboards/dashboards/understanding-dashboards/understand-how-reports-display-dashboard.md).

   <!--
   <MadCap:conditionalText data-mc-conditions="QuicksilverOrClassic.Draft mode">
   (NOTE: Consider adding the information from this article here, at some point, instead of linking to it.)
   </MadCap:conditionalText>
   -->

1. Add existing reports, calendars, or external pages by searching for them in the **Search by name or type ...** field, then dragging them to the layout pane, when they appear in the list.

   >[!NOTE]
   >
   >When searching for an item, the search returns any of the 2,000 most recently created reports. Report names that include unicode characters are not returned in search results. As a best practice, avoid including unicode characters when naming objects in Workfront by typing names rather than copying and pasting names from another source.

   ![Search for reports](assets/qs-new-dashboard-ui-0722.png)

1. (Optional) Click **Add External Page** to add an External Page to the dashboard.   
   For more information about creating external pages and embedding them into dashboards, see [Embed an external web page in a dashboard](../../../reports-and-dashboards/dashboards/creating-and-managing-dashboards/embed-external-web-page-dashboard.md).

1. Click **Save + Close**.  
   A timestamp is displayed in the upper-right corner of the dashboard. The timestamp includes the date, time, and time zone when the dashboard was last refreshed.
