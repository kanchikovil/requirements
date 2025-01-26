---
sidebar_position: 6
---

# Workflows

All Persona Workflows go here...

## Registration Workflow
- User Enters Aadhar number.
    - Aadhar Number validated against UIDAI.
    - *API details to be explored.*
- Upon successful valiation fills in the Respective Forms and submits.
- Receives SMS & Whatsapp Notification upon Submission.
    - *API details to be Explored.*
- Upon successful approval of the registration receives SMS & Whatspp Notification confirming the registration.
    - Unique Identification code is sent.
- Uses the unique code received to print the confirmation message.
    - Confirmation message with QR Code.
- Upon rejection receives SMS & Whatspp Notification.

## Admin Workflow

### Batch Flow

:::info[Executes End of Everyday at **Predefined Time**]

- Job to Send Approval / Reject notifications to Users.
- Send Orders to Vendors.

:::
