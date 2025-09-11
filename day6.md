## 📌 SYSTEM TESTING OVERVIEW

## 

**Definition:**  
System Testing verifies the **entire integrated application** to ensure it meets client requirements.

**Type:** Black Box Testing (tests from user perspective; no need to know code)

**Goal:** Ensure software works as expected in **real-world scenarios**.

**Importance:**

*   Validates overall system functionality
    
*   Detects defects from module integration
    
*   Ensures functional & non-functional requirements are met
    
*   Acts as a final check before **User Acceptance Testing (UAT)**
    

**Sequence:**  
**Integration Testing → System Testing → UAT**

* * *

## 🧩 TYPES OF SYSTEM TESTING

## 

| Type | Purpose / Checks | Example |
| --- | --- | --- |
| GUI Testing | Checks software appearance and UI elements | Buttons, menus, layouts, colors, icons |
| Usability Testing | Checks ease of use & navigation | Checkout process, menu clarity |
| Functional Testing | Checks feature functionality | Login, search, checkout |
| Non-Functional Testing | Checks performance, security, reliability | Load testing, security tests, recovery |

* * *

## 1️⃣ GUI TESTING

## 

**Definition:** Focuses on **interface look and functionality**.

**Type:** Black Box  
**Applicable For:** Web & Desktop apps

**Importance:**

*   Confirms UI matches design specs
    
*   Detects font, color, layout, and alignment issues
    
*   Improves user experience
    

**Checklist / Key Areas:**

*   UI elements: buttons, links, dropdowns
    
*   Visual design: colors, fonts, images
    
*   Layout & alignment
    
*   Error messages & colors
    
*   Responsiveness across screens
    
*   Scrollbars, disabled fields
    
*   Hyperlink behavior
    

**Example:** Login screen

*   Login button works & redirects
    
*   Username/password fields aligned
    
*   Error messages appear in red
    

**Takeaway:** **GUI = Look & Feel**

* * *

## 2️⃣ USABILITY TESTING

## 

**Definition:** Ensures the app is **easy and intuitive** to use.

**Checks:**

*   **Ease of Use:** menus, buttons, tasks
    
*   **Understandability:** simple language, instructions
    
*   **User Experience:** intuitive workflow, error prevention
    
*   **Help Documents:** readable, accurate
    
*   **Context-sensitive Help:** tooltips, shortcuts
    

**Example:** Online shopping checkout

*   Add items to cart easily
    
*   Clear discount application
    
*   Understandable error messages
    

**Takeaway:** **Usability = Ease of Use / User Experience**

* * *

## 3️⃣ FUNCTIONAL TESTING

## 

**Definition:** Ensures **features work as per requirements**.

**Types:**

1.  **Object Properties Testing** – UI elements behave correctly (enable/disable, visible/hidden, focus, dropdowns, links, colors)
    
2.  **Database Testing** – Ensures correct data manipulation (Insert, Update, Delete, Select) and back-end verification
    
3.  **Error Handling Testing** – Proper error/warning/info messages, system stability
    
4.  **Calculations / Manipulations Testing** – Numeric/data operations accurate (cart totals, taxes, payroll)
    
5.  **Links Testing** – Internal, external, and broken links work correctly
    
6.  **Cookies & Sessions Testing** – Login persistence, proper session timeout handling
    

**Example:** Registration form

*   Object properties: input boxes enabled & focused
    
*   Database: user record created/updated/deleted
    
*   Error Handling: invalid input shows clear message
    
*   Calculations: price × quantity, discounts correct
    
*   Links: navigate to correct page
    
*   Cookies & Sessions: login persists until timeout
    

**Takeaway:** **Functional Testing = Feature Behavior & Accuracy**

* * *

### 🔹 Summary Table for Functional Testing

## 

| Type | Focus |
| --- | --- |
| Object Properties | UI element behavior |
| Database | Data stored & retrieved correctly |
| Error Handling | Meaningful error/warning/info messages |
| Calculations | Numeric and logical operations accurate |
| Links | Navigation paths correct |
| Cookies & Sessions | Login persistence & session handling |

* * *

### ✅ Key Takeaways

## 

*   **System Testing** validates the complete application before UAT
    
*   **GUI Testing → Look & Feel**
    
*   **Usability Testing → Ease of Use / User Experience**
    
*   **Functional Testing → Feature behavior, data, errors, calculations, links, sessions**
    
*   All testing types work together to ensure **quality, reliability, and user satisfaction**
*   
