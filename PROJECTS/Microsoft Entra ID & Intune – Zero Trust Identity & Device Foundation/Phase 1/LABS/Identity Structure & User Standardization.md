# LAB 1 – Identity Structure & User Standardization

## Goal

The goal of this lab is to design and implement a **clean and consistent identity structure** in Microsoft Entra ID by standardizing users, departments, and security groups.

This lab ensures that identities are **predictable, scalable, and easy to manage**.

---

## Why This Matters

Without a clear identity structure:
- Users are created inconsistently
- Access becomes difficult to manage
- Automation is almost impossible
- Security groups lose their meaning

A standardized identity structure is the **foundation for licensing, access control, and Conditional Access**.

---

## What Was Implemented

During this lab, the following elements were configured:

### Department Modeling
Departments were modeled conceptually using the **Department** attribute in the user profile:

- Operations  
- Support  
- Marketing  
- Finance  
- Management  

This allows identities to be logically grouped without relying on traditional OUs.

---

### User Scenarios

To validate the structure, realistic user scenarios were created:

- A new internal employee in **Support**
- An external user working with **Marketing**
- A manager in **Operations**

These scenarios simulate real enterprise identity use cases.

---

### Security Groups

Department-based security groups were created:

- `SG_Department_Support`
- `SG_Department_Marketing`
- `SG_Department_Operations`

Users were assigned to the correct groups based on their role and department.

---

<img width="1641" height="687" alt="image" src="https://github.com/user-attachments/assets/4629359d-cab7-41f8-9e32-1be63b595b38" />

<img width="1625" height="392" alt="image" src="https://github.com/user-attachments/assets/a7541a26-c3d3-4de5-879c-71537788fea1" />


---

## Key Concepts Applied

- Identity standardization
- Department-based access modeling
- Security groups as the basis for access control
- Preparation for automation and group-based licensing

---

## Result

At the end of this lab:

- Users follow a clear and consistent structure
- Departments are correctly represented
- Security groups reflect business roles
- The Entra ID tenant has a **clean identity baseline**

This lab delivers a **solid identity structure** that supports scalable access management and future security controls.
