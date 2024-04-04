# Setting up by the Scientific Secretary/Admin/Editor-in-Chief for the submission of contributed abstracts

[//]: # "[Invited Presentations in the Programme](../InvitedOrals/intro)"

Since ECRIS does not have Invited Orals, which would be the first phase of setting up, what is missing is contributed oral presentations and contributed posters. The abstract proposals for these two kind of presentations will be submitted by their authors during the general abstract submission interval.

Some changes in the Indico setup are needed before starting this important part of the conference organisation.

Again, before letting anybody submitting abstracts, please check that [manual entry of authors/speakers is disallowed](/InitialSetup/mgmt_area_02/#participant-roles). This way, authors will be forced to only use profiles from the JACoW Central Repository when submitting or editing abstracts or contributions.

## 1. Removal of all the abstract proposals (e.g. for invited orals)

If you have created any abstract proposals beforehand for whatever reason, before opening the general abstract submission and contemporary access to existing contributions by invited authors it is necessary to remove all the abstracts (not the contributions!). If not, any proposed author for invited orals will be able to see who proposed their abstracts and get evidence of their acceptance or not, which won't be nice. 

[//]: # "This operation is also described in the [final Admin steps for the Invited Oral proposals](../InvitedOrals/SSinviteinvited.md#cleaning-up-to-remove-proposals)."

## 2. Changing visibility of Contribution types

[//]: # "During the [Setup for proposals of invited presentations](../InvitedOrals/SSsetup/#organization-contributions-settings) all presentation types were created. Only *Invited Oral Presentation* where made visible to the public which, at that time, was made of SAB/OC/SPC members."

We have to switch off visibility for special presentations and only allow Contributed ones to be choosable. 

Start by accessing the Contributions panel, then open the Settings menu and click on "*Contribution types*":

![](../InvitedOrals/img/contribution_types.png)

Now, edit all contribution types **ensuring that all except *Contributed Oral Presentation* and *Poster Presentation* are Private**:

![](img/contribution_type_list.png)

## 3. Configuring abstract submission

Small changes are also required in *Workflows / Call for Abstracts*.

### Submission / Settings

![](../InvitedOrals/img/call4abstracts.png)

#### Announcement

Enter here a statement concerning abstract submission that will be visible by accessing the *Call for Abstracts* menu item in the Home Page Menu, above the *Submit New Abstract* button:

![](../InvitedOrals/img/call4abstracts-announcement.png)

#### Instructions

The instructions here will be displayed above the abstract submission form. It should be used for precise instructions, for example concerning the Footnotes field or any special instructions peculiar to this ECRIS edition. Reference to the [general submission instructions](../submission) may be useful to also have here. 

---

All remaining controls should be left unchanged from the previous exercise related to invited oral proposals.

## 4. Setup email notifications to submitters

It will be nice for the submitters to receive an email confirming reception of their abstracts. Indico can do this by way of the Notificatons tool available at *Workflows / Call for Abstracts / Submission / Notifications*.

Start adding a new notification by way of the "**Add new one**" button:

![](img/emailnotifications.png)

Give a name to this new ruleset (visible only to admins in Indico) and choose the "**Submit**" email template.

Press the button "**Add new rule**" and choose "**Submitted**" from the popup menu. The result should be similar to this image:

![](img/emailnewrule.png)

Now you can setup the details of the email. Placeholders can be uses (e.g. `{abstract_id}`, `{submitter_name}`, etc.) Refer to the legenda below the Body of the email.

![](img/emailnotificationtext.png)

We recommend that only submitters are notified (not the other authors), so be sure to deselect "Send to primary authors" and "Send to co-authors".

It may be useful for the scientific secretariat to receive copy of these emails to monitor the submission activity. For this purpose, enter their email address in the "CC" field.

## 5. Change of event access mode/rights

To let people to access the Indico event, go to *Protection* and change the *Protection mode* to *Inheriting* (or *Public*, which should be inherited from the ECRIS category).

![](img/ProtectionInheriting.png)

## 6. Opening abstract submission

When you're ready to open abstract submission, go back to [Submission / Settings](#submission-settings) and either schedule it or open it explicitly.

## 7. Send announcement to the ECRIS community

JACoW allows only **one** general announcement to the ECRIS mailing list\* (and up to two to the Industry one).

In the past these announcements were sent directly by the Scientific Secretariat via the conference SPMS instance. Nowadays only the JACoW Board of Directors can send these announcements. It is necessary to request this action via email to the [JACoW Coordinator (with the Chair in copy)](https://www.jacow.org/Main/Contacts).

Please be sure to take your time and agree in advance with the JACoW coordinator on these points:

- Exact time of delivery

- Text for the email Subject

- Text for the email body

Please be aware that text only emails ([ASCII](https://en.wikipedia.org/wiki/ASCII)) can be sent: no HTML, no "hidden" links, no attachments.

---

\* the ECRIS mailing list is the list of JACoW accounts in the Central Repository that have explicitly requested news on the ECRIS conference series. Although every person is responsible for their account update, the JACoW Coordinator can manage these lists as well.
