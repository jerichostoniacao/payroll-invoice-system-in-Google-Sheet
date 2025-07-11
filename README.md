# Sheet Structure for Payroll Invoice System

## 1. PayrollData Sheet
Used to feed invoice data.

| Column | Header     | Description                      |
|--------|------------|----------------------------------|
| A      | Name       | Full name of the employee        |
| B      | Email      | Email address of the employee    |
| C      | Address    | Home or business address         |
| D      | Cutoff     | Payroll cutoff (e.g., July 1–10) |
| E      | Regular    | Regular pay                      |
| F      | OT         | Overtime pay                     |
| G      | Bonus      | Bonus or incentive               |
| H      | Total      | Total salary for the period      |

---

## 2. Invoice Template Sheet
Used as a printable template with placeholders like:

- `{{Name}}`
- `{{Address}}`
- `{{Date}}`
- `{{Cutoff}}`
- `{{Pay}}`
- `{{OT}}`
- `{{Bonus}}`
- `{{Total}}`
- `{{InvoiceNumber}}`

---

## 3. Invoice Log Sheet
Used for tracking all invoices sent.

| Column | Header       | Description                            |
|--------|--------------|----------------------------------------|
| A      | Timestamp     | When the invoice was generated         |
| B      | Name          | Employee name                          |
| C      | Email         | Email address                          |
| D      | Invoice #     | Unique invoice number                  |
| E      | Cutoff        | Pay period                             |
| F      | Total         | Amount paid                            |
| G      | Status        | "Draft Sent" or "Invoice Sent"         |
| H      | Thread ID     | (Optional) Gmail thread for replies    |

---

## 4. (Optional) Form Responses Sheet
If you're using a Google Form for confirmation.

Usually auto-generated and includes:
- Timestamp
- Name
- Email
- Cutoff
- Confirmation Status
