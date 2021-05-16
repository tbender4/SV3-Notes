# Making a building from scratch

*TLDR*: Create a building, create the default management group for that building, customize the layout, enable default features.

Note: The following URLs are for the *Core* instance. Adapt to your desired instance by replacing the subdomain.

Superuser permission is **required**.

## Create Building

Go to New Building (SU).

Fill out Building Name (first line of building address is acceptable.
Fill out full address of building.
Select Create new group. **Create a new group for each new building**. Typical naming convention for group is the building name/building address + "Management". Ex: If building is named *11th Broadway*, name the group *11th Broadway Management*.

## Enable Features

The following features are considered **essential** to enable for a building:

### Visitor Management Settings
- Schedule
- Visitors

### Visitor Scheduling Features
- New Scheduling Interface
- Send Apple Wallet to the Visitor
- Show Visitor Photo In Email Notification
- Visitor Type
- Import Users Function

### Check In Features
- Allow No Badge Print Option on Visitor Check-In
- Display Last Visit Photo During Check In
- Show Visitor Photo In Email Notification
- Show visitor image on checkin page

### Group Settings
- Hide leases tab for tenants
- Hide Email guests invitation by default
- Hide Work Orders features

On right hand column: Default Group dropdown, select the management group offered.

Press UPDATE.

## Adding default visitor type
Under super management, go to Visitor Type Settings.
Name your default visitor category and name. (An easy default is naming both `Visitor`)

Press on SAVE SETTINGS.

## Customization

### Creating subdomain for building
While in features page, find Subdomain and click on **[configure]** next to the dropdown.
Scroll to bottom of page. Press on New subdomain.
Type in subdomain, upload logo of company, choose email hex color that best contrasts with the logo.
Under subdomainable search for name of the building. Select desired building.
Press Save. You'll see a confirmation of change. Then press Back.

Back in the features page, go to Subdomain dropdown, confirm your desired subdomain is listed.
Press UPDATE.

### Background Image on login
While in features page, find Background Image on right hand side. Click on Choose File
Upload high-resolution background image.
Press UPDATE.

**NOTE**: If one domain is used to access multiple buildings, the background image must still be set *per building*.

## Printer configuration

In the features page go to right hand column: Go to to dropdown under Badge Type. Select printer that's used for this building.
Press update.

### Dymo printer configuration
Under Super Management go to Badge Config.
If printer configured is the dymo printer, you'll be given an option to download the current label. The current label is saved as a `.xml` file. Rename the extension to `.label`.
Open this label file in the Dymo label editor software and make changes if necessary.
To upload the label, press Choose File, select the updated logo for upload.
Press SAVE CHANGES.

## Create Stacking Plan

Create a basic stacking plan first of one floor. Then generate other floors and groups using the stacking plan template.

Go to Stacking Plan.
Enter 1 next to *How many stories*.
Select Lobby
Select Add Space
Rename this space as "Lobby" or "100"
Select Create
Click on "Add Lease" on the top right
Search for your Management Group by name. The entry field will automatically update as your type. Click on the name when it appears.
Select "Create"
Return to your building's administrator page by going to the Buildings dropdown and selecting on your building. (*NOTE*: This will just be named "Building" and not be a dropdown menu if this is your first building)
Click on "Import Users" next to the name.

### Importing Users

Importing Users via the template is the most effective way to filling out the stacking plan. It'll also create the respect management groups and user accounts for everyone associated with the building.

Download the template. Fill out all fields. Be sure to make "send infromation" column **NO** for all users. It is more ideal to email them when the system goes live.
Click on Choose File. Find and upload the filled out template. Press **IMPORT**

Go into Stacking Plan again to confirm changes are made.

