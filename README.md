## Lab 7 - End-to-End Testing with Puppeteer

**Name:** Samson Gebrekidan  

---

### Check Your Understanding

**1) Where would you fit your automated tests in your Recipe project development pipeline?**  
I would use a **GitHub Action** that runs whenever code is pushed. This way, tests run automatically to catch bugs early before deployment.

**2) Would you use an end-to-end test to check if a function is returning the correct output?**  
No. End-to-end tests simulate user interactions. To test function outputs, unit tests are more appropriate.

**3) What is the difference between navigation and snapshot mode?**  
Navigation mode reloads the whole page and tests full performance.  
Snapshot mode tests the current state of the page without reloading.

**4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.**  
1. Use optimized image formats (e.g., WebP)  
2. Improve accessibility (e.g., contrast, alt text)  
3. Minimize unused JavaScript/CSS to speed up performance
