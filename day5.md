##   

## 🧩 Levels of Software Testing

## 

1.  **Unit Testing 🛠️** – First Check (Building Blocks)
    
    *   **What is it?**  
        Testing the smallest testable part of an application (function, method, or module).
        
    *   **Who performs it?**  
        Developers 👨‍💻 (QA testers usually do **not** perform unit testing)
        
    *   **When?**  
        Right after a piece of code is developed, before the full software is ready.
        
    *   **Technique:** White Box Testing 🔍
        
    *   **Example (Banking app):**
        
        *   Login logic
            
        *   Interest calculation function
            
        *   Display balance module
            
    *   **Techniques:**
        
        1.  **Basis Path Testing** – Test all independent code paths
            
            `def number_type(x):     if x > 0: return "Positive"     elif x == 0: return "Zero"     else: return "Negative"`
            
            Test cases: 5 → Positive, 0 → Zero, -3 → Negative
            
        2.  **Control Structure Testing** – Check decision points & loops
            
            *   Condition coverage: Execute both true/false branches
                
            *   Branch coverage: Ensure all branches run
                
            *   Loop coverage: Test zero, one, multiple iterations
                
        3.  **Mutation Testing** – Introduce small changes to check if tests catch errors
            
            `int add(int a, int b) { return a + b; } // mutation: return a - b;`
            
    *   **Unit vs Component Testing:**
        
        *   Unit: Single piece of code
            
        *   Component: Single feature/UI element, may use UI, blurs into Black Box
            

* * *

2.  **Integration Testing 🔗** – Testing Module Connections
    
    *   **What is it?**  
        Testing interfaces and interactions between combined modules.
        
    *   **Who performs it?**  
        Developers (White Box) or Testers (Black Box)
        
    *   **Why needed?**  
        Defects can appear in module interactions even if units work individually.
        
    *   **Example:** Banking app – Sending money updates balance correctly
        
    *   **Approaches:**
        
        1.  **Incremental Integration Testing (preferred)** – Add modules one by one
            
            *   Top-Down ⬆️: Start from main module, use stubs for missing child modules
                
            *   Bottom-Up ⬇️: Start from lowest module, use drivers for missing parent modules
                
            *   Hybrid/Sandwich 🥪: Mix top-down & bottom-up, meet in middle
                
        2.  **Non-Incremental (Big Bang) 💥** – Integrate all modules at once
            
            *   Hard to isolate defects
                
            *   High chance of missing communication issues
                
    *   **Temporary Tools:**
        
        *   **Stub:** Simulates missing child module
            
        *   **Driver:** Simulates missing parent module
            

* * *

3.  **System Testing 🌐** – End-to-End Validation
    
    *   **What is it?**  
        Test the complete, integrated system from end to end.
        
    *   **Who performs it?** QA Testing team 🧪
        
    *   **Technique:** Black Box (via UI) 🚫💻
        
    *   **Focus Areas:**
        
        1.  **UI/GUI Testing 🎨** – Buttons, input boxes, layout, fonts, logos
            
        2.  **Functional Testing ✅** – Features work per requirements (Smoke, Sanity, Regression)
            
        3.  **Non-Functional Testing ⚡🔒** – Performance, Security, Recovery, Load, Stress, Compatibility
            
        4.  **Usability Testing 🖱️** – User-friendliness, navigation, error messages
            
    *   **Example:**
        
        *   Banking app: Login, money transfer, balance check
            
        *   E-commerce app: Product search, cart, payment, order history
            

* * *

4.  **User Acceptance Testing (UAT) 👥** – Customer Approval
    
    *   **What is it?**  
        Final validation to ensure software meets business requirements from user perspective.
        
    *   **Who performs it?** End-users, customers, or dedicated UAT team
        
    *   **Technique:** Black Box, real-world usage scenarios
        
    *   **Levels of UAT:**
        
        1.  **Alpha Testing 🅰️** – Internal team, simulated real data
            
        2.  **Beta Testing 🅱️** – Real users, live environment, real data
            
    *   **Purpose:** Confirm software is practically useful and fully accepted by end-users
        

* * *

### Quick Recap Table

## 

| Level | Focus | Who Performs | Technique | Example |
| --- | --- | --- | --- | --- |
| Unit Testing 🛠️ | Single code unit | Developers | White Box 🔍 | Login function logic |
| Integration Testing 🔗 | Module interaction | Developers/Testers | White & Black Box ⚪⚫ | Balance updates after sending money |
| System Testing 🌐 | Full system | QA Testers 🧪 | Black Box 🚫💻 | E-commerce cart, payment, order flow |
| UAT 👥 | Customer approval | End Users / Clients | Black Box 🚫💻 | Real-world usage validation |
