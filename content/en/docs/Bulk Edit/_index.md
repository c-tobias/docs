---
title: "Bulk Edit"
linkTitle: "Bulk Edit"
date: 2025-02-21
weight: 550
---

**This section of the documentation contains links to external sites. Please be advised that these external sites are not maintained by the FOLIO Documentation Group and may be aligned with a different FOLIO release.**


The Bulk Edit app allows a user to apply changes to multiple Inventory or User records simultaneously.


## Permissions

The permissions listed below allow you to interact with the Bulk Edit app and determine what you can or cannot do within the app. Bulk edit permissions, combined with other functional app permissions, allow a user to access specific areas of the Bulk Edit app. 

Permissions are assigned to users in the Users app. If none of the Bulk edit permissions are assigned to a user, they are unable to see the Bulk Edit app or any related information. 
See [Users \> Assign or unassign permissions](../users/#assign-or-unassign-permissions) for more information. 

The following are the permissions for the Bulk edit app:

- **Bulk edit: Can build query**: This permission allows the user to build and test a query, and preview matched records in the Bulk edit app. 
- **Bulk edit: Can view logs** This permission allows the user to download and view logs in the Bulk Edit app.
- **Bulk edit: In app - Edit inventory records** This permission allows the user to edit a field in multiple inventory records in the Bulk Edit app.
- **Bulk edit: In app - View inventory records** This permission allows the user to view a list of identified inventory records in the Bulk Edit app. 
- **Bulk edit: Local - Edit user records** This permission allows the user to edit a field in multiple identified user records in the Bulk Edit app by uploading a .csv file.
- **Bulk edit: Local - View user records** This permission allows the user to view a list of identified user records in Bulk Edit by uploading a .csv file.


## Supported fields by record type

In the Bulk edit app, the **Fields** available for building a query and displaying as column headings in the preview of matched records depend on the **Record type** selected for the bulk edit. See the appropriate table for more information about supported fields by record type:

- [Inventory - holdings](#inventory---holdings)
- [Inventory - instances](#inventory---instances)
- [Inventory - items](#inventory---items)
- [Users](#users)

### Inventory - holdings

| *Field name* in Bulk edit app | Available for Build query? | Available as column heading in preview of matched records? |
| :----- | :-----: | :-----: | 
| *Holdings effective library code* | YES | YES |
| *Holdings effective library ID* | NO | YES |
| *Holdings effective library name* | YES | YES |
| *Holdings effective location* | YES | YES |
| *Holdings effective location ID* | NO | YES |
| *Holdings HRID* | YES | YES |
| *Holdings ID* | YES | YES |
| *Holdings permanent location* | YES | YES | 
| *Holdings permanent location ID* | NO | YES |
| *Holdings statistical code ID list* | NO | YES |
| *Holdings statistical code list* | NO | YES |
| *Holdings suppress from discovery* | YES | YES |
| *Holdings temporary location* | YES | YES |
| *Holdings temporary location ID* | NO | YES |
| *Instance UUID* | NO | YES | 

### Inventory - instances

| *Field name* in Bulk edit app | Available for Build query? | Available as column heading in preview of matched records? |
| :----- | :-----: | :-----: |
| *Instance statistical code list* | NO | YES | 
| *Instance cataloged date* | YES | YES | 
| *Instance contributor name type ID list* | NO | YES |
| *Instance contributor name type list* | NO | YES |
| *Instance contributor type ID list* | NO | YES |
| *Instance contributor type list* | NO | YES |
| *Instance created date* | YES | YES |
| *Instance HRID* | YES | YES |
| *Instance language* | NO | YES | 
| *Instance mode of issuance* | YES | YES | 
| *Instance mode of issuance ID* | NO | YES |
| *Instance resource title* | YES | YES |
| *Instance source* | YES | YES |
| *Instance statistical code ID list* | NO | YES |
| *Instance status* | YES | YES |
| *Instance status ID* | NO | YES |
| *Instance suppress from discovery* | YES | YES |
| *Instance updated date* | YES | YES | 
| *Instance UUID* | YES | YES | 

### Inventory - items

| *Field name* in Bulk edit app | Available for Build query? | Available as column heading in preview of matched records? |
| :----- | :-----: | :-----: |
| *Holdings ID* | YES | YES
| *Instance created date* | YES | YES |
| *Instance ID* | YES | YES | 
| *Instance primary contributor* | YES | YES |
| *Instance title* | YES | YES | 
| *Instance updated date* | YES | YES |
| *Item barcode* | YES | YES | 
| *Item call number* | YES | YES |
| *Item call number type ID* | NO | YES | 
| *Item call number type name* | YES | YES |
| *Item copy number* | NO | YES | 
| *Item created date* | NO | YES | 
| *Item effective call number* | NO | YES |
| *IItem effective call number type ID* | NO | YES |
| *Item effective call number type name* | NO | YES |
| *Item effective library code* | YES | YES |
| *Item effective library ID* | NO | YES |
| *Item effective library name* | YES | YES |
| *Item effective location ID* | NO | YES |
| *Item effective location name* | YES | YES |
| *Item hrid* | YES | YES |
| *Item ID* | YES | YES |
| *Item material ID* | NO | YES |
| *Item material type* | YES | YES |
| *Item permanent ID* | NO | YES |
| *Item permanent location name* | YES | YES |
| *Item statistical code ID list* | NO | YES |
| *Item statistical code list* | NO | YES |
| *Item status* | YES | YES | 
| *Item temporary ID* | NO | YES |
| *Item temporary location name* | YES | YES |
| *Item updated date* | YES | YES |

### Users

| *Field name* in Bulk edit app | Available for Build query? | Available as column heading in preview of matched records? |
| :----- | :-----: | :-----: |
| *User active* | YES | YES |
| *User address ID list* | NO | YES |
| *User address list (line 1)* | NO | YES |
| *User address list (line 2)* | NO | YES |
| *User address type list* | NO | YES |
| *User barcode* | YES | YES |
| *User city list* | NO | YES |
| *User country ID list* | NO | YES |
| *User created date* | YES | YES |
| *User date of birth* | YES | YES |
| *User department ID list* | NO | YES |
| *User department list* | NO | YES |
| *User email* | YES | YES |
| *User enrollment date* | YES | YES |
| *User expiration date* | YES | YES |
| *User external system ID* | YES | YES |
| *User first name* | YES | YES |
| *User ID* | YES | YES |
| *User last name* | YES | YES |
| *User middle name* | YES | YES |
| *User mobile phone* | YES | YES |
| *User patron group* | YES | YES |
| *User patron group ID* | NO | YES |
| *User phone* | YES | YES |
| *User postal code list* | NO | YES |
| *User preferred contact type* | YES | YES |
| *User preferred first name* | YES | YES |
| *User primary address* | YES | YES |
| *User region list* | NO | YES |
| *User updated date* | YES | YES |
| *Username* | YES | YES |


## Identify records for bulk edit

The Bulk edit app provides two methods for setting criteria and identifying records for bulk edit: **Identifier** and **Query**.  In either method, the **Record identifiers** or **Fields** available for selection are based on the **Record type**.

### Identifier

The **Identifier** approach allows the user to set criteria for the bulk edit by uploading a list of record identifiers from a .csv file.

To set criteria for bulk edit using **Identifier**:

1. In the **Set Criteria** pane, select the **Identifier** button.
2. Select the **Record type**. The following **Record types** are available for bulk edit:

   - Inventory - holdings
   - Inventory - instances
   - Inventory - items
   - Users

3. Select the **Record identifier** from the **Select record identifier** drop-down menu. [Record identifiers available for selection](#record-identifiers-by-record-type) are based on the Record type.
4. **Drag and drop** your .csv file into the **Select a file with record identifiers** box, or click **or choose file** to upload the .csv file from your computer. Only .csv files containing one column of record identifiers are accepted for upload in the Bulk edit app. If the .csv file contains more than one column, the upload will not be successful and an error message, *_filename_ is formatted incorrectly. Please correct the formatting and upload the file again* displays.

#### Record identifiers by record type

In the **Identifier** method, the **Record identifiers** available for selection are based on the selected **Record type**.

| Record Type | Record identifier |
| :----- | :----- |  
| *Inventory - holdings* | Holdings UUIDs |
| *Inventory - holdings* | Holdings HRIDs |
| *Inventory - holdings* | Instance HRIDs |
| *Inventory - holdings* | Item barcodes |
| *Inventory - instances* | Instance UUIDs |
| *Inventory - instances* | Instance HRIDs |
| *Inventory - items* | Item barcode |
| *Inventory - items* | Item UUIDs |
| *Inventory - items* | Item HRIDs |
| *Inventory - items* | Item former identifier |
| *Inventory - items* | Item accession number |
| *Inventory - items* | Holdings UUID |
| *Users* | User UUIDs |
| *Users* | User Barcodes |
| *Users* | External IDs |
| *Users* | Usernames |

### Query

The **Query** function in the Bulk Edit app allows the user to build a query to identify records for bulk edit. The **Fields** available for building a query are based on the selected **Record type**. The **Fields** available for building a query are based on the selected **Record type**. See [Supported fields by record type](#supported-fields-by-record-type) for more information. 


#### Build a query to identify records

To set criteria and identify records for bulk edit using the **Query** method:

1. In the **Set Criteria** pane, click on the **Query** tab.
2. Select the **Record type**. The Bulk edit app allows changes to these **Record types**:
   
   - Inventory - holdings
   - Inventory - instances
   - Inventory - items
   - Users

3. Click the **Build query** button to open the **Build query** modal.
4. Select a **Field** from the *Select field* drop-down menu or filter the selection by typing the field in the *Filter options list* text box. The **Fields** available for selection are based on the selected **Record type**. See [Supported fields by record type](#supported-fields-by-record-type) for more information.  
5. Select an **Operator** from the *Select operator* drop-down list. The **Operators** available for selection are based on the **Field**.

| Operator | Meaning |
| :----- | :----- |
| == | Field equals selected or input value. |
| != | Field does not equal selected or input value. |
| > | Field is greater than the selected or input value. |
| < | Field is less than the selected or input value. |
| >= | Field is greater than or equal to the selected or input value. |
| <= | Field is less than or equal to the selected or input value. |
| *contains* | Field appears in selected or input value. |
| *starts with* | Field starts with selected or input value. |
| *is null/empty* | Field is blank; the field does not contain any data. |

6. Select a **Value** from the *Select value* drop-down list or type the value in the text box.  The values available for selection are based on the **Field** and **Operator**.
7. Click on the **+ icon** to add additional lines to the query or click on the **trash can icon** to delete a line from the query.
8. Once a query is built, it must be tested before the query can be run and saved. Click the **Test query** button to run the query and display a preview of matched records. The query string can be edited in the **Query string** field. If edited, another Test query must be done.
9. If the Test query is successful, click the **Run query** button to run the query and preview the matched records in the **Bulk edit query** modal.

### Preview matched records

If the **Identifier** method is used to identify records for bulk edit, the number of records matched and the filename display at the top of the **Bulk edit** modal. 

If the **Query** method is used to identify records for bulk edit, a **Test query** displays the query string and number of matched records at the top of the **Build query** modal. If the query is run, the **Query** and a preview of matched records display in the **Bulk edit query** modal.

To add or remove **Field** columns in the preview pane:

1. Click the **Actions** button.
2. In the **Show columns** section of the Actions menu, check the box next to the name of the **Field** to include as a column heading in the preview. The **Fields** available to display as column headings depend on the record type selected for the bulk edit. See [Supported fields by record type](#supported-fields-by-record-type) for more information.
3. Uncheck the box next to the name of the **Field** to remove the column from the preview.

### Download matched records

If desired, download the matched records as a .csv file:

In the **Preview** pane, click **Actions** and select **Download matched records (CSV)**.
Depending on the web browser settings, the .csv file may be opened and/or saved. 

### Download errors

If there are errors in the matched records, a message indicating the filename, number of entries, number of records matched, and number of errors displays in a two-column table in the **Errors** section. 

**Record identifier.** The record identifier for the records that produced the error.
**Reason for error.** The reason why the error was produced.

To download the list of errors as a .csv file, follow these steps:

In the **Preview** pane, select **Actions > Download errors (CSV)**.
Depending on the web browser settings, the .csv file may be opened and/or saved. 

## Bulk edit by record type

### Inventory - holdings

In the Bulk edit app, the **Fields** that can be changed in Holdings records include:

   - **Administrative note**
   - **Electronic access**
   - **Holdings location**
   - **Holdings notes**
   - **Suppress from discovery**.

To identify **Holdings** records for bulk edit:

In the **Set criteria** pane, ensure **Record types** is set to **Inventory-holdings**.
[Identify holdings records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method. 
[Preview the list of matched holdings records](#preview-matched-records) in the **Preview of record matched** pane.
(Optional): [Download the matched holdings records](#download-matched-records) as a .csv file.
(Optional): [Download errors in matched holdings records](#download-errors) as a .csv file.

Once **Holdings** records are identified, you can start a bulk edit on the matching records. The **Options** and **Actions** available to perform the bulk edit vary for each **Field**.

#### Administrative note

To bulk edit the **Administrative note** field in the matched **Holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Administrative note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Administrative note** field:

| Options | Actions | Data | Actions | Data |
| :----- | :----- | :----- | :----- | :----- |
| *Administrative note* | Add note | Text field | - | - |
| *Administrative note* | Change note type | Select note type | - | - |
| *Administrative note* | Find (full field search) | Text field | Remove | - |
| *Administrative note* | Find (full field search) | Text field | Replace with | Text field |
| *Administrative note* | Remove all | - | - | - |
   
4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Holdings** records.


#### Electronic access

To bulk edit the **Electronic access** field in the matched **Holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Electronic access** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Electronic access** field:

| Options | Actions | Data | Actions | Data |
| :-----  | :----- | :----- | :----- | :----- |
| *Electronic access - Link text* | Clear field | - | - | - |
| *Electronic access - Link text* | Find (full field search) | Text field | Remove | - |
| *Electronic access - Link text* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - Link text* | Replace with | Text field | - | - |
| *Electronic access - Materials specified* | Clear field | - | - | - |
| *Electronic access - Materials specified* | Find (full field search) | Text field | Remove | - |
| *Electronic access - Materials specified* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - Materials specified* | Replace with | Text field | - | - |
| *Electronic access - URI* | Clear field | - | - | - |
| *Electronic access - URI* | Find (full field search) | Text field | Remove | - |
| *Electronic access - URI* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - URI* | Replace with | Text field | - | - |
| *Electronic access - URL public note* | Clear field | - | - | - |
| *Electronic access - URL public note* | Find (full field search) | Text field | Remove | - |
| *Electronic access - URL public note* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - URL public note* | Replace with | Text field | - | - |
| *Electronic access - URL Relationship* | Clear field | - | - | - |
| *Electronic access - URL Relationship* | Find (full field search) | Text field | Remove | - |
| *Electronic access - URL Relationship* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - URL Relationship* | Replace with | Text field | - | - |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Holdings** records.

#### Holdings location

To bulk edit the **Holdings location** in the matched **Holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Holdings location** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Holdings location** field:

| Options | Actions | Data | 
| :-----  | :----- | :----- | 
| *Holdings location - Permanent holdings location* | Replace with (pre-selected) | Select location or Location lookup |
| *Holdings location - Temporary holdings location* | Clear field | - | 
| *Holdings location - Temporary holdings location* | Replace with | Select location or Location lookup | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Holdings** records.

#### Holdings notes

To bulk edit a **Holdings note** in the matched **Holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select a **Holdings note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Holdings location** field:

| Options | Actions | Data | Actions | Data |
| :----- | :----- | :----- | :----- | :----- |
| *Holdings notes - Action note*| Add note | Text field | - | - |
| *Holdings notes - Action note* | Change note type | Select note type | - | - |
| *Holdings notes - Action note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Action note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Action note* | Mark as staff only | - | - | - |
| *Holdings notes - Action note* | Remove all | - | - | - |
| *Holdings notes - Action note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Binding*| Add note | Text field | - | - |
| *Holdings notes - Binding* | Change note type | Select note type | - | - |
| *Holdings notes - Binding* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Binding* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Binding* | Mark as staff only | - | - | - |
| *Holdings notes - Binding* | Remove all | - | - | - |
| *Holdings notes - Binding* | Remove mark as staff only | - | - | - |
| *Holdings notes - Check note* | Add note | Text field | - | - |
| *Holdings notes - Check note* | Change note type | Select note type | - | - |
| *Holdings notes - Check note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Check note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Check note* | Mark as staff only | - | - | - |
| *Holdings notes - Check note* | Remove all | - | - | - |
| *Holdings notes - Check note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Copy note* | Add note | Text field | - | - |
| *Holdings notes - Copy note* | Change note type | Select note type | - | - |
| *Holdings notes - Copy note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Copy note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Copy note* | Mark as staff only | - | - | - |
| *Holdings notes - Copy note* | Remove all | - | - | - |
| *Holdings notes - Copy note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Electronic bookplate* | Add note | Text field | - | - |
| *Holdings notes - Electronic bookplate* | Change note type | Select note type | - | - |
| *Holdings notes - Electronic bookplate* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Electronic bookplate* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Electronic bookplate* | Mark as staff only | - | - | - |
| *Holdings notes - Electronic bookplate* | Remove all | - | - | - |
| *Holdings notes - Electronic bookplate* | Remove mark as staff only | - | - | - |
| *Holdings notes - External note* | Add note | Text field | - | - |
| *Holdings notes - External note* | Change note type | Select note type | - | - |
| *Holdings notes - External note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - External note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - External note* | Mark as staff only | - | - | - |
| *Holdings notes - External note* | Remove all | - | - | - |
| *Holdings notes - External note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Identity note* | Add note | Text field | - | - |
| *Holdings notes - Identity note* | Change note type | Select note type | - | - |
| *Holdings notes - Identity note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Identity note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Identity note* | Remove all | - | - | - |
| *Holdings notes - Identity note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Note* | Add note | Text field | - | - |
| *Holdings notes - Note* | Change note type | Select note type | - | - |
| *Holdings notes - Note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Note* | Mark as staff only | - | - | - |
| *Holdings notes - Note* | Remove all | - | - | - |
| *Holdings notes - Note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Process Note* | Add note | Text field | - | - |
| *Holdings notes - Process Note* | Change note type | Select note type | - | - |
| *Holdings notes - Process Note* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Process Note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Process Note* | Mark as staff only | - | - | - |
| *Holdings notes - Process Note* | Remove all | - | - | - |
| *Holdings notes - Process Note* | Remove mark as staff only | - | - | - |
| *Holdings notes - Provenance* | Add note | Text field | - | - |
| *Holdings notes - Provenance* | Change note type | Select note type | - | - |
| *Holdings notes - Provenance* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Provenance* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Provenance* | Mark as staff only | - | - | - |
| *Holdings notes - Provenance* | Remove all | - | - | - |
| *Holdings notes - Provenance* | Remove mark as staff only | - | - | - |
| *Holdings notes - Reproduction* | Add note | Text field | - | - |
| *Holdings notes - Reproduction* | Change note type | Select note type | - | - |
| *Holdings notes - Reproduction* | Find (full field search) | Text field | Remove | - |
| *Holdings notes - Reproduction* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Reproduction* | Mark as staff only | - | - | - |
| *Holdings notes - Reproduction* | Remove all | - | - | - |
| *Holdings notes - Reproduction* | Remove mark as staff only | - | - | - |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Holdings** records.

#### Suppress from discovery

To bulk edit the **Suppress from discovery** field in the matched **Holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select  **Suppress from discovery** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Suppress from discovery** field:

| Options | Actions | 
| :----- | :----- | 
| *Suppress from discovery* | Set false | 
| *Suppress from discovery* | Set true | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Holdings** records.

### Inventory - instances

In the Bulk edit app, the fields that can be changed in **Instance** records include:

   - **Staff suppress**
   - **Suppress from discovery**.


To identify **Instance** records for bulk edit:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory-instances**.
2. [Identify holdings records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matched holdings records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched holdings records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in matched holdings records](#download-errors) as a .csv file.

Once **Instance** records are identified, you can start a bulk edit on the matching records. The **Options** and **Actions** available to perform the bulk edit vary for each **Field**.


#### Staff suppress

To bulk edit the **Staff suppress** field in the matched **Instance** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select  **Staff suppress** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Staff suppress** field:

| Options | Actions |
| :----- | :-----|
| *Staff suppress* | Set false |
| *Staff suppress* | Set true |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Instance** records.

#### Suppress from discovery

To bulk edit the **Suppress from discovery** field in the matched **Instance** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select  **Suppress from discovery** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Suppress from discovery** field:

| Options | Actions | 
| :-----  | :----- | 
| *Suppress from discovery* | Set false | 
| *Suppress from discovery* | Set true | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Instance** records.

### Inventory - items

In the Bulk edit app, the fields that can be changed in **Item** records include:

   - **Administrative note**
   - **Check in note**
   - **Check out note**
   - **Item note**
   - **Item status**
   - **Loan type**
   - **Location**
   - **Suppress from discovery**

To identify **Item** records for bulk edit:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory-items**.
2. [Identify holdings records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matched holdings records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched holdings records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in matched holdings records](#download-errors) as a .csv file.

Once **Item** records are identified, you can start a bulk edit on the matching records. The **Options** and **Actions** available to perform the bulk edit vary for each **Field**.


#### Administrative note 

To bulk edit the **Administrative note** in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Administrative note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Administrative note** field:

| Options | Actions | Data | Actions | Data |
| :-----  | :----- | :----- | :----- | :----- |
| *Administrative note* | Add note | Text field | - | - |
| *Administrative note* | Change note type | Select note type | - | - |
| *Administrative note* | Find (full field search) | Text field | Remove | - |
| *Administrative note* | Find (full field search) | Text field | Replace with | Text field |
| *Administrative note* | Remove all | - | - | - |
   
4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Check in note

To bulk edit the **Check in note** in the matched **Item** records:
1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Check in note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Check in note** field:

| Options | Actions | Data | Actions | Data |
| :-----  | :----- | :----- | :----- | :----- |
| *Check in note* | Add note | Text field | - | - |
| *Check in note* | Change note type | Select note type | - | - |
| *Check in note* | Duplicate to | Check out note (pre-selected) | - | - |
| *Check in note* | Find (full field search) | Text field | Remove | - |
| *Check in note* | Find (full field search) | Text field | Replace with | Text field |
| *Check in note* | Mark as staff only | - | - | - |
| *Check in note* | Remove all | - | - | - | 
| *Check in note* | Remove mark as staff only | - | - | - | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Check out note

To bulk edit the **Check out note** in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Check in note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Check in note** field:

| Options | Actions | Data | Actions | Data |
| :-----  | :----- | :----- | :----- | :----- |
| *Check out note* | Add note | Text field | - | - |
| *Check out note* | Change note type | Select note type | - | - |
| *Check out note* | Duplicate to | Check out note (pre-selected) | - | - |
| *Check out note* | Find (full field search) | Text field | Remove | - | - |
| *Check out note* | Find (full field search) | Text field | Replace with | Text field |
| *Check out note* | Mark as staff only | - | - | - | 
| *Check out note* | Remove all | - | - | - | 
| *Check out note* | Remove mark as staff only | - | - | - | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Item notes

The following types of **Item notes** may be changed in the Bulk edit app:

   - **Action note**
   - **Binding**
   - **Copy note**
   - **Electronic bookplate**
   - **Note**
   - **Provenance**
   - **Reproduction**

To bulk edit the **Item note** field in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select the type of **Item note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Item note** field:
 
| Options | Actions | Data | Actions | Data |
| :----- | :----- | :----- | :----- | :----- |
| *Action note* | Add note | Text field | - | - |
| *Action note* | Change note type | Select item note | - | - |
| *Action note* | Find (full field search) | Text field | Remove | - |
| *Action note* | Find (full field search) | Text field | Replace with | Text field |
| *Action note* | Mark as staff only | - | - | - | 
| *Action note* | Remove all | - | - | - | 
| *Action note* | Remove mark as staff only | - | - | - | 
| *Binding* | Add note | Text field | - | - |
| *Binding* | Change note type | Select item note | - | - |
| *Binding* | Find (full field search) | Text field | Remove | - |
| *Binding* | Find (full field search) | Text field | Replace with | Text field |
| *Binding* | Mark as staff only | - | - | - | 
| *Binding* | Remove all | - | - | - | 
| *Binding* | Remove mark as staff only | - | - | - | 
| *Copy note* | Add note | Text field | - | - |
| *Copy note* | Change note type | Select item note | - | - |
| *Copy note* | Find (full field search) | Text field | Remove | - |
| *Copy note* | Find (full field search) | Text field | Replace with | Text field |
| *Copy note* | Mark as staff only | - | - | - | 
| *Copy note* | Remove all | - | - | - | 
| *Copy note* | Remove mark as staff only | - | - | - | 
| *Electronic bookplate* | Add note | Text field | - | - |
| *Electronic bookplate* | Change note type | Select item note | - | - |
| *Electronic bookplate* | Find (full field search) | Text field | Remove | - |
| *Electronic bookplate* | Find (full field search) | Text field | Replace with | Text field |
| *Electronic bookplate* | Mark as staff only | - | - | - | 
| *Electronic bookplate* | Remove all | - | - | - | 
| *Electronic bookplate* | Remove mark as staff only | - | - | - | 
| *Note* | Add note | Text field | - | - |
| *Note* | Change note type | Select item note | - | - |
| *Note* | Find (full field search) | Text field | Remove | - |
| *Note* | Find (full field search) | Text field | Replace with | Text field |
| *Note* | Mark as staff only | - | - | - | 
| *Note* | Remove all | - | - | - | 
| *Note* | Remove mark as staff only | - | - | - |
| *Provenance* | Add note | Text field | - | - |
| *Provenance* | Change note type | Select item note | - | - |
| *Provenance* | Find (full field search) | Text field | Remove | - |
| *Provenance* | Find (full field search) | Text field | Replace with | Text field |
| *Provenance* | Mark as staff only | - | - | - | 
| *Provenance* | Remove all | - | - | - | 
| *Provenance* | Remove mark as staff only | - | - | - |
| *Reproduction* | Add note | Text field | - | - |
| *Reproduction* | Change note type | Select item note | - | - |
| *Reproduction* | Find (full field search) | Text field | Remove | - |
| *Reproduction* | Find (full field search) | Text field | Replace with | Text field |
| *Reproduction* | Mark as staff only | - | - | - | 
| *Reproduction* | Remove all | - | - | - | 
| *Reproduction* | Remove mark as staff only | - | - | - |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Item status

To bulk edit the **Item status** field in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Item status** from the drop-down list.
3. Select the **Item status** you want to apply from the drop-down list. The following options are available for **Item status**: 

   - Available
   - Withdrawn
   - Missing
   - In process (non-requestable)
   - Intellectual item
   - Long missing
   - Restricted
   - Unavailable
   - Unknown

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Loan type

To bulk edit the **Loan type** field in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Loan type** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Loan type** field:

| Options | Actions | Data | 
| :----- | :----- | :----- | 
| *Permanent loan type* | Replace with (pre-selected) | Select loan type |
| *Temporary loan type* | Clear field | - |
| *Temporary loan type* | Replace with | Select loan type |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Item** records.

#### Location

To bulk edit the **Location** field in the matched **Item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select type of **Location** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Location** field:

| Options | Actions | Data | 
| :----- | :----- | :----- | 
| *Permanent item location* | Clear field | - | 
| *Permanent item location* | Replace with | Select Item location (drop-down menu) or Location lookup | 
| *Temporary item location* | Clear field | - |
| *Temporary item location* | Replace with | Select Item location (drop-down menu)  or Location lookup |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.

8. Click **Commit changes** to save the changes to the matched **Item** records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

#### Suppress from discovery

To bulk edit the **Suppress from discovery** field in the matched **Item** records:


1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select  **Suppress from discovery** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Suppress from discovery** field:

| Options | Actions | 
| :----- | :----- | 
| *Suppress from discovery* | Set false | 
| *Suppress from discovery* | Set true | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device. 

8. Click **Commit changes** to save the changes to the matched **Inventory-item** records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

### Users

The **Query** method allows bulk edit to only the **Email**, **Expiration date**, and **Patron group** fields in a user record. 
The **Identifier** method allows bulk edit to be performed on all fields of a user record.

To identify **User** records for bulk edit:

1. In the **Set criteria** pane, ensure **Record types** is set to **Users**.
2. [Identify user records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matching user records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional; Identifier method only): [Download the matched user records](#download-matched-records) as a .csv file.
5. (Optional; Identifier method only): [Download errors in matched user records](#download-errors) as a .csv file.

#### Start bulk edit

The **Start bulk edit** approach allows bulk edit to change the **Email**, **Expiration Date**, and/or **Patron Group** fields in matching user records. Bulk edit may be performed on each of these fields individually or simultaneously. 

To perform bulk edit on the matched **User** records using the **Start bulk edit** method:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select  **Email**, **Expiration date**, or **Patron group** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Email**, **Expiration date**, and **Patron group** fields of user records:

| Options | Actions | Data | Actions | Data |
| :----- | :----- | :----- | :----- | :----- |
| **Email** | Find (pre-selected) | Text field | Replace with | Text field |
| **Expiration date** | Replace with | Text field (MM/DD/YYYY or Calendar picker) | - | - |
| **Patron group** | Replace with | Select Patron group | - | - | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
     
8. Click **Commit changes** to save the changes to the matched **User** records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

### Start bulk edit (Local)

The **Start bulk edit (Local)** function allows the user to perform a bulk edit on user records edited locally (external to FOLIO) by uploading a .csv file of the changed, or edited, user records. 

Any field in user records can be changed using the **Bulk edit (Local)** approach.

To perform bulk edit on user records using the **Start bulk edit (Local)** approach: 

1. In the **Set criteria** pane, select **Users** as the **Record type** and select the appropriate **Record identifier**: **User UUIDs**, **User barcodes**, **External IDs**, or **Usernames**.
2. Upload a .csv file with the selected Record identifier by either using the **Drag and drop** option or clicking the **Choose file** button.
3. Select **Actions \> Download matched records (CSV)** to download a .csv file of matched user records; or select **Actions \> Download errors (CSV)** to download a .csv file of records that did not match your selected record identifier.
4. Edit the downloaded .csv file and make changes to the user records in the file itself. Save the edited .csv file to your computer.
5. Select **Actions \> Start bulk edit (Local)**.
6. In the **Bulk edit** window, **Drag and drop** the .csv file into the **Upload CSV file with edited records** box, or click **or choose file** to upload the .csv file from your computer. If the .csv file is uploaded successfully, the confirmation message, *_filename.csv_ successfully uploaded*, displays in a new window.
7. Click **Next**. The warning message, *(Number of) records will be updated if the **Commit changes** button is clicked.* appears in a new window.
8. Click **Commit changes**. Bulk edit will apply the local changes to the matched **User** records in FOLIO.

## Logs

The Bulk edit app allows users to preview **bulk edit logs** based on set criteria and download a file associated with a bulk edit job. 

### Preview bulk edit logs

The options available for setting criteria include: **Statuses**, **Record types**, **Started**, **Ended**, and **User**.  

To set criteria and preview bulk edit logs:

1. Click on the **Logs** tab in the **Set criteria** pane.
2. Under the **Statuses** accordion, select the status for the bulk edit log by checking the appropriate box:  

   - **New**
   - **Retrieving records**
   - **Saving records**
   - **Data modification**
   - **Reviewing changes**
   - **Completed**
   - **Completed with errors**
   - **Failed**  

3. Under the **Record types** accordion, select the record type for the bulk edit log by checking the appropriate box: 

   - **Inventory - holdings**
   - **Inventory - instances**
   - **Inventory - items**
   - **Users**

4. In the **Started** accordion, use the **calendar icon** or type in the date using the YYYY-MM-DD format in the **From** and **To** fields to limit the preview by the start date of the bulk edit. Click **Apply**.
5. In the **Ended** accordion, use the **calendar icon** or type in the date using the YYYY-MM-DD format in the **From** and **To** fields to limit the preview by the end date of the bulk edit. Click **Apply**.
6. In the **Users** accordion, select the user, or FOLIO account, that ran the bulk edit job from the **Choose user** drop-down list.
7. A preview list of bulk edit logs displays in the **Bulk edit logs** pane. The number of bulk edit logs in the preview displays at the top of the pane as *(number of) records found*. The column headings display the following criteria for each bulk edit log: 

   - **Record type**: type of records changed in the bulk edit job
   - **Status**: status of the bulk edit job
   - **Editing**: method of bulk edit used
   - **# of records**: number of records retrieved for bulk edit job
   - **Processed**: number of records changed in bulk edit job
   - **Started**: start date and start time of bulk edit job
   - **Ended**: end date and end time of bulk edit job
   - **Run by**: user or FOLIO account used to run the bulk edit job
   - **ID**: system-generated number assigned to the bulk edit job

### Download a bulk edit log file

In the Bulk edit app, a file used to run a bulk edit job can be downloaded and saved from the **Bulk edit logs** pane.

To download a file associated with a bulk edit log:

1. In the **Bulk edit logs** pane, click on the **ellipses** in the **Actions** column next to the appropriate Bulk edit log.
2. Select the appropriate action from the **Download** drop-down list. The types of files available for download include: 

   - **File that was used to trigger the bulk edit**
   - **File with the matching records**
   - **File with errors encountered during the record matching**

3. Depending on the web browser settings, the file can be opened and/or saved to your computer. 


