# ticket-lifecycle
<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

# osTicket — Ticket lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines / Compute)  
- Remote Desktop  
- Internet Information Services (IIS)

## Operating Systems Used
- Windows 10 (21H2)

## Ticket lifecycle stages
- Intake  
- Assignment and communication  
- Working the issue  
- Resolution

---

### Intake
User Ken creates a ticket:

![Open a Ticket](https://i.imgur.com/ewueu9b.png)

---

### Ticket assignment
Support agent John Doe logs in:

![Support agent login](https://i.imgur.com/i3sa7FH.jpg)

---

### Communication
Agent John sees this is a Sev-A (emergency) ticket and reassigns it to a System Administrator. He leaves a proper message:

![Communication](https://i.imgur.com/wVucqKf.png)

---

### Working the issue
System Administrator agent Jane Doe logs in:

![Sys admin agent login](https://i.imgur.com/i61WQKi.jpg)

Agent Jane works the issue and communicates back to agent John. She also changes the status of the ticket from **open** to **resolved**:

![Working the issue](https://i.imgur.com/DYPJufr.png)

---

### Resolution
Support agent John sees in his portal that System Administrator Jane left a message and that the ticket is now closed:

![Ticket closed](https://i.imgur.com/kRpUysm.png)

---

This walkthrough demonstrated a basic example of creating a ticket, assigning it, facilitating agent communication, and resolving it. In real-world use, tickets may also be reassigned, escalated based on urgency, or redirected to other departments depending on the impact.

Depending on the organization’s size, help desk agents might manage anywhere from **10 to 100 tickets daily**.

Hopefully, this guide gave you a clearer understanding of how a typical ticket lifecycle works.
