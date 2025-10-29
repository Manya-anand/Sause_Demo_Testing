
#  Manual Testing Project – Sauce Demo Shopify

### Tester: Manya Anand  
### Website Tested: [https://sauce-demo.myshopify.com/](https://sauce-demo.myshopify.com/)

---

## 1. Objective
The purpose of this project is to perform **manual functional testing** on two key features of the **Sauce Demo Shopify** website:
1. **Login Functionality**  
2. **Cart and Checkout Flow**

The goal was to verify that these user flows work as expected and meet functional requirements.

---

## 2. Scope
**In Scope**
- Login with valid, invalid, and empty credentials  
- Cart operations (add, remove, quantity behavior)  
- Checkout process (valid and invalid input validation)

**Out of Scope**
- Payment gateway testing  
- Backend or API testing  
- Performance, security, and stress testing  

---

## 3. Type of Testing Performed
- Functional Testing  
- UI/UX Testing  
- Negative Testing  

---

## 4. Test Environment
| Parameter | Details |
|------------|----------|
| Website | [https://sauce-demo.myshopify.com/](https://sauce-demo.myshopify.com/) |
| Browser | Google Chrome (latest version) |
| OS | Windows 10 |
| Internet | Stable broadband connection |
| Device | Desktop |

---

## 5. Test Artifacts
| Artifact | Description |
|-----------|--------------|
| 🧾 **Test Plan (Doc)** | Includes objectives, scope, environment, and execution details |
| 📊 **Test Cases (Google Sheet)** | Contains 13 test cases covering Login, Cart, and Checkout features |

**Test Case Sheet Link:**  
[Click here to view the Google Sheet](https://docs.google.com/spreadsheets/d/1JCr3twozP-ftCPNwdO1fwZQ5lmHdynbHdjunUzYE52U/edit?usp=sharing)

---


## 6. Notable Observation
When the same product is added multiple times, the cart correctly displays the increased quantity.  
However, clicking **“Remove”** removes the entire product instead of reducing the quantity by one.  
This behavior is consistent and might be part of the website’s intended design.

---

## 7. Tools Used
- **Browser:** Google Chrome  
- **Documentation:** Google Docs (Test Plan)  
- **Test Management:** Google Sheets (Test Cases)  
- **Version Control:** GitHub  

---

## 8. Key Learnings
- Created professional QA documentation: Test Plan and Test Case Sheet.  
- Designed and executed real-world test cases for e-commerce functionalities.  
- Practiced Functional and Negative Testing for web applications.  
- Observed and documented consistent user behaviors accurately.  

---

## 9. Summary
All major functionalities of the Sauce Demo Shopify website were tested successfully.  
Login, Cart, and Checkout workflows behaved as expected without any functional defects.

---

## 10. Future Improvements
- Automate smoke test cases using **Selenium + Python**.  
- Add **cross-browser testing** (Firefox, Edge).  

---

### Author
**Manya Anand**  


---
