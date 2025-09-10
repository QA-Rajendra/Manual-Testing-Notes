# Manual-Testing-Notes
## 🖥️ Software Overview

*   **Software** = collection of programs to perform tasks/functions
    

### Types of Software

| Type | Description | Examples |
| --- | --- | --- |
| System Software | Controls hardware & system operations | Windows, Linux, Drivers |
| Programming Software | Helps developers code, test, debug | Compilers, Interpreters, Debuggers |
| Application Software | End-user daily tasks | MS Word, Chrome, WhatsApp |

* * *

## 🧪 Software Testing

*   **Definition**: Process to check correctness, detect bugs, and ensure customer requirements are met.
    
*   **Goals**:
    
    *   Detect defects before release
        
    *   Deliver quality product
        

### Why Do We Need Testing?

| Reason | Explanation |
| --- | --- |
| Ensure bug-free software | Builds trust & good experience |
| Meet customer requirements | Works as expected |
| Meet user expectations | Smooth features |
| Avoid costly fixes | Early bug detection is cheaper |

**Example**: A phone where the camera doesn’t open → defect.

* * *

## 📐 Core Characteristics of Quality Software

✅ Bug-free  
✅ On-time delivery  
✅ Within budget  
✅ Meets requirements  
✅ Maintainable

* * *

## 🧱 The Three P’s of Software Companies

| P | Meaning | Why It Matters in Testing |
| --- | --- | --- |
| People | Developers, Testers, Designers, Analysts, Managers, Clients | Skilled testers find bugs early |
| Process | Planned, Developed, Tested, Delivered | Ensures consistency & fewer defects |
| Product | Final software (web, mobile, desktop app) | Must be high quality & user-friendly |

**Relation** → People → follow Process → to build Product

# 📊 Project vs Product

## 

| Aspect | Project | Product |
| --- | --- | --- |
| Definition | Software made for a specific customer | Software made for many customers |
| Requirements | Based on one client’s needs | Based on general market needs |
| Reusability | Not reusable without changes | Ready-to-use for anyone |
| Example | ICICI Bank’s custom banking app | WhatsApp, MS Word, Chrome |
| Analogy | Tailor-made dress | Ready-made dress |

* * *

# 🏢 Company Types

## 

| Type | What They Do | Examples |
| --- | --- | --- |
| Product-Based | Build products for mass usage | Google, Microsoft, Adobe, Oracle |
| Service-Based | Work on client-specific projects | TCS, Infosys, Wipro, Accenture |

* * *

# 🐞 Error, Bug/Defect & Failure

## 

| Term | Definition | Stage | Cause | Example |
| --- | --- | --- | --- | --- |
| Error | Human mistake in coding/design/requirements | Development | Misunderstanding, lack of knowledge, carelessness | a = b - c instead of a = b + c |
| Bug / Defect | Actual result ≠ Expected result | Testing | Due to earlier error in code | Expected: Total=100 → Shown: Total=50 |
| Failure | Defect not caught → causes issue in real use | Production (user environment) | Uncaught bug reaches customer | App crashes when clicking “Pay Now” |

**Relation:**  
👉 **Error** → causes → **Bug/Defect** → if not fixed → causes → **Failure**

# 🧪 Types of Software Testing

## 1\. Based on Functionality

## 

| Type | Meaning | Example |
| --- | --- | --- |
| Functional Testing | Checks if software works as per requirements | Login button should log in |
| Non-Functional Testing | Checks performance, usability, security, etc. | Page should load within 3 sec |

* * *

## 2\. Based on Execution

## 

| Type | Meaning | Example |
| --- | --- | --- |
| Manual Testing | Tester executes test cases without tools | Tester clicks buttons manually |
| Automation Testing | Test cases executed using scripts/tools | Selenium, JUnit, TestNG |

* * *

## 3\. Common Testing Types

## 

| Type | Purpose | Example |
| --- | --- | --- |
| Unit Testing | Tests smallest piece (function/module) | Add(2,3) → 5 |
| Integration Testing | Tests combined modules | Login + Dashboard |
| System Testing | Tests full application as a whole | Full website workflow |
| Acceptance Testing | Done by client/end-user | UAT before release |
| Regression Testing | Ensure old features work after changes | Re-check login after update |
| Smoke Testing | Basic check: "Is build stable?" | App opens without crash |
| Sanity Testing | Quick check of new functionality | Check only new “Search Filter” |

# 🔄 Software Development Life Cycle (SDLC)

# 

➡️ **Definition**: A step-by-step process followed to design, develop, test, and deliver high-quality software.

* * *

## 🛠️ Phases of SDLC

# 

1️⃣ **Requirement Gathering & Analysis**

*   Understand **what the customer wants** ✍️
    
*   Do **feasibility study** (time ⏳, cost 💰, technology ⚙️).
    
*   Create docs: **SRS, FRS, BRS**.  
    📌 _Example_: Bank client wants **Login + Balance view + Fund transfer**.
    

* * *

2️⃣ **Design**

*   Create the **blueprint of the system** 🏗️.
    
*   Two levels:
    
    *   **HLD** (High-Level Design) → Architecture, modules 🏛️
        
    *   **LLD** (Low-Level Design) → Detailed logic, flowcharts 🔄  
        📌 _Example_: User flow → Login → Dashboard → Transfer Funds.
        

* * *

3️⃣ **Development (Coding)**

*   Developers start writing the actual **code 💻**.
    
*   Build modules + write **unit tests** + integrate components.  
    📌 _Example_: Code for login validation, DB queries, fund transfer APIs.
    

* * *

4️⃣ **Testing**

*   Testers validate the software 🔍.
    
*   Goal = find **bugs 🐞** before customer uses it.
    
*   Includes:
    
    *   **Functional Testing** (Does it work?) ✔️
        
    *   **Non-Functional Testing** (Is it fast, secure?) ⚡🔐  
        📌 _Example_: Invalid login should show error, transfer only if balance > 0.
        

* * *

5️⃣ **Deployment**

*   Software goes **live 🚀** for the customer.
    
*   Could be:
    
    *   Production server 🌐
        
    *   App Store 📱
        
    *   Client system 🖥️  
        📌 _Example_: Bank staff start using the app.
        

* * *

6️⃣ **Maintenance**

*   Even after release → issues appear ⚠️.
    
*   Handle **bug fixes 🔧, updates 🔄, new features ➕**.  
    📌 _Example_: Fix transfer issue at midnight.
    

* * *

# 🏗️ SDLC Models

# 

Different **ways/philosophies** to follow SDLC:

1.  **💧 Waterfall Model**
    

*   Linear, step-by-step → Finish one phase before moving ahead.
    
*   Best for **small, clear projects**.
    

2.  **✔️ V-Model (Verification & Validation)**
    

*   Each development phase has a **matching test phase**.
    
*   Encourages **early testing** 🕵️.
    

3.  **🔁 Iterative Model**
    

*   Build software in **small parts (iterations)**.
    
*   Each iteration = **build ➝ test ➝ improve**.
    

4.  **🌀 Spiral Model**
    

*   Mix of **iteration + risk analysis** ⚠️.
    
*   Used for **complex, high-risk projects**.
    

5.  **⚡ Agile Model**
    

*   Flexible, short cycles called **sprints 🏃**.
    
*   Continuous feedback 👥 + fast delivery 🚀.
    
*   Best for **changing requirements**.
    

* * *

✅ **Quick Visual Formula**:  
**Idea 💡 → Requirement ✍️ → Design 🏗️ → Code 💻 → Test 🔍 → Deploy 🚀 → Maintain 🔧**
