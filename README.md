# Changelog

## Version 1.2.1 - 17/08/2023

* Allow Franchisees to drag dogs into the left column. It will reconstruct itself (and any of the formatting), so they can safely drag them to that column to remove them from the right side.
* Walk Date now has the day ("Thursday" etc) displayed on Staff Sheets and the Planner Sheet.
* Added **automatic back-ups** for all Staff Spreadsheets.

## Version 1.2.0 - 16/08/2023

* Add more protected cells.
* Improve formatting repropagation behaviour on changes occurring eg. accidentally modifying or deleting certain cells.
* Display which dogs have been dragged into the Staff Planner with a ~~strikethrough~~ effect.
* Display a modifiable **Walk Date** section that propagates across all Staff sheets, to indicate the date of the organised walks.
* Improve colour scheme on individual staff sheets.
* Fix a bug where the "Reset" button on individual staff sheets would sometimes only partially reset data.

## Version 1.1.1b - 30/08/2022

* Hotfix for incorrect Early Walk OK form behaviour.
* Modified formatting for the template Day Planner columns.

## Version 1.1.1 - 26/08/2022

### Bugfixes

* Fixed an issue where the Dog Form failed to push TRUE/FALSE values to the Dogs sheet.
* Fixed an issue where editing row 7 in the "Parks" tab would attempt to submit the **Add Dogs** form.

### Minor Changes

* Added 150 additional rows to the Staff Planner sheet to allow for more listings.

## Version 1.1.0 - 25/08/2022

### Bugfixes

* Fixed an issue where the Staff Planner would copy contents from the incorrect sheet when rolling back changes.
* Fixed an issue where Staff deletion would sometimes not remove the corresponding column.
* Fixed an issue where Notes would not sync due to the Staff member sheet losing their column ID.

### Minor Changes

* Replaced the textbox submission in the "Add Dogs" form with a large checkbox, which, when ticked, submits the form.
* Modified how and when Notes are updated - this should result in more performant and frequent updates.
* Modifed how Staff members are added to include their relevant column ID immediately - this should result in more responsive Note updates as well.
* Added a version number to the top of the Sync sheet in order to keep tabs on the most recent sheet.
* Added some protected ranges to the Dogs sheet.

## Version 1.0.1 - 19/08/2022

### Major Changes

* Added rollback code to nearly all sheets, copying data from a template when destructive edits are made.
* Added some protected ranges.
* Unlisted: multiple changes to the Sync/Staff UIs.
