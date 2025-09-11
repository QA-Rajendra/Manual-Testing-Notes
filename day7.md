# 📅 Non-Functional Testing (NFT)

## 

**Definition:**  
Non-Functional Testing checks **how well** a software application works, unlike Functional Testing which checks **what it does**.

* * *

## 🔹 Focus Areas

## 

*   ⚡ **Performance** – Speed & responsiveness
    
*   🔒 **Security** – Data protection & access control
    
*   ♻️ **Recovery** – System recovery from failures
    
*   🖥 **Installation & Configuration** – Setup on various systems
    
*   🌐 **Compatibility** – Different devices, OS, browsers
    
*   🗑 **Sanitation / Garbage Testing** – Checks leftover or unnecessary data
    

**Key Points:**

*   Performed after functional testing is stable ✅
    
*   Needs dedicated teams & environments 👥
    
*   Requires specialized tools & skills 🛠️
    

* * *

## 🟢 Functional vs Non-Functional Testing

## 

| Aspect | Functional Testing | Non-Functional Testing |
| --- | --- | --- |
| Focus | Does software work? | How well software works |
| Key Question | WHAT does it do? | HOW WELL does it perform? |
| Example | Login functionality works ✅ | System handles 1000 users simultaneously ⚡ |

* * *

# ⭐ Types of Non-Functional Testing

## 1️⃣ Performance Testing (Speed, Stability, Responsiveness)

## 

**Subtypes:**

*   **Load Testing** – Check app under expected user load.
    
    *   Measures: Response time, throughput, turnaround time ⏱️
        
    *   Tools: JMeter, LoadRunner
        
    *   Example: 1000 concurrent users on an e-commerce site 🛒
        
*   **Stress Testing** – Check app under **beyond expected load** to find breaking point 💥
    
    *   Example: Expected 1000 users → test with 1200, 1300, … until failure
        
*   **Endurance / Soak Testing** – Check long-term stability under expected load ⏳
    
    *   Focus: Memory leaks, performance degradation
        
    *   Example: Tax-filing app running continuously for 24+ hours 📄
        
*   **Spike Testing** – Check app under sudden increase/decrease in users ⚡
    
    *   Example: E-commerce sale causes users to jump 100 → 200 instantly
        
*   **Volume Testing** – Check app with large data volume 💾
    
    *   Example: Insert millions of rows in database for e-commerce app
        

**Comparison Table – Performance Testing Types**

| Type | Goal | Load Pattern | Example |
| --- | --- | --- | --- |
| Load | Expected load | Gradual | 10,000 daily users |
| Stress | Find breaking point | Gradual beyond limit | Push app to 50,000+ users |
| Endurance | Stability over time | Constant | 10,000 users for 72 hrs |
| Spike | Sudden traffic change | Sudden increase/decrease | TV ad → 30,000 users instantly |
| Volume | Handle huge data | Large data sets | Millions of DB records |

* * *

## 2️⃣ Security Testing 🔒

## 

**Purpose:** Protect sensitive data & prevent unauthorized access

**Key Areas:**

*   **Authentication** – Only valid users can log in ✅
    
*   **Authorization** – Permissions for each user role 🔑
    
*   **Network Security** – Protect data in transit 🌐
    
*   **Data Encryption & Decryption** – Secure transmission 🔏
    
*   **Client-side & Server-side Security**
    
*   **Vulnerability Testing** – Identify system weaknesses
    

**Example:** Online banking – valid login, encrypted network data, role-based access 💳

* * *

## 3️⃣ Recovery Testing ♻️

## 

**Purpose:** Ensure system recovers from failures without losing data

**Scenarios:**

*   Power outage ⚡
    
*   Database crash 🗄️
    
*   Network failure 🌐
    
*   Application crash 💥
    
*   API failure 🔌
    

**Example:** Composing Gmail email → power loss → email saved in Drafts ✉️

* * *

## 4️⃣ Compatibility Testing 🌐

## 

Ensures software works across:

*   **OS** – Windows, Mac, Linux 💻
    
*   **Browser** – Chrome, Firefox, Edge, Safari 🌍
    
*   **Hardware** – Different RAM, CPU, HDD ⚙️
    
*   **Backward & Forward Compatibility** – Old & future versions 🔄
    

**Example:** WhatsApp works on Android & iOS devices with different screen sizes 📱

* * *

## 5️⃣ Configuration Testing ⚙️

## 

Ensures software works under different system setups:

*   Hardware: RAM, CPU, HDD 💻
    
*   Software: OS versions, plugins 🖥️
    
*   Network: Wi-Fi, LAN, 4G/5G 🌐
    
*   Version updates: Forward/backward compatibility 🔄
    

**Example:** Video game runs smoothly on PCs with 8GB vs 16GB RAM 🎮

* * *

## 6️⃣ Installation Testing 💾

## 

Checks smooth installation, uninstallation, and updates

**Focus Areas:**

*   Installation process & screen clarity 🖱️
    
*   Uninstallation removes all files 🗑️
    
*   Reinstallation works fine 🔄
    
*   Auto-update functionality ⬆️
    

**Example:** Word processor installs → uninstall → reinstall → updates without errors ✅

* * *

## 7️⃣ Sanitation / Garbage Testing 🗑

## 

Checks for extra, leftover, or unnecessary features/data

**Example:** Bank software customized for Bank Y shouldn’t show extra features from Bank X 🏦

* * *

## ✅ Summary Table – Non-Functional Testing Overview

## 

| Type | Purpose / Focus | Example / Notes |
| --- | --- | --- |
| Performance | Speed, response, stability under load | Load, stress, endurance, spike, volume testing |
| Security | Protect data & access control | Online banking app secure from hackers |
| Recovery | Recover after failures | Power outage, database crash, API failure |
| Compatibility | Works on all devices, OS, browsers | Mobile apps Android/iOS, web apps Chrome/Firefox |
| Configuration | Works under different hardware/software | Game tested on PCs with different RAM & CPU |
| Installation | Smooth install/uninstall, auto-updates | Software installs/uninstalls properly |
| Sanitation | Remove extra/unused features | Bank software with leftover features flagged |

* * *

## 🔑 Key Takeaways

## 

*   Functional Testing → _WHAT the app does_
    
*   Non-Functional Testing → _HOW WELL the app performs_
    
*   NFT requires:
    
    *   Specialized tools 🛠️
        
    *   Long-term monitoring ⏳
        
    *   Simulation of real-world scenarios 🌍
