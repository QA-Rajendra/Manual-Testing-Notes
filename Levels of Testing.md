# 🧪 Levels of Testing 

## 

| Level | Purpose | Who Performs | When | Type of Testing | Examples |
| --- | --- | --- | --- | --- | --- |
| 1. Unit Testing | Test individual units (smallest code parts like functions, methods, modules). Ensures each building block works correctly. | Developers | After writing a unit of code | White Box (code-level testing) | ✅ Checking login function logic✅ Testing interest calculation method |
| 2. Integration Testing | Verify that different modules work together correctly (data flow & interaction). | Developers + Testers | After Unit Testing, when modules are combined | White Box + Black Box(depends on code/UI level) | ✅ Balance Inquiry + Fund Transfer in a banking app✅ Cart → Payment flow in e-commerce |
| 3. System Testing | End-to-end validation of the complete, fully integrated system against requirements (functional & non-functional). | QA Testers | After Integration Testing, stable build ready | Black Box | ✅ UI testing (buttons, forms)✅ Functional: Login, checkout✅ Non-functional: Performance, Security, Load, Usability |
| 4. User Acceptance Testing (UAT) | Final validation by end-users/customers to ensure the software meets business needs. | End-users / Clients (with QA support) | After System Testing, before release | Black Box | ✅ Alpha Testing – Internal team (pre-release)✅ Beta Testing – Real customers (live data, real environment) |

* * *

### 🔑 Key Takeaways

## 

*   **Unit Testing** → Smallest part of code, tested by **developers**.
    
*   **Integration Testing** → Module interactions, tested by **dev + QA**.
    
*   **System Testing** → Entire system validation, tested by **QA team**.
    
*   **UAT** → Business acceptance, tested by **end-users/customers**.
    

👉 Think of it like building a car:

*   **Unit Testing** = Test engine, tires, brakes separately.
    
*   **Integration Testing** = Check if engine connects with gearbox & wheels.
    
*   **System Testing** = Drive the whole car to see if it runs fine.
    
*   **UAT** = Customer test-drive before buying. 🚗✅
