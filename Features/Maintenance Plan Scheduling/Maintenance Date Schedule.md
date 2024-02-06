## Maintenance Plan Scheduling Feature Preview
![Scheduling](https://github.com/JakePatolilic/vsulib-ms/assets/114040840/c7a62b74-f215-42d6-8a8a-467ce0dd0dd4)
## Schedule the Date of Maintenance
This is used to record when the Technician is supposed to fix the equipment.
### Input
-	The library staff user shall set the proposed schedule date of maintenance.
### Process
-	The library staff user shall press the maintenance button.
-	The library staff user shall find the equipment that needs maintenance
-	The library staff user shall click the equipment.
-	The library staff user shall click the proposed date.
-	The library staff user shall set the date when the equipment will undergo maintenance.
-	The library staff user shall click the add image to add the damage part.
-	The library staff user shall click the actual date.
-	The library staff user shall choose the actual date of maintenance.
-	The library staff shall record the feedback.
### Output
-	The date set will be shown in the Maintenance Plan for Equipment.
### Data Dictionary
| Element ID                   | Element Text          | Element Type     | Data Type | Required? | Rules                  |
|------------------------------|-----------------------|------------------|-----------|-----------|------------------------|
| ScheduleSideBarButton        | Schedule              | Button           | Button    |           |                        |
| ScheduleFloorNameText       | First Floor           | Link             | Button    |           |                        |
| ScheduleFloorNameButton     | First Floor           | Button           | Button    |           |                        |
| SchedulePendingButton       | Pending               | Button           | Button    |           |                        |
| ScheduleAreaLink            | AreaLink              | AreaLink         | AreaLink  |           |                        |
| ScheduleAreNameButton       | AVR Room              | Button           | Button    |           |                        |
| EquipmentLink               | Equipment             | Link             | Button    |           |                        |
| SortEquipmentHeader         | SORT BY               | Header           | String    |           |                        |
| SortButton                  | Name                  | Dropdown Button  | Button    |           |                        |
| EquipmentNumberText         | 01                    | Text             | String    |           |                        |
| EquipmentNameText           | PC Monitor            | Text             | String    |           |                        |
| SpecificationButton         | Specifications       | Button           | Button    |           |                        |
| PartButton                  | Parts                 | Button           | Button    |           |                        |
| SchedulePlanButton          | Calendar icon         | Button           | Button    |           |                        |
| ProposedDateButton          | Proposed Date         | Button           | Button    |           |                        |
| SchedulePoposedLink         | Proposed              | Link             | Button    |           |                        |
| MonthHeader                 | MONTH                 | Text             | String    |           |                        |
| MonthButton                 | January               | Dropdown Button  | Button    |           |                        |
| YearHeader                  | MONTH                 | Text             | String    |           |                        |
| YearButton                  | 2024                  | Dropdown Button  | Button    |           |                        |
| DisplayCalendar             | Calendar              | Calendar         | Calendar  |           |                        |
| SetScheduleButton           | Set Schedule          | Button           | Button    |           |                        |
| ActualDateButton            | Actual Date           | Button           | Button    |           | Proposed date is set.  |
| ScheduleActualLink          | Actual                | Link             | Button    |           |                        |
| DisplayCalendar             | Calendar              | Calendar         | Calendar  |           |                        |
| SetScheduleButton           | Set Schedule          | Button           | Button    |           |                        |
| ConfirmButton               | Confirm               | Button           | Button    |           |                        |
| PartsLink                   | Parts                 | Link             | Button    |           |                        |
| EquipmentPartsHeader        | Equipment Parts       | Header           | String    |           |                        |
| PartsConditionDropdown      | "Working" or "Not Working" | Dropdown Button | Button  |           |                        |
| UpdateButton                | Update                | Button           | Button    |           |                        |
| RemarksHeader               | Remarks               | Header           | String    |           |                        |
| RemarksTextbox              | Lorem ipsum           | Textbox          | String    |           |                        |
| EquipmentStatusHeader       | EquipmentStatus       | Header           | String    |           |                        |
| WorkingHeader               | Working:              | Header           | String    |           |                        |
| WorkingCounter              | 5                     | Text             | Int       |           |                        |
| NotWorkingHeader            | Working:              | Header           | String    |           |                        |
| NotWorkingCounter           | 1                     | Text             | Int       |           |                        |
| StatusHeader                | Status: Needs Repair  | Header           | String    |           |                        |
| PartsNameHeader             | Name                  | Header           | String    |           |                        |
| PartsConditionHeader        | Name                  | Header           | String    |           |                        |
| ListofParts                 | <List of Parts>       | Text             | String    |           |                        |
| ConditionEditButton         | Pen icon              | Button           | Button    |           |                        |
| DoneButton                  | Done                  | Button           | Button    |           |                        |


