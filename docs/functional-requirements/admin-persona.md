---
sidebar_position: 2
---

# Admin Persona

Admin Persona requirements go here

## Setup Flow

- Sys Admin Configures Admin user.
- Admin Logs in and sets up the below.
    - Sets up the *Start Date* and *End Date* for the Event.
    - Sets up the **Num** of *Kanyas* allowed to Attend per Day.
    - Sets up the **Num** of *Suvashinis* alllowed to attend per Day.
    - Sets up the Date for **Locals Only Allowed** 
    - Configures *Vendor* details.
        - Vendor for Tailoring.
        - Vendor for Kolusu.
        - Vendor for Bangles

## Approver Flow

### Registration Approval

- Admin logs in.
- Goes through the List of the Registration Entries.

| # | Pooja Date | Registration Fields List | Action |
|----|----| --- | --- |
| 1 | *date registered for*| *Registration Fields List* | Approve :white_check_mark: &nbsp; Reject :x: | 
| 2 | *date registered for*| *Registration Fields List* | Approve :white_check_mark: &nbsp; Reject :x: | 
| 3 | *date registered for*| *Registration Fields List* | Approve :white_check_mark: &nbsp; Reject :x: | 
| ... | *date registered for*| *Registration Fields List* | Approve :white_check_mark: &nbsp; Reject :x: | 
| nn | *date registered for*| *Registration Fields List* | Approve :white_check_mark: &nbsp; Reject :x: | 

- Validates each Entry and Approves / Rejects entry.
 
## Vendor Flow

### Vendor Order Approval

- Admin logs in.
- Goes through the List of Expected Materials from each Vendor.

| # | Pooja Date | Order # | Vendor | Item | Size | Quantity | Expected Delivery Date | Action |
| --- | --- | --- |--- | --- |--- | --- | --- | --- |
| 1 | *date registered for* | 001 | Tailer | Dress | 20 | 30 | *date registered for* - 2 Days | Send :arrow_forward: |
| 2 | *date registered for* | 002 | Tailer | Dress | 30 | 45 | *date registered for* - 2 Days | Send :arrow_forward: |
| 3 | *date registered for* | 003 | Bangle | Bangle | 2.4 | 35 | *date registered for* - 2 Days | Send :arrow_forward: |
| 3 | *date registered for* | 004 | Kolusu | Kolusu | 5.0 | 35 | *date registered for* - 2 Days | Send :arrow_forward: |
| -- | *date registered for* | 00n | Tailer | Dress | 20 | 30 | *date registered for* - 2 Days | Send :arrow_forward: |
| n | *date registered for* | nnn | Tailer | Dress | 20 | 30 | *date registered for* - 2 Days | Send :arrow_forward: |

- Send the Order to Vendors. Orders sent through
    - Email (*template to be finalized*)
    - Whatsapp (*message to be finalized*)

### Vendor Order Receipt
- Validates each Order with the Received Goods.
- Reconciles and Accepts Delivery

## Donation Approval

- TBD