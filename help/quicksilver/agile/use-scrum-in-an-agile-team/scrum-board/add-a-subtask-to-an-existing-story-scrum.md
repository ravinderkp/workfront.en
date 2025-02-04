---
product-area: agile-and-teams;projects
navigation-topic: scrum-board
title: Add a subtask to an existing story on the Scrum board
description: When creating subtasks for existing stories, keep in mind the Completion Mode setting for the project, because this affects how stories are updated.
author: Lisa
feature: Agile
---

# Add a subtask to an existing story on the Scrum board

When creating subtasks for existing stories, keep in mind the following:

**When the Completion Mode setting for the project is set to Manual:**

* Moving a parent story with subtasks to Complete updates the parent story to 100% and the Status to Complete. Subtasks are not updated.
* To update the Percent Complete for the story, you must update it from the Stories tab or from the Details page of the object.

**When the Completion Mode setting for the project is set to Automatic**:

* Moving a parent story with subtasks to Complete updates the parent story to 100% and the Status to Complete. Subtasks are also updated to 100% and the Status is updated to Complete.
* To update the Percent Complete for the story, you must update the Percent Complete for any subtasks. The Percent Complete for the story is calculated based on the Percent Complete of all subtasks.

## Access requirements

You must have the following access to perform the steps in this article:

<table style="table-layout:auto"> 
 <col> 
 </col> 
 <col> 
 </col> 
 <tbody> 
  <tr> 
   <td role="rowheader"><strong>Adobe Workfront plan*</strong></td> 
   <td> <p>Any</p> </td> 
  </tr> 
  <tr> 
   <td role="rowheader"><strong>Adobe Workfront license*</strong></td> 
   <td> <p>Work or higher</p> </td> 
  </tr> 
  <tr> 
   <td role="rowheader"><strong>Access level configurations*</strong></td> 
   <td> <p>Worker or higher</p> <p>Note: If you still don't have access, ask your Workfront administrator if they set additional restrictions in your access level. For information on how a Workfront administrator can modify your access level, see <a href="../../../administration-and-setup/add-users/configure-and-grant-access/create-modify-access-levels.md" class="MCXref xref">Create or modify custom access levels</a>.</p> </td> 
  </tr> 
  <tr> 
   <td role="rowheader"><strong>Object permissions</strong></td> 
   <td> <p>Contribute or Manage access to the task the subtask is on</p> <p>For information on requesting additional access, see <a href="../../../workfront-basics/grant-and-request-access-to-objects/request-access.md" class="MCXref xref">Request access to objects </a>.</p> </td> 
  </tr> 
 </tbody> 
</table>

&#42;To find out what plan, license type, or access you have, contact your Workfront administrator.

## Add a subtask to an existing story on the Scrum board

1. Click the **Main Menu** icon ![](assets/main-menu-icon.png) in the upper-right corner of Adobe Workfront, then click **Teams**.

1. (Optional) Click the **Switch team** icon ![Switch team icon](assets/switch-team-icon.png), then either select a new Scrum team from the drop-down menu or search for a team in the search bar.

1. Go to the agile iteration or project that contains the story where you want to add a subtask. For information about how to navigate to an iteration, see [View an iteration](../../../agile/use-scrum-in-an-agile-team/iterations/view-iteration.md).
1. Go to the story tile on the story board where you want to add a subtask.
1. Click **Add Subtask** on the main story card to create a subtask to the story.

   ![Add subtask](assets/agile-story-addsubtask-NWE.png)

   Or

   Click **Add Subtask** on a subtask tile to create a subtask to the subtask.

   Workfront supports infinite levels of subtasks, but only two levels (subtasks of subtasks are displayed on the agile story board.

   ![Add subtask](assets/agile-story-addsubtask2-NWE.png)

   When adding a subtask to a story that currently does not have a swimlane, the parent task is promoted to the Parent Story column and the subtask moves inside the swimlane.

1. Specify the following information:  

   <table style="table-layout:auto">
    <col>
    <col>
    <tbody>
     <tr>
      <td role="rowheader"><strong>Subtask Name</strong></td>
      <td> Specify a name for the subtask.</td>
     </tr>
     <tr>
      <td role="rowheader"><strong>Description</strong></td>
      <td>Specify a description for the subtask.</td>
     </tr>
     <tr>
      <td role="rowheader"><strong>Estimate</strong></td>
      <td>Specify the estimate for the subtask.<br><p>Keep in mind the following when creating estimates:</p>
       <ul>
        <li>If your&nbsp;agile team is configured to estimate stories in points, then by default 1 point equals 8 hours. Estimates are added as Planned Hours on the story.</li>
        <li>The combined&nbsp;estimates for all subtasks determines the estimate of&nbsp;the parent story. For more information, see <a href="../../../agile/use-scrum-in-an-agile-team/scrum-board/update-status-of-stories-and-subtasks.md" class="MCXref xref">Update the status of stories and subtasks on the Scrum board</a>.</li>
        <li>When you create a new subtask, the Estimate field is already set. If you reset the estimate on the subtask, you are resetting the estimate on the parent story (because the parent story is the sum of all its subtasks).</li>
       </ul><br></td>
     </tr>
     <tr>
      <td role="rowheader"><strong>Planned Hours</strong></td>
      <td> (Available only in projects) Specify the number of planned hours for the task.</td>
     </tr>
     <tr>
      <td role="rowheader"><strong>Assignment</strong></td>
      <td>Begin typing the name of the team where you want to assign the subtask, then click it when it appears in the drop-down list.</td>
     </tr>
    </tbody>
   </table>

1. Click **Create**.

