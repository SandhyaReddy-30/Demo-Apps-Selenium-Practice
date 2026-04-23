# ⚡ Demo Apps — Selenium Practice

A playground for automation testers to practice all kinds of UI interactions using Selenium, Cypress, Playwright, or any other automation tool.

🔗 **Live Site:** [https://sandhyareddy-30.github.io/Demo-Apps-Selenium-Practice/](https://sandhyareddy-30.github.io/Demo-Apps-Selenium-Practice/)

---

## 📌 About the Project

This is a single-page HTML application built as a **Selenium practice website**. It contains commonly tested UI elements that automation testers encounter in real-world projects.

---

## ✅ Features

| Section | What You Can Practice |
|---|---|
| ✏️ Text Box | Input fields, textarea, read-only, disabled, slider |
| 🔘 Buttons | Click, double click, right click, toggle, counter |
| ☑️ Check Box | Single, multiple, select all |
| 🔵 Radio Button | Single selection, group selection |
| 🔽 Dropdown | Single select, multi select |
| 📊 Table | Add, Edit, Delete rows (data persists via localStorage) |
| 🔗 Links | Navigation links, external links, tooltips |
| ⚠️ Alerts | Browser alert, confirm, prompt, custom notifications |
| 🪟 Modal Dialog | Basic modal, confirm modal |
| 📑 Tabs | Tab switching, content panels |
| 🪗 Accordion | Expand and collapse FAQ sections |
| 🖱️ Drag & Drop | Sortable list drag and reorder |
| 🖼️ iFrame | Nested frame interactions |
| 🔐 Login Form | Authentication (admin / admin123) |
| 📝 Registration | Full form filling practice |
| ✅ Form Validation | Validate name, email, phone, password |
| ⏱️ Dynamic Elements | Explicit wait, progress bar, dynamic table |
| 📜 Scroll & Waits | Scroll to element, infinite scroll |

---

## 🛠️ Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling (dark theme with CSS variables)
- **Vanilla JavaScript** — All interactions and logic
- **localStorage** — Data persistence for the Table section
- **GitHub Pages** — Hosting

---

## 🗂️ Project Structure

```
Demo-Apps-Selenium-Practice/
│
├── index.html        # Main application file (all-in-one)
└── README.md         # Project documentation
```

---

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/SandhyaReddy-30/Demo-Apps-Selenium-Practice.git
```

2. Open `index.html` in your browser — no server needed!

---

## 📊 Table Feature (Add / Edit / Delete)

The Table section supports full CRUD operations:

- ➕ **Add Row** — Fill in Name, Course, Batch, Status, Score and click `+ Add Row`
- ✏️ **Edit Row** — Click the Edit button on any row to update details
- 🗑️ **Delete Row** — Click the Delete button to remove a row (with confirmation)
- 🔄 **Reset** — Click `Reset to Default` to restore the original 5 rows
- 💾 **Data persists** after page refresh using browser localStorage

### Table Element IDs for Selenium:
| Element | ID |
|---|---|
| Name input | `add-name` |
| Course dropdown | `add-course` |
| Batch input | `add-batch` |
| Status dropdown | `add-status` |
| Score input | `add-score` |
| Add Row button | `btn-add-row` |
| Reset button | `btn-reset-table` |
| Edit button (per row) | `btn-edit-{id}` |
| Delete button (per row) | `btn-delete-{id}` |
| Save Edit button | `btn-save-edit` |
| Confirm Delete button | `btn-confirm-delete` |

---

## 🔐 Login Credentials

| Username | Password |
|---|---|
| admin | admin123 |

---

## 🧪 Suggested Selenium Test Cases

- [ ] Add a new student row and verify it appears in the table
- [ ] Edit an existing row and verify the changes are saved
- [ ] Delete a row and verify it is removed from the table
- [ ] Refresh the page and verify data persists
- [ ] Login with valid credentials and verify success message
- [ ] Login with invalid credentials and verify error message
- [ ] Fill and submit the registration form
- [ ] Verify form validation error messages
- [ ] Switch between tabs and verify correct content
- [ ] Test drag and drop reordering
- [ ] Handle browser alert, confirm, and prompt dialogs
- [ ] Switch into iFrame and interact with elements inside
- [ ] Test infinite scroll loads more items

---

## 👩‍💻 Author

**Sandhya Reddy**
- GitHub: [@SandhyaReddy-30](https://github.com/SandhyaReddy-30)

---

## 📄 License

This project is open source and available for anyone to use for learning and practice purposes.
