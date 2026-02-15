---
editor_options: 
  markdown: 
    wrap: 72
---

**Test Scenarios:**

1.  Browse product catalog and open flashlight product page

2.  Search for a product using search bar (e.g. “Baton”)

3.  Filter products by category / price and verify results

4.  Add flashlight to cart, change quantity, and remove item

5.  Proceed to checkout as guest user until payment page

**TC-001 for scenario #1: Open product from catalog**

**Test Case ID:** TC-001\
**Title:** Open product page from catalog

**Objective:**\
Verify that user can open product page from catalog and view product
details

**Preconditions:**

-   User is on Olight.com website

-   User is not logged in (optional)

**Steps:**

1.  Open Olight.com

2.  Click “All Products”

3.  Select “Everyday Carry” category

4.  Click on “Olight i3T 2 EOS Small” product

5.  Review product description, images, and reviews

**Expected Result:**\
Product page is opened and displays correct product information, images,
price, and reviews

**Actual Result:**\
Product page is opened and displays correct product information

**TC-002 for scenario #2: Search for a product using search bar (e.g.
“Baton”)**

**Test Case ID:** TC-002\
**Title:** Search for product using search bar (keyword: “Baton”)

**Objective:**\
Verify that user can find a specific product using search functionality

**Preconditions:**

-   User is on Olight.com website

-   User is not logged in (optional)

**Steps:**

1.  Open Olight.com

2.  Click on the search icon / search field

3.  Enter keyword “Baton”

4.  Press “Enter” or click Search button

**Expected Result:**\
Search results display products related to “Baton” keyword

**Actual Result:**\
Products related to “Baton” are displayed in search results

**TC-003 for scenario #4: Add flashlight to cart, change quantity, and
remove item**

**Test Case ID:** TC-003\
**Title:** Add product to cart and update quantity

**Objective:**\
Verify that user can add product to cart, change quantity, and see
updated total price

**Preconditions:**

-   User is on Olight.com website

-   User is not logged in (optional)

**Steps:**

1.  Open Olight.com

2.  Navigate to “All Products” → “Everyday Carry”

3.  Select “Olight Baton Turbo Compact” product

4.  Click “Add to Cart”

5.  Open Cart

6.  Increase product quantity using “+” button

7.  Proceed to Checkout page

**Expected Result:**\
Product is added to cart\
Quantity is updated correctly\
Total price changes according to selected quantity

**Actual Result:**\
Product is added to cart\
Quantity can be changed\
Total price is updated correctly

**Test Case ID:** TC-004\
**Title:** Attempt to add large quantity (99 items) to cart

**Objective:**\
Verify system behavior when user tries to add a large quantity of
product to cart

**Preconditions:**

-   User is on Olight.com website

-   User is not logged in (optional)

**Steps:**

1.  Open Olight.com

2.  Navigate to “All Products” → “Everyday Carry”

3.  Select “Olight Baton Turbo Compact”

4.  Click “Add to Cart”

5.  Open Cart

6.  Enter quantity “99” in quantity field

7.  Click outside the field

8.  Proceed to Checkout

**Expected Result:**\
System validates entered quantity\
Quantity is limited to available stock\
Total price is updated accordingly

**Actual Result:**\
System automatically adjusts quantity to available stock\
User cannot order 99 items\
Total price is updated correctly

## 📄 PROJECT OVERVIEW

**Project Name:** Olight E-commerce Website Testing\
**Website:** <https://www.olight.com>\
**Role:** Manual QA Tester\
**Testing Type:** Functional & Exploratory Testing

**Description:**\
The purpose of this project was to test core functionality of the Olight
e-commerce website, including website navigation, search functionality,
cart management, and checkout process.

## 📌 SCOPE OF TESTING

**Tested Features:**

-   Product catalog availability

-   Product search functionality

-   Product details and reviews page

-   Shopping cart

-   Quantity management

-   Checkout flow (until payment step)

**Not Tested:**

-   Payment processing

-   Account registration

-   Admin panel

-   Guest checkout (non-registered users)

## 🧪 TEST ARTIFACTS

**Created Test Cases:**

-   TC-001 — Open product from catalog

-   TC-002 — Search product

-   TC-003 — Add to cart & update quantity

-   TC-004 — Large quantity validation

**Total Test Cases:** 4\
**Negative Test Cases:** 1\
**Edge Cases:** 1

## 🐞 DEFECTS SUMMARY

No critical defects were found during testing.\
The system correctly handled quantity validation and prevented ordering
beyond available stock.

## 📊 TEST RESULTS

| Status  | Count |
|---------|-------|
| Passed  | 4     |
| Failed  | 0     |
| Blocked | 0     |

## 🚀 CONCLUSION

Olight website functionality works properly.\
Product browsing, searching, cart operations, and quantity validation
are stable and user-friendly.\
No major issues affecting user experience were detected during this
testing cycle.
