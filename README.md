<div align="center">

# 💻 Laptop Request Catalog Item in ServiceNow
### *A SmartInternz – Naan Mudhalvan Project using ServiceNow + Automation*

</div>

---

## 📌 Project Overview
Employees in the organization require an easy and fast way to request laptops for their work.  
Currently, the request process is manual, slow, and prone to errors.

This project solves that by developing a **Service Catalog Item in ServiceNow** with **dynamic fields, form validation, reset functionality and audit traceability**.  
This ensures better governance and faster fulfillment.

---

## 🎯 Objective
- Build a **Laptop Request Form** inside ServiceNow Catalog
- Enable dynamic form behavior (fields changing based on selection)
- Validate user inputs to ensure clean data entry
- Maintain audit history for governance
- Improve request processing time and reduce manual mistakes

---

## ⚙️ Implementation Steps

### 1. Create Catalog Item
- Navigate: **Service Catalog → Maintain Items → New**
- Item Name: **Laptop Request**
- Add description, category and UI policies

### 2. Add Form Fields (Variables)
Examples:
| Variable | Type | Purpose |
|---------|------|----------|
| Laptop Type | Choice | Select Brand / Model |
| RAM | Choice | 8GB / 16GB / 32GB |
| Storage | Choice | SSD options |
| Reason for Requirement | Text Area | Justification |
| Needed By Date | Date | Delivery timeline |

### 3. Dynamic Form Logic (UI Policies)
- If Laptop Type = High-end model → show extended specifications
- If Reason not filled → disable Submit

### 4. Add Client Script
- Clear Form / Reset Button
- Validations before submit
- Input sanitization

### 5. Approval Flow
- Manager approval → IT Hardware approval → Fulfillment team

### 6. Audit / Tracking
- Updated field values tracked
- Change history and submission identifiers stored

---

## 📈 Outcome
The laptop request process becomes:

| Before | After |
|---|---|
| Manual request | Digital catalog item |
| No validation | Dynamic UI + validation |
| No tracking | Full audit tracking |
| Delayed provisioning | Faster fulfillment |

---

## 👨‍💻 Team Members
SmartInternz – Naan Mudhalvan Team

| Name |
|---|
| Enostar H J |
| Bristin K Thomas |
| Benson Bethees |
| Jershan J |

---

## 🏁 Conclusion
This project demonstrates how ServiceNow Catalog Item customization improves IT request handling.  
Dynamic fields, validations, and audit support make the laptop provisioning workflow faster and more reliable.

