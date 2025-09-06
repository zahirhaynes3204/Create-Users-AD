[
](https://www.loom.com/share/0a3cf05e7e294ff9a172adfad6c5cd7a?sid=4c61d047-f252-49a0-913a-542a3e2410d7)
# Create Users in Active Directory (AD)

This guide explains how to create new user accounts in **Active Directory Users and Computers (ADUC)**.

> **Goal:** Add a new user with a logon name and password, using best practices.

---

## 1) Open Active Directory Users & Computers

1. Go to the **Search bar** on Windows Server.
2. Type **Active Directory Users and Computers** and open it.
3. In ADUC, expand your **domain** (e.g., `corp.local`).

---

## 2) Navigate to the Users Container / OU

1. In the left pane, click the **Users** container (or your target OU).
2. In the right pane, right‑click an empty area, select **New → User**.

---

## 3) Fill User Information

1. Enter:
   - **First Name**
   - **Last Name** (optional)
   - **User Logon Name** (e.g., `jdoe`)
2. Click **Next**.

---

## 4) Set Password

1. Enter a **secure password**.
2. Select options as needed:
   - ☑ **Password never expires** (lab only — for production leave unchecked)
   - ☐ User must change password at next logon (optional)
3. Click **Next**, review settings, then click **Finish**.

---

## 5) Verify User

- The new user will now appear in the Users container.
- Double‑click the user to open **Properties** and adjust settings if necessary.

---

## Best Practices

- Create users inside **Organizational Units (OUs)** — not the default Users container — so you can apply Group Policies more effectively.
- Use **strong passwords** or enable **password policies** in Group Policy.
- Group users by department or role for easier administration.

---

## Credits

Created by **Zahir Haynes** as part of Active Directory practice labs.
