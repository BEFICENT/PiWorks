# User-Management UI

## Must-have bits
- Grid: ID | User Name | Email | Enabled
- Checkbox: “Hide Disabled Users”
- Button: **+ New User**
- Button: **Save User**
- Form fields: Username, Display Name, Phone, Email, Roles (multi-select), Enabled

## How it works
1. Page loads → grid filled, form empty, “Hide Disabled” ON.
2. Click a row → form shows that user.
3. **+ New User** → clears form.
4. **Save User** → POST (new) or PUT (edit), then refresh grid.