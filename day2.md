## 1️⃣ Software Development Life Cycle (SDLC)

## 1️⃣ SDLC Overview

## 

**Definition:**  
SDLC is the process to **design, develop, and test high-quality software**.

**6 Key Phases of SDLC:**

1.  📝 **Requirement Gathering & Analysis**
    
    *   Understand customer needs and current system
        
    *   Conduct feasibility study: technical, financial, time
        
    *   Document requirements in **SRS, FRS, BRS**
        
    *   _Example:_ Bank app: login, balance, fund transfer
        
2.  🏗️ **Design**
    
    *   Create blueprint of the system
        
    *   High-Level Design (HLD) = architecture & modules
        
    *   Low-Level Design (LLD) = detailed module design
        
    *   _Example:_ Plan user flow: login → dashboard → transfer
        
3.  💻 **Development (Coding)**
    
    *   Developers write code based on design
        
    *   Create unit tests & integration points
        
    *   _Example:_ Code login validation, fetch balance, fund transfer API
        
4.  🧪 **Testing**
    
    *   QA validates software functionality
        
    *   Types: functional, non-functional (performance, security)
        
    *   Report bugs/defects
        
    *   _Example:_ Test invalid login, balance checks
        
5.  🚀 **Deployment**
    
    *   Release software to customer environment
        
    *   Upload to server, app store, or internal system
        
    *   _Example:_ App installed at bank for staff use
        
6.  🔧 **Maintenance**
    
    *   Fix bugs, add features, ensure compatibility
        
    *   _Example:_ Fix “midnight fund transfer” bug
        

* * *

## 2️⃣ Popular SDLC Models

## 

*   💧 **Waterfall** – Linear & sequential; best for small, fixed projects
    
*   ✅ **V-Model** – Testing at every phase; for high-quality verification
    
*   🔄 **Iterative** – Build in small iterations; incremental delivery
    
*   🌀 **Spiral** – Iterative + risk analysis; for large, complex projects
    
*   ⚡ **Agile** – Short sprints & continuous feedback; flexible requirements
    

* * *

## 3️⃣ Waterfall Model

## 

**Characteristics:**

*   🧗‍♂️ Step-by-step flow
    
*   📚 Documentation-heavy
    
*   ✔️ Best for clear & fixed requirements
    

**Pros ✅ / Cons ❌**

*   ✅ High product quality & structure
    
*   ✅ Less chance of bugs
    
*   ✅ Low initial investment
    
*   ✅ Easy to manage
    
*   ❌ Cannot change requirements mid-way
    
*   ❌ Defects propagate if early mistake occurs
    
*   ❌ High rework cost if bugs found late
    
*   ❌ Testing happens late
    

* * *

## 4️⃣ Spiral Model 🌀

## 

**Definition:** Iterative + controlled + risk-focused model  
**Best for:** Large, evolving, high-risk projects

**Each Spiral Cycle Steps:**

1.  📋 **Planning** – Define objectives, deliverables, assign roles
    
    *   _Example:_ Plan login module & responsibilities
        
2.  ⚠️ **Risk Analysis** – Identify risks & mitigation
    
    *   _Example:_ SMS OTP may fail → fallback to email
        
3.  💻 **Development & Testing** – Code & validate module
    
    *   _Example:_ Test login, password security
        
4.  👁️ **Evaluation** – Customer feedback for next cycle
    
    *   _Example:_ Add “Forgot Password” next cycle
        

**Pros ✅ / Cons ❌**

*   ✅ Testing in every cycle
    
*   ✅ Customer gets working module
    
*   ✅ Early risk analysis
    
*   ✅ Suitable for long-term projects
    
*   ❌ Requirement changes not allowed mid-cycle
    
*   ❌ No early testing during Requirement/Design
    
*   ❌ Costly & time-consuming
    
*   ❌ No fixed number of cycles, closure uncertain
    

**Common Problem (Waterfall & Spiral):**

*   🐛 Testing happens after coding, not during Requirements/Design → late defect discovery
    

## 1️⃣ SDLC Phases

## 

| Phase | Key Points |
| --- | --- |
| Requirement Gathering | Understand needs, feasibility, document |
| Design | Blueprint, HLD & LLD, diagrams |
| Development | Code & unit tests |
| Testing | Validate, functional & non-functional |
| Deployment | Release to users/server/app store |
| Maintenance | Bug fixes & enhancements |

* * *

## 2️⃣ Popular SDLC Models

## 

| Model | Feature |
| --- | --- |
| Waterfall | Linear & sequential |
| V-Model | Testing at each phase |
| Iterative | Build in small iterations |
| Spiral | Iterative + risk analysis |
| Agile | Short sprints, continuous feedback |

* * *

