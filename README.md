# Changelog

## Version 1.1.0 - 25/08/2022

### Bugfixes

* Fixed an issue where the Staff Planner would copy contents from the incorrect sheet when rolling back changes.
* Fixed an issue where Staff deletion would sometimes not remove the corresponding column.

### Minor Changes

* Replaced the textbox submission in the "Add Dogs" form with a large checkbox, which, when ticked, submits the form.
* Added some protected ranges to the Dogs sheet.
* Modified how and when Notes are updated - this should result in more performant and frequent updates.
* Modifed how Staff members are added to include their relevant column ID immediately - this should result in more responsive Note updates as well.
* Added a version number to the top of the Sync sheet in order to keep tabs on the most recent sheet.
