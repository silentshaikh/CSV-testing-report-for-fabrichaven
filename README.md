# 🛠️ CSV Testing Report for Fabric Haven  

This document provides a structured **test report** for Fabric Haven, ensuring functionality, error handling, responsiveness, and user experience.  

## 📋 Test Cases  

| 🆔 Test Case ID | 📝 Description                           | 🔄 Test Steps                                      | 🎯 Expected Result                                  | ✅ Actual Result                                   | 📌 Status  | 🏷️ Remarks                                |
|---------------|----------------------------------|------------------------------------|-------------------------------------|--------------------------------------|--------|-------------------------------------|
| **TC001**    | 🏷️ Validate Product Listing     | Open product page > Verify product | Product should be displayed         | ✅ Product displayed                 | ✅ Passed  | No issues found                    |
| **TC002**    | 🛠️ Test API Error Handling      | Trigger Discount API error > Refresh page | Show fallback UI with a user-friendly message | ✅ Fallback UI shown                 | ✅ Passed  | Handled gracefully                  |
| **TC003**    | 🛒 Cart Functionality           | Add item to cart > Verify cart    | Cart should work perfectly          | ✅ Cart works perfectly               | ✅ Passed  | Works as expected                   |
| **TC004**    | 📱 Test Responsiveness          | Resize window > Check layout in different browsers | Layout should adjust perfectly      | ✅ Layout adjusts correctly           | ✅ Passed  | UI can be improved for better UX   |
| **TC005**    | 🔍 Search Functionality         | Enter product name in search bar > Verify results | Correct product list should appear | ✅ Search works correctly             | ✅ Passed  | Performance is good                 |
| **TC006**    | 📦 Checkout Process            | Add product to cart > Proceed to checkout | Checkout should complete smoothly  | ✅ Checkout works as expected         | ✅ Passed  | Consider adding a progress bar      |
