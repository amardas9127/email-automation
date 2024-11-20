
# Email Automation

This project is an Email Automation System that streamlines the process of sending bulk emails. Users can upload a CSV file containing recipient email addresses, subjects, and messages directly through the website. With a single click, the system sends multiple emails efficiently.

## Screenshots

![App Screenshot](https://github.com/amardas9127/email-automation/blob/main/Screenshot%202024-11-20%20211929.png)


## How to setup ?


Change this to your email and app password in gmail in Backend/app.py

```python
    EMAIL_ADDRESS = "your email address"
    EMAIL_PASSWORD = "your password"
```


In the Backend folder run the following commands.

```bash
    python -m venv venv
    venv\Scripts\activate
    pip install flask flask-cors

```

In the Email_Automation folder run the following commands.

```bash
    npm install
```


## How to Run ?


In the Backend folder run the following commands.

```bash
    venv\Scripts\activate
    python app.py
```
```bash
    deactivate //for deactivate the environmeent
```

In the Email_Automation folder run the following commands.

```bash
    npm run dev
```

