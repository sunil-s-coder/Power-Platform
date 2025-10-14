# Daily Customer Update Flow – Power Automate

This Power Automate flow reads customer details from an Excel table stored in OneDrive and sends daily update emails to each customer using Office 365 Outlook.

---

## Project Description

This flow is scheduled to run **every day at 10:00 AM IST**. It performs the following steps:

1. **Reads customer data** from an Excel Online (Business) table stored in OneDrive.
2. Loops through each row (customer) in the table.
3. Sends a **personalized email** to each customer with relevant updates using Office 365 Outlook.

---

## Connectors Used

- [Recurrence Trigger](https://learn.microsoft.com/en-us/power-automate/run-scheduled-tasks)
- [Excel Online (Business)](https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/)
- [Office 365 Outlook](https://learn.microsoft.com/en-us/connectors/office365/)

---

## Flow Diagram
> Below is a visual of the flow steps in Power Automate

![Flow Screenshot](images/01.%20Code.png)

---

## Schedule

- Runs **automatically** at: `10:00 AM IST daily`
- Trigger type: **Recurrence**

---

## Files Included

| File/Folder         | Description                                |
|---------------------|--------------------------------------------|
| `flow-package/`     | Contains the exported flow as a .zip file  |
| `images/`           | Screenshots of the flow for visual reference |
| `README.md`         | Project overview and documentation         |

---

## How to Import the Flow

1. Download the `.zip` file from the `flow-package/` folder.
2. Go to [Power Automate](https://make.powerautomate.com/).
3. Click on **"Solutions"** (optional, or go directly to **"My flows"**).
4. Click **Import** → Upload the `.zip` file.
5. Reconnect your **Excel Online** and **Outlook** connectors.
6. Set the **Excel file path** and **table name** as needed.

---

## Requirements

- Microsoft Power Automate account
- Excel file stored in OneDrive with a structured table of customer data
- Office 365 Outlook account to send emails

---

## Sample Excel file

![Flow Screenshot](supporting%20files/Customer%20Details.xlsx)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

Created by **Sunil Sridharmurthy**  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/sunil-sridharmurthy) or reach out with questions or feedback.