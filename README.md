# Salesforce LWC Parent-Child Communication Project

A Salesforce Lightning Web Component (LWC) project demonstrating **Parent to Child Communication**, **Pagination**, **Search Functionality**, **Row Actions**, and **NavigationMixin** using Apex.

---

## 🚀 Features

- 🔍 Search Accounts by Name
- 📄 Server-Side Pagination
- ⚡ Imperative Apex Calls
- 👨‍👩‍👧 Parent → Child Component Communication
- 📋 Display Related Contacts
- 👁 View Record Action
- ✏ Edit Record Action
- 🧭 NavigationMixin
- 📊 Lightning Datatable

---

## 🛠 Technologies Used

- Salesforce LWC
- Apex
- SOQL
- Lightning Datatable
- NavigationMixin
- Imperative Apex
- @api Decorator
- @AuraEnabled(cacheable=true)

---

## 📂 Project Structure

```
force-app
│
├── lwc
│   ├── imperativePagination
│   └── contactWireChild
│
└── classes
    ├── AccountController.cls
    └── ContactController.cls
```

---

## 📌 Functionality

### Parent Component

- Fetches Account records from Apex
- Supports Search
- Implements Pagination
- Provides Row Actions
- Sends selected Account Id to Child Component

### Child Component

- Receives Account Id using `@api`
- Fetches related Contacts using `@wire`
- Displays Contact records inside Lightning Datatable

---

## 🔄 Project Flow

```
Search Account
      │
      ▼
Load Accounts
      │
      ▼
Select "Show Contacts"
      │
      ▼
Pass Account Id to Child Component
      │
      ▼
Fetch Related Contacts
      │
      ▼
Display Contact List
```

---

## 📷 Features Demonstrated

- Parent to Child Communication
- @api Property
- @wire
- Imperative Apex
- Server-Side Pagination
- Search Filter
- NavigationMixin
- Lightning Datatable
- Row Actions
- Related Record Display

---

## 💡 Learning Outcomes

This project helps understand:

- Component Communication in LWC
- Calling Apex from LWC
- Working with Datatables
- Pagination Logic
- Search Implementation
- Navigation to Standard Record Pages
- Fetching Related Records
- Clean Component Design

---

## ⭐ Future Enhancements

- Previous/Next Button Disable
- Total Record Count
- Page Number Display
- Sorting
- Contact Search
- Loading Spinner
- Toast Notifications

---

## 👨‍💻 Author

**Himadri Paul**

Salesforce Developer | Apex | LWC | SOQL | JavaScript | Git | GitHub

If you found this project useful, don't forget to ⭐ the repository.
