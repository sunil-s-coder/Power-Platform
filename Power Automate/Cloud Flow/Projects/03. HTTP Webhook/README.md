# Webhook Connector

This Power Automate flow demonstrates how webhooks work.

---

## Project Description

The flow runs automatically when a new email arrives in a specified Outlook folder. It performs the following actions:

1. **Subscription:** The flow makes a subscription call to [Webhook.site](https://webhook.site/) using an auto-generated callback URL.
2. **Callback:** A client (e.g., VS Code) makes an API call to the **callback URL** from the subscription request with an acknowledgement message.
3. **Unsubscription:** After receiving the acknowledgement, the flow makes an **unsubscription** call back to [Webhook.site](https://webhook.site/) to clean up.

---

## Connectors Used

- [HTTP Connector](https://learn.microsoft.com/en-us/training/modules/http-connectors)  

---

## Flow Diagram
> Below is a visual representation of the flow steps in Power Automate

![Process-Flow](images/01.%20PA%20flow.png)

---

## Trigger

- Manual trigger

---

## Files Included

| File/Folder         | Description                                 |
|---------------------|---------------------------------------------|
| `flow-package/`     | Contains the exported Power Automate flow (`.zip`) |
| `images/`           | Screenshots of the flow for reference       |
| `README.md`         | Project documentation                       |

---

## How to Import and Use the Flow

1. Download the `.zip` file from the `flow-package/` folder.
2. Go to [Power Automate](https://make.powerautomate.com/).
3. Click **"My Flows"** → **"Import"**.
4. Upload the flow `.zip` file.
5. Reconnect the required connectors (Outlook, HTTP).
6. Configure:
   - Go to [Webhook.site](https://webhook.site/)
   - Copy your **unique URL** and use it in the exercise.

---

## Requirements

- Microsoft Power Automate account
- Basic knowledge of Power Automate to modify and extend the flow

---

## Sample Images

- **01. Webhook Subscription:**  
![Webhook Subscription](images/02.%20Webhook%20Subscription%20Image.png)

- **02. Webhook Callback via VSCode:**  
![Webhook Callback via VSCode](images/04.%20Webhook%20Callback%20from%20VSCode%20Image.png)

- **03. Webhook Callback Output:**  
![Webhook Callback Output](images/05.%20Webhook%20Callback%20Output%20Image.png)

- **04. Webhook Unsubscription:**  
![Webhook Unsubscription](images/03.Webhook_Unsubscription_Image.png)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

Created by **Sunil Sridharmurthy**  
Connect on [LinkedIn](https://www.linkedin.com/in/sunil-sridharmurthy)
