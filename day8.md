# 1️⃣ REGRESSION TESTING

# 

**Definition:** Regression testing ensures that new changes like bug fixes, new features, or code updates do not break the existing functionality of the application.

**Example:**

*   In Build 2, the developer adds the "Upload Profile Picture" feature.
    
*   Tester must still check that Login, Profile, Send Messages, etc., work correctly.
    

**Emoji Tip:** 🧪➡️✅ (Test new changes → Old features still work)

* * *

## TYPES OF REGRESSION TESTING

### 1\. UNIT REGRESSION TESTING

# 

**Definition:** Focuses only on the specific change made by the developer. Other areas are not tested.

**Example:**

*   Bug: “Password reset not working.”
    
*   Developer fixes it → Tester checks ONLY the password reset function.
    
*   Tester does not check login, profile, etc.
    

**Use Case ✅:** Low risk, small change.

* * *

### 2\. REGIONAL REGRESSION TESTING

# 

**Definition:** Tests the changed functionality plus related/connected features.

**Example:**

*   Bug: “Login not working.”
    
*   Login affects Profile and Dashboard.
    
*   Tester checks: Login, Profile, Dashboard.
    

**Use Case ✅:** When nearby modules might be affected.

* * *

### 3\. FULL REGRESSION TESTING

# 

**Definition:** Test the entire application when major changes are made.

**Example:**

*   Payment module updated → Might affect Login, Profile, Cart, Checkout, Notifications, Reports.
    
*   Tester retests everything to ensure system stability.
    

**Use Case ✅:** High risk, many modules touched.

**Summary Table:**

| Term | Focus | Example |
| --- | --- | --- |
| Unit Regression | Only changed part | Test “Password Reset” fix |
| Regional Regression | Changed part + connected parts | Test Login + Profile + Dashboard |
| Full Regression | Entire application | Test all modules after major changes |

* * *

## IMPACT ANALYSIS MEETING

# 

**Definition:** Meeting between developers and testers before regression to decide test scope and impacted areas.

**Example:**

*   Developer: “I changed code in Profile Picture Upload.”
    
*   Tester: Must test Profile Module + Login + Dashboard.
    

* * *

# 2️⃣ RETESTING

# 

**Definition:** Retesting means testing the same bug again after the developer has fixed it.

**Purpose:** Confirm the defect is actually resolved.

**Tester Actions:**

*   If fix works → close bug ✅
    
*   If fix fails → reopen bug ❌
    

**When:** Every time a developer fixes a bug and provides a new build.

**Example:**

*   Build 1.0 → Bugs 1.0.1, 1.0.2 found → Build 1.1 → Tester checks same bugs again.
    

**Key Points:**

*   Only for bug fixes.
    
*   Same test cases executed multiple times.
    
*   Focus only on defect, not impacted areas.
    

* * *

### RETESTING vs REGRESSION TESTING

# 

| Aspect | RETESTING | REGRESSION TESTING |
| --- | --- | --- |
| Focus | Specific bug fix | Overall system stability after changes |
| Scope | Only reported defect | Defect + connected modules |
| Example | Test only Purchase module bug fix | Test Purchase + Finance module (Finance depends on Purchase) |
| When | After developer fixes bug | After any change (bug fix, new feature, modification) |
| Subset? | Part of regression | Includes retesting + impacted areas |

**Summary:**

*   Retesting = Did the bug get fixed? ✅
    
*   Regression = Did the fix break anything else? ⚠️
    
*   Relation: Regression = Retesting + Impact Verification
    

* * *

# 3️⃣ SMOKE TESTING

# 

**Definition:** Checks if a build is stable enough for further testing. Also called Build Verification Test (BVT).

**Focus:** Build stability (installation, screens, navigation).

**Example:**

*   App installs without crash.
    
*   Basic screens appear.
    
*   Database/API works.
    

**Phone Example:**

*   Smoke = Can phone switch ON? 📴➡️📱
    
*   Sanity = Can phone make a call? 📞
    

* * *

# 4️⃣ SANITY TESTING

# 

**Definition:** Checks if basic functionality works after a stable build.

**Example:**

*   Login, Signup, Logout.
    
*   Sign up redirects correctly, login works.
    

**Difference:**

| Aspect | Smoke Testing | Sanity Testing |
| --- | --- | --- |
| Objective | Ensure build is stable | Ensure basic functionality works |
| Performed by | Developers & Testers | Testers only |
| Build Condition | Early / unstable | Relatively stable |
| Depth | Shallow, stability | Shallow, functional |
| Frequency | Every new build | When stable, time-limited |

**Workflow:** Smoke → Sanity → Detailed Testing

* * *

# 5️⃣ EXPLORATORY TESTING

# 

**Definition:** Learn, explore, and test the app without documentation.

**Use Case:**

*   App ready but no requirements/test cases.
    
*   Tester has little knowledge of the application.
    

**Example:**

*   New e-commerce app → login, add to cart, checkout → note observations.
    

**Drawbacks:**

*   Might mistake a feature as a bug.
    
*   Time-consuming.
    

**Summary:** Exploratory = Learn + Explore + Test

* * *

# 6️⃣ AD HOC TESTING

# 

**Definition:** Random, informal testing without test cases or documentation. Tester usually knows the app.

**Purpose:** Find hidden or corner bugs quickly.

**Example:**

*   Tester knows Axis Bank Net Banking → randomly tests HDFC Bank app.
    

**Characteristics:** Random, Unplanned, Knowledge-based, Informal

* * *

# 7️⃣ MONKEY TESTING

# 

**Definition:** Random testing with no knowledge, plan, or documentation; goal is to break system.

**Example:**

*   Child presses random buttons in a mobile game.
    

**Usage:** Mainly in gaming or highly interactive apps.

**Comparison Table:**

| Aspect | Exploratory | Ad-hoc | Monkey |
| --- | --- | --- | --- |
| Knowledge | None | Some | None |
| Approach | Explore → test | Random → break | Pure random |
| Purpose | Learn & understand | Break hidden bugs | Break randomly |

* * *

# 8️⃣ POSITIVE TESTING

# 

**Definition:** Tests system with valid inputs. Confirms it works as expected.

**Example:**

*   Login with correct username/password → success ✅
    
*   Calculator 2+3 → 5
    
*   Form submission valid → success
    

* * *

# 9️⃣ NEGATIVE TESTING

# 

**Definition:** Tests system with invalid/wrong inputs to see if errors are handled properly.

**Example:**

*   Wrong password → reject login ❌
    
*   File .exe upload → error
    
*   Expired credit card → payment rejected
    

* * *

# 🔟 END-TO-END TESTING (E2E)

# 

**Definition:** Tests complete workflow from start to finish.

**Example:** E-commerce:

*   Login → Add to cart → Checkout → Payment → Order confirmation → Email received
    

**Goal:** Ensure all components interact correctly and workflow functions as expected.

* * *

# 1️⃣1️⃣ GLOBALIZATION TESTING

# 

**Definition:** Check if the application works across countries, languages, currencies, and formats.

**Example:** PayPal, Amazon

* * *

# 1️⃣2️⃣ LOCALIZATION TESTING

# 

**Definition:** Check if the application is adapted to a specific locale/region.

**Example:** Chinese banking app (Chinese language + currency)

**Key Difference Table:**

| Aspect | Globalization | Localization |
| --- | --- | --- |
| Purpose | Work globally | Work locally |
| Language | Multiple | One region |
| Currency | Multiple | Local |
| Example | PayPal, Amazon | India-specific app |

**Summary:**

*   Globalization = Work anywhere 🌎
    
*   Localization = Work perfectly in one region 🏠
