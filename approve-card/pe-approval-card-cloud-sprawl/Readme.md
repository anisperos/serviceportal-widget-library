## Title - Approval / Reject Card

## Description - Use Case

Displays a simple approval card with three buttons - **Accept**, **Reject**, **View**. 

## Screenshots
![alt text](../../images/pe-approve-reject-card.png "Approve Reject Card")

## Additional Information/Notes 
> None
---
## Installation
---
Download and install update set **[pe-approval-cloud-sprawl.u-update-set.xml](pe-approval-cloud-sprawl.u-update-set.xml)** <br/><br/>
After installation, the widget can be accessed via the `Service Portal > Widgets` section for use and customization.<br/>
* SN Product Documentation - ['Load a customization from a single XML file'](https://docs.servicenow.com/search?q=Load+a+customization+from+a+single+XML+file)   (<i>Select appropriate instance version</i>)

---
## Configuration
---
Widget Option Schema parameters:

**"Card Data"** to fill the card with sample data using a JSON object.
```javascript
    {
      "title":"BudgetRequest",
      "sub_title":"Engineering",
      "attention_text":"Tier1",
      "attention_icon":"fa-exclamation-circle",
      "big_text":"$25k",
      "state":"pending",
      "big_text_icon":"coins.png"
    }
```

---
## Platform Dependencies
---
> None
---
## Sample Data and Data Structures
---
> See 'Configuration' above

---
## API Dependencies
---
<i>Dependencies are included and configured as part of the provided Update Set.</i>
> None

---
## CSS/SASS Variables
---
_CSS/SASS variables are given default values that can be overridden with theming or portal-level CSS._
> None