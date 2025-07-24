---
icon: alert
nav:
  badge: NEW|info
tags: [guide]
---

# Troubleshooting Guide

If you encounter any problems while setting up or running your Profilie website, this comprehensive guide will help you quickly identify and resolve common issues.  

Follow the steps below to troubleshoot and get your project back on track.

---

### **IMPORTANT:**  
!!!danger  
**Make sure your `config.js` is correctly configured!**  
Most problems stem from configuration errors. Double-check your setup before proceeding.
!!!

---

## JavaScript Loading Error

One of the most common issues is the **JavaScript Loading Error: 722**.  

### What does it mean?  
This error typically indicates that your `config.js` is not properly configured or there's a syntax issue.

### How to fix it:

1. Verify that your `config.js` file is correctly set up.  
2. Ensure all quotes (`""`) and backticks (`` ` ``) are correctly placed and balanced.  
3. Confirm that no accidental modifications have been made to the file.  
4. Check that your `index.html` is properly linked and unaltered in a way that breaks the setup.

---

#### Sample Error Message:  
![JavaScript Loading Error](media/javascript-loading-error.png)

---

### Common Causes:  
- Mistakes in your configuration code  
- Improper use of quotes or backticks  
- Changes to `config.js` or `index.html` that introduce syntax errors  
- Incorrect file paths or missing files

---

### Need Further Assistance?  

If you’ve checked everything and still see this error, and you're confident your files are correct, please **reach out to us**!  

Email us at: [profilie@harys.is-a.dev](mailto:profilie@harys.is-a.dev) and we will investigate your issue immediately.

---

## Additional Tips

- Always validate your JavaScript syntax before deploying.  
- Use browser developer tools (Console) to identify errors.  
- Review your recent changes to `config.js` and `index.html` for mistakes.

**Remember:** Most issues are easily fixed with a careful review of your configuration files. Happy profiling! 🚀
