# PO-auto-approval-stage
develop a custom module in Odoo 18 that extends the Purchase Order (PO) workflow so that each PO automatically enters an approval stage based on its total value :
- Less than IDR 5 million: directly to the Manager

- Between IDR 5 million and 20 million: to the Department Head, then to the CFO

- More than IDR 20 million: directly to the CFO

The PO form must include buttons for "Submit for Approval", "Approve", and "Reject". Each approval step should send an email notification and log the action in the chatter (inbox), including the reason if rejected. The system must also ensure that only the authorized role at each stage can view and act on the PO.

