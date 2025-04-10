# Amazon Mobile App – Manual Testing
![Amazon Logo](https://github.com/theabhishekmauryaa/Mobile_Testing_amazon_Application/blob/main/Amazon-Logo.png)

## Introduction
The Amazon Mobile App is a widely used e-commerce platform that allows users to browse, search, add to cart, and purchase items. This test plan focuses on ensuring that all core functionalities of the Amazon mobile app perform as expected on Android and iOS devices through comprehensive manual testing.

## Scope
- **Functional Testing:** Verify key modules like Login, Search, Product Listing, Product Details, Add to Cart, Checkout, and Order Tracking.
- **UI/UX Testing:** Ensure a user-friendly interface, responsiveness, and consistent layout across screen sizes.
- **Performance Testing:** Basic checks on load times and responsiveness of high-traffic features.
- **Security Testing:** Validate secure login and data privacy during transactions.
- **Device Compatibility Testing:** Test across various screen sizes and OS versions.

## Test Strategy

### Manual Testing
- **Mind Map Creation:** Understand flow from login to checkout.
- **Test Scenario Development:** Identify real-world user actions (search, purchase, track order, etc.).
- **Test Case Execution:** Execute prepared test cases and log issues.
- **Bug Reporting:** Log bugs in Excel sheet or JIRA.
- **Test Summary Report:** Track defects, coverage, and status.

## Test Scenarios

### 1. Login Functionality
- Test login with valid and invalid credentials.
- Validate OTP and password login.
- Forgot password flow.

### 2. Search Functionality
- Search by product name, category, or brand.
- Search with special characters, empty strings, or long text.
- Apply filters and sort results.

### 3. Product Listing & Details
- Open product pages from listings.
- Verify product info, images, and pricing.
- Check "Add to Wishlist" and "Share" options.

### 4. Add to Cart
- Add single and multiple items.
- Update quantity, remove products.
- Verify cart total and item details.

### 5. Checkout Process
- Verify address selection, payment options.
- Apply promo codes and coupons.
- Confirm order placement.

### 6. Order Tracking
- Track placed orders.
- Cancel, return, or replace options.

### 7. Notifications
- Test push and in-app notifications.

### 8. Device-Level Events
- App behavior during calls, multitasking, or background state.

### 9. Network Conditions
- Behavior under Wi-Fi, Mobile Data, or offline mode.

### 10. Logout & Data Clearing
- Logout flow, data retention, re-login.

## Test Cases

| **Test Case ID** | **Description** | **Steps** | **Expected Result** | **Status** |
|------------------|-----------------|-----------|---------------------|------------|
| TC001 | Verify login functionality | Enter valid credentials and submit | User is logged in successfully | Pending |
| TC002 | Search with valid keyword | Type “Shoes” in search bar and submit | Relevant results are displayed | Pending |
| TC003 | Add item to cart | Select a product and tap “Add to Cart” | Product added to cart | Pending |
| TC004 | Checkout using COD | Proceed to checkout and select COD | Order placed successfully | Pending |
| TC005 | View order status | Go to “Your Orders” and select an order | Tracking info is visible | Pending |

## Bug Reporting
All bugs will be reported with the following details:
- **Bug ID**
- **Title**
- **Environment**
- **Severity / Priority**
- **Steps to Reproduce**
- **Expected vs Actual Result**
- **Screenshot/Video (if applicable)**

## Test Summary Report
At the end of the cycle, a test summary will include:
- Total test cases executed
- Number of pass/fail cases
- List of bugs with status
- Recommendations for improvements

## Prepared by:
Abhishek Maurya  
Date: 10-04-2025
