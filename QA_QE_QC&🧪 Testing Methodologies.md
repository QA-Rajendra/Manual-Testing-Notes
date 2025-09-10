## | Aspect | Quality Assurance (QA) 🛠️ | Quality Control (QC) 🔍 | Quality Engineering (QE) ⚡ |
| --- | --- | --- | --- |
| Focus | Process-oriented → Prevents defects | Product-oriented → Detects defects | Build quality in from the start |
| Goal | Ensure correct process is followed | Ensure product meets requirements | Continuous quality via automation & CI/CD |
| SDLC Coverage | Entire SDLC | Mainly Testing phase | Entire SDLC (shift-left approach) |
| Activity Type | Management activity (standards, audits, reviews) | Technical activity (executing tests, finding bugs) | Engineering activity (automation, DevOps, CI/CD pipelines) |
| Who Performs | Managers, QA leads, auditors | Testers (manual & automation) | QEs / SDETs (engineers writing code to test code) |
| Example | Defining coding standards, process audits | Writing & executing test cases, reporting bugs | Building test frameworks, automated regression suites, API testing in CI/CD |

# 🧪 Testing Methodologies

### 1️⃣ White Box Testing (Transparent Box)

## 

*   **Focus:** Internal code, logic, paths, coverage
    
*   **Requires programming knowledge**
    
*   **Done by developers**
    
*   Examples: Unit Testing, Code Review, Static Analysis
    

### 2️⃣ Black Box Testing (Opaque Box)

## 

*   **Focus:** External functionality, user perspective
    
*   **No coding knowledge needed**
    
*   **Done by testers/end-users**
    
*   Examples: Login testing, System Testing, UAT
    

### 3️⃣ Grey Box Testing (Semi-Transparent Box)

## 

*   **Focus:** Mix of UI + backend (databases, APIs, logs)
    
*   **Some technical knowledge required**
    
*   **Done by technical testers / devs**
    
*   Examples: DB testing after registration, API testing
    

* * *

# 📊 Quick Comparison

## 

| Feature | White Box ⚪ | Black Box ⚫ | Grey Box ⚫⚪ |
| --- | --- | --- | --- |
| Knowledge of Internals | Full | None | Partial |
| Focus | Code, logic, coverage | Functionality, user needs | UI + Backend flow |
| Skills Needed | Programming | None | Some technical (SQL, API) |
| Done By | Developers | Testers, End-users | Testers with tech skills |
| Examples | Unit Testing, Code Review | System Testing, UAT | DB & API Testin |