## 3️⃣ Waterfall Model

## 

| Pros | Cons |
| --- | --- |
| Structured & high quality | Cannot change requirements mid-way |
| Less bugs | High rework cost if bugs found late |
| Low initial investment | Testing happens late |

* * *

## 4️⃣ Spiral Model

## 

| Step | Key Points |
| --- | --- |
| Planning | Define objectives & deliverables |
| Risk Analysis | Identify & mitigate risks |
| Development & Testing | Code & validate |
| Evaluation | Customer feedback & improvements |

**Pros / Cons**

| Advantages | Disadvantages |
| --- | --- |
| Early testing & risk analysis | No mid-cycle changes |
| Customer gets working module | Costly & time-consuming |
| Suitable for long-term projects | No fixed number of cycles |

**Definition:**  
SDLC is the process used to **design, develop, and test high-quality software**.

**Key Phases of SDLC (6 Phases):**

| Phase | Description | Example |
| --- | --- | --- |
| Requirement Gathering & Analysis | Understand what the customer wants. Conduct feasibility (technical, financial, time). Document requirements in SRS, FRS, BRS. | A bank wants an app for login, balance, fund transfer. |
| Design | Blueprint of software. HLD = architecture/modules, LLD = detailed module design. Use diagrams. | User flow: login → dashboard → transfer funds |
| Development (Coding) | Developers write code based on design. May include unit tests and integration points. | Code for login validation, fetch balance from DB, fund transfer API |
| Testing | QA tests software for bugs. Types: functional, non-functional. Report defects. | Test invalid login, check transfer only with sufficient balance |
| Deployment | Software goes live for users. | App uploaded to Play Store or installed in bank |
| Maintenance | Fix bugs, add features, ensure compatibility. | Fix fund transfer issue at midnight |

* * *

## 2️⃣ SDLC Models Overview

**Purpose:** Defines how SDLC phases flow from requirements to maintenance.

**Popular Models:**

1.  **Waterfall Model** – Linear & sequential, best for **small, fixed projects**.
    
2.  **V-Model** – Waterfall with **testing at every phase**.
    
3.  **Iterative Model** – Software built in **iterations**, each adds features.
    
4.  **Spiral Model** – Iterative + **risk analysis**, for **complex/high-risk projects**.
    
5.  **Agile Model** – **Short sprints**, continuous feedback, flexible requirements.
    

* * *

## 3️⃣ Waterfall Model (Linear Model)

**Characteristics:**

*   Step-by-step flow; **no going back**.
    
*   Documentation-heavy.
    
*   Works well when requirements are **clear & fixed**.
    

**Phases & Roles:**

| Phase | Who’s involved | Example |
| --- | --- | --- |
| Requirement Gathering | BA, Client, Product Manager | Understand login, balance, transfer features |
| Design | Architects, Designers | Plan user flow, system architecture |
| Development | Developers | Code login, transfer features |
| Testing | QA Testers | Test login, transfer functionality |
| Deployment | DevOps, Release Team | Upload app or deliver to client |
| Maintenance | Developers, Support Team | Fix “midnight transfer” bug |

**Pros vs Cons:**

| Advantages | Disadvantages |
| --- | --- |
| High product quality | Cannot change requirements mid-way |
| Less chances of bugs | Defect propagation if early mistakes happen |
| Low initial investment | High rework cost if bugs found late |
| Structured & manageable | Testing happens late |

✅ **Best for:** Small projects with fixed requirements  
❌ **Not suitable for:** Projects with frequent changes

* * *

## 4️⃣ Spiral Model (Iterative + Risk-Focused)

**Purpose:** Combines **Waterfall structure** with **iterations & risk analysis**.  
Used for **large, complex projects** where requirements evolve.

**Each Spiral Cycle has 4 steps:**

| Step | What happens | Example |
| --- | --- | --- |
| Planning | Define objectives, deliverables, assign roles | Login feature: define functionality, tech stack, responsibilities |
| Risk Analysis | Identify risks, plan mitigation | OTP SMS gateway may fail → fallback to email |
| Development & Testing | Code module, test functionality | Developers code login, testers validate login & security |
| Evaluation | Customer reviews, feedback collected | Add “Forgot Password” next cycle, change button color |

**Pros vs Cons:**

| Advantages | Disadvantages |
| --- | --- |
| Testing each cycle | Requirement changes not allowed mid-cycle |
| Customer gets working software each cycle | No early testing during Requirement & Design |
| Early risk analysis | Costly due to rework & continuous cycles |
| Suitable for long-term projects | No fixed number of cycles, closure uncertain |

**Summary:**

*   Spiral = **Iterative + Controlled + Risk-focused**
    
*   Allows partial delivery & ongoing enhancements
    
