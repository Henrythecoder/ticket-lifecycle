<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines how tickets work in the work place and how they may be resolved .<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- ChatGPT

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Disclaimer</h2>

**Change the Sysadmins Department to a top level Department and Delete the Maintenence Department**  

**Sign into your user and make sure they have all access**

---

Step 1: Creating a Ticket

Open two windows side by side.

In the first window, navigate to http://localhost/osTicket/.

Log in as the user Norman and click on "Open a Ticket."

Fill in the ticket information:

Subject: "Mobile banking system is down"

Help Topic: Choose a random help topic, as the user may not know the best option.

Message: Write a realistic message like:
"The mobile banking system is down. I cannot access my account or perform any transactions through the app. Please look into this issue ASAP."

Submit the ticket.

---

![os1](https://github.com/user-attachments/assets/f4984429-8b75-44cc-bf4c-b1d923484953)

---

Step 2: Reviewing the Ticket in Agent's View

In the second window, sign in as your agent (the support agent, not the admin).

Go to the agent dashboard and click on the ticket created by Norman (which should appear in the ticket list).

---

![os2](https://github.com/user-attachments/assets/1ed028df-c021-4aba-bcce-f31b5ca9504a)

---

Review the ticket details:

Status: Check if the ticket is new or pending.

Department: Ensure the correct department is assigned (e.g., Mobile Banking).

SLA (Service Level Agreement): Check the SLA to see the expected response time.

Step 3: Soft Skills and Ticket Resolution

Phone Call to Harry: Call Harry to gather more information.

Ask if the issue is still happening.

Since Harry says it's still happening and is a serious problem, change the SLA to Sev A (this indicates the severity of the issue).

---

![os3](https://github.com/user-attachments/assets/2b67d69a-96e8-4fe1-a3a7-e8b5352777e1)

---

Update the ticket with a relevant message such as:

"The issue is still affecting the mobile banking system, and it is urgent. Changing SLA to Sev A for immediate attention."

---

![os5](https://github.com/user-attachments/assets/285d1ef3-91d6-4daa-b9fa-fd946ea1aa0a)

---


Reassign the Ticket:

After updating the SLA, reassign the ticket to the team you created earlier. Refresh the page to confirm that the ticket is assigned to the correct team.

---

![os4](https://github.com/user-attachments/assets/dfcfce73-98e0-4153-abd8-9c404a00ebd5)

---


Sign in as Team Member:

Sign into the team account and access the ticket that was assigned.

Assign the Ticket to Yourself:

Log in to your Admin account, find the ticket, and assign it to yourself with an appropriate message, such as:
"Assigning this ticket to myself to investigate further and resolve the issue."

---

![os7](https://github.com/user-attachments/assets/ac687bec-460f-4bfb-a452-e6953fd1ccb8)

---

Work the Ticket:

Respond to the ticket with an appropriate message, such as:
"I am currently investigating the issue with the mobile banking system. Please allow me some time to find a solution."

---

![os8](https://github.com/user-attachments/assets/eecce207-23d4-442d-962e-bd812fe0673e)

---

Resolve the Ticket:

Once the issue is resolved, go to the top of the ticket and mark it as Resolved.

---

![os9](https://github.com/user-attachments/assets/8ae22e5e-8f11-4a0c-8012-31787abe677d)
![os10](https://github.com/user-attachments/assets/43c75428-14f3-48b8-9e49-ef238b3fd4e9)

---

Step 4: Practicing with ChatGPT
Ask ChatGPT to act as a user with a problem and respond to it line by line so you can practice your response.

Example:

User: "I can't use my email. What's going on?"

Agent: "I see you are having trouble with your email. When did this issue start, and how long has it been occurring?"

User: "It started yesterday, and I still can't log in."

Agent: "Thank you for that information. Let me quickly check if you've already submitted a ticket regarding this issue."

Agent: "It seems you haven't submitted a ticket yet. I'll create one for you. Please hold on."

---

![os11](https://github.com/user-attachments/assets/e2a9510b-ccf2-4e7b-9cb5-d60a8497da6a)
![os12](https://github.com/user-attachments/assets/ad78719a-93be-48f8-8860-0ca1c4fc409e)

---



User: "Thank you."

Agent: "I’ve created the ticket for you. Let me do some research on the issue and get back to you shortly."

User: "Thanks, I'll wait."

---

![os13](https://github.com/user-attachments/assets/ae850948-e721-4568-ba0a-1b5595fb61e7)

---

Agent: "I haven't figured out the issue immediately, but I will escalate this to my manager to ensure we find a solution as quickly as possible."

User: "Okay, please let me know if you find anything."

Agent: "I’ll keep you updated. Please hold tight for a moment."

User: "I tried restarting my computer, and it works now! Thanks!"

Agent: "I’m glad to hear that! If you encounter any more issues, feel free to reach out. Have a great day!"

---

![os14](https://github.com/user-attachments/assets/72666bf0-53ee-4987-8d5b-919c3404c88b)

---

Step 5: Key Takeaways
Ticketing Systems: Learn how ticketing systems work and are operated. Familiarize yourself with creating, managing, and resolving tickets effectively.

Soft Skills: Practice soft skills like active listening, empathy, and effective communication when handling user issues.

Ticket Management: Understand how to escalate issues and assign tickets to the correct team for resolution.

By practicing these steps, you'll be better equipped to handle real-world support scenarios and efficiently manage tickets in a helpdesk environment.





