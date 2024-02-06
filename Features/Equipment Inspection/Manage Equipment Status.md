# Equipment Inspection
## Manage Equipment Status
This is used by the library staff assigned to this activity in order to record the condition of the equipment.
### Input
-	The library staff user shall change the status or condition of the equipment if necessary.
### Process
-	The library staff user shall press the inspection button.
-	The library staff user shall find the equipment to be inspected
-	The library staff user shall click the equipment.
-	The library staff user shall enter the activity done on the equipment.
-	The library staff user shall choose its findings.
-	The library staff user shall record the remarks of the inspection.
-	The library staff user shall click the add image to add the damage part.
### Output
- The status of the equipment will be changed based on the findings.
### Data Dictionary
| Element ID               | Element Text          | Element Type     | Data Type | Required? | Rules                |
|--------------------------|-----------------------|------------------|-----------|-----------|----------------------|
| EquipmentLink            | Equipment             | Link             | Button    |           |                      |
| SortEquipmentHeader      | SORT BY               | Header           | String    |           |                      |
| SortButton               | Name                  | Dropdown Button  | Button    |           |                      |
| EquipmentNumberText      | 01                    | Text             | String    |           |                      |
| EquipmentNameText        | PC Monitor            | Text             | String    |           |                      |
| InspectButton            | Inspect               | Button           | Button    |           |                      |
| PartsLink                | Parts                 | Link             | Button    |           |                      |
| EquipmentPartsHeader     | Equipment Parts       | Header           | String    |           |                      |
| PartsConditionDropdown   | 'Working' or 'Not Working' | Dropdown Button | Button    |           |                      |
| UpdateButton             | Update                | Button           | Button    |           |                      |
| RemarksHeader            | Remarks               | Header           | String    |           |                      |
| RemarksTextbox           | Lorem ipsum           | Textbox          | String    |           |                      |
| EquipmentStatusHeader    | EquipmentStatus       | Header           | String    |           |                      |
| WorkingHeader            | Working:              | Header           | String    |           |                      |
| WorkingCounter           | 5                     | Text             | Int       |           |                      |
| NotWorkingHeader         | Working:              | Header           | String    |           |                      |
| NotWorkingCounter        | 1                     | Text             | Int       |           |                      |
| StatusHeader             | Status: Needs Repair  | Header           | String    |           |                      |
| PartsNameHeader          | Name                  | Header           | String    |           |                      |
| PartsConditionHeader     | Name                  | Header           | String    |           |                      |
| ListofParts              | <List of Parts>       | Text             | String    |           |                      |
| ConditionEditButton      | Pen icon              | Button           | Button    |           |                      |
| ConfirmationMessage      | Status Updated!       | Text             | String    |           |                      |
| OkButton                 | Ok                    | Button           | Button    |           |                      |

## Preview
<img src="interfaceImages/Inspection.png">