*   Overcomes Waterfall rigidity but still **delays early testing**
    

**Common Problem in Waterfall & Spiral:**

*   Testing occurs **after coding**, not during Requirements/Design → late defect discovery.
    
    ## 1️⃣ Software Development Life Cycle (SDLC)
    
    **Definition:**  
    SDLC is the process used to **design, develop, and test high-quality software**.
    
    **Key Phases of SDLC (6 Phases):**
    
    | Phase | Description | Example |
    | --- | --- | --- |
    | Requirement Gathering & Analysis | Understand what the customer wants. Conduct feasibility (technical, financial, time). Document requirements in SRS, FRS, BRS. | A bank wants an app for login, balance, fund transfer. |
    | Design | Blueprint of software. HLD = architecture/modules, LLD = detailed module design. Use diagrams. | User flow: login → dashboard → transfer funds |
    | Development (Coding) | Developers write code based on design. May include unit tests and integration points. | Code for login validation, fetch balance from DB, fund transfer API |
    | Testing | QA tests software for bugs. Types: functional, non-functional. Report defects. | Test invalid login, check transfer only with sufficient balance |
    | Deployment | Software goes live for users. | App uploaded to Play Store or installed in bank |
    | Maintenance | Fix bugs, add features, ensure compatibility. | Fix fund transfer issue at midnight |
    
    * * *
    
    ## 2️⃣ SDLC Models Overview
    
    **Purpose:** Defines how SDLC phases flow from requirements to maintenance.
    
    **Popular Models:**
    
    1.  **Waterfall Model** – Linear & sequential, best for **small, fixed projects**.
        
    2.  **V-Model** – Waterfall with **testing at every phase**.
        
    3.  **Iterative Model** – Software built in **iterations**, each adds features.
        
    4.  **Spiral Model** – Iterative + **risk analysis**, for **complex/high-risk projects**.
        
    5.  **Agile Model** – **Short sprints**, continuous feedback, flexible requirements.
        
    
    * * *
    
    ## 3️⃣ Waterfall Model (Linear Model)
    
    **Characteristics:**
    
    *   Step-by-step flow; **no going back**.
        
    *   Documentation-heavy.
        
    *   Works well when requirements are **clear & fixed**.
        
    
    **Phases & Roles:**
    
    | Phase | Who’s involved | Example |
    | --- | --- | --- |
    | Requirement Gathering | BA, Client, Product Manager | Understand login, balance, transfer features |
    | Design | Architects, Designers | Plan user flow, system architecture |
    | Development | Developers | Code login, transfer features |
    | Testing | QA Testers | Test login, transfer functionality |
    | Deployment | DevOps, Release Team | Upload app or deliver to client |
    | Maintenance | Developers, Support Team | Fix “midnight transfer” bug |
    
    **Pros vs Cons:**
    
    | Advantages | Disadvantages |
    | --- | --- |
    | High product quality | Cannot change requirements mid-way |
    | Less chances of bugs | Defect propagation if early mistakes happen |
    | Low initial investment | High rework cost if bugs found late |
    | Structured & manageable | Testing happens late |
    
    ✅ **Best for:** Small projects with fixed requirements  
    ❌ **Not suitable for:** Projects with frequent changes
    
    * * *
    
    ## 4️⃣ Spiral Model (Iterative + Risk-Focused)
    
    **Purpose:** Combines **Waterfall structure** with **iterations & risk analysis**.  
    Used for **large, complex projects** where requirements evolve.
    
    **Each Spiral Cycle has 4 steps:**
    
    | Step | What happens | Example |
    | --- | --- | --- |
    | Planning | Define objectives, deliverables, assign roles | Login feature: define functionality, tech stack, responsibilities |
    | Risk Analysis | Identify risks, plan mitigation | OTP SMS gateway may fail → fallback to email |
    | Development & Testing | Code module, test functionality | Developers code login, testers validate login & security |
    | Evaluation | Customer reviews, feedback collected | Add “Forgot Password” next cycle, change button color |
    
    **Pros vs Cons:**
    
    | Advantages | Disadvantages |
    | --- | --- |
    | Testing each cycle | Requirement changes not allowed mid-cycle |
    | Customer gets working software each cycle | No early testing during Requirement & Design |
    | Early risk analysis | Costly due to rework & continuous cycles |
    | Suitable for long-term projects | No fixed number of cycles, closure uncertain |
    
    **Summary:**
    
    *   Spiral = **Iterative + Controlled + Risk-focused**
        
    *   Allows partial delivery & ongoing enhancements
        
    *   Overcomes Waterfall rigidity but still **delays early testing**
        
    
    **Common Problem in Waterfall & Spiral:**
    
    *   Testing occurs **after coding**, not during Requirements/Design → late defect discovery.
