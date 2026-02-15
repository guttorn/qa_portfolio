**Test Scenarios:**

1.  Browse product categories and product list

2.  Open product details page

3.  Add selected product to cart

4.  View cart page and manage cart items

5.  Proceed to checkout and submit order form

**TC-001 for scenario #1: Browse product categories and product list**

**Test Case ID:** TC-001\
**Title:** Verify product categories filtering

**Objective:**\
Verify that user can browse products by selecting different categories

**Preconditions:**

-   User is on demoblaze.com website

-   User is not logged in (optional)

**Steps:**

1.  Open demoblaze.com

2.  Click “Phones” category

3.  Verify that only phone products are displayed

4.  Click “Laptops” category

5.  Verify that only laptop products are displayed

6.  Click “Monitors” category

7.  Verify that only monitor products are displayed

**Expected Result:**\
Products displayed correspond to selected category

**Actual Result:**\
Products are filtered correctly according to selected category

**TC-002 for scenario #2: Open product details page**

**Test Case ID:** TC-002\
**Title:** Verify product details page displays correct information

**Objective:**\
Verify that user can open product details page and view product information

**Preconditions:**

-   User is on demoblaze.com website

-   User is not logged in (optional)

**Steps:**

1.  Open demoblaze.com

2.  Click on a product (e.g. “Sony Xperia Z5”)

3.  Verify that product details page is opened

4.  Verify product name, image, price, and description are displayed

**Expected Result:**\
Product details page is opened and displays correct product information

**Actual Result:**\
Product details page is opened and shows correct product information

**TC-003 for scenario #3: Add selected product to cart**

**Test Case ID:** TC-003\
**Title:** Verify product can be added to cart

**Objective:**\
Verify that user can add selected product to shopping cart

**Preconditions:**

-   User is on demoblaze.com website

-   User is not logged in (optional)

**Steps:**

1.  Open demoblaze.com

2.  Click on a product (e.g. “Sony Xperia Z5”)

3.  Verify product details page is opened

4.  Click “Add to Cart” button

5.  Verify alert message “Product added” is displayed

6.  Click “OK”

7.  Click “Cart”

8.  Verify selected product appears in cart

**Expected Result:**\
Selected product is successfully added to cart and displayed in cart page

**Actual Result:**\
Product is added to cart and displayed correctly

**TC-004 for scenario #4: Browse cart page and cart administration**

**Test Case ID:** TC-004\
**Title:** Verify product can be removed from cart

**Objective:**\
Verify that user can remove selected product from shopping cart

**Preconditions:**

-   User is on demoblaze.com website

-   User is not logged in (optional)

**Steps:**

1.  Open demoblaze.com

2.  Open product page (e.g. “Sony Xperia Z5”)

3.  Click “Add to Cart”

4.  Verify alert “Product added” is displayed

5.  Click “OK”

6.  Open Cart page

7.  Verify selected product is displayed

8.  Click “Delete”

9.  Verify product is removed from cart

**Expected Result:**\
Selected product is successfully removed from cart

**Actual Result:**\
Product is removed from cart successfully

**TC-005 for scenario #5: Proceed to checkout and submit order form**

**Test Case ID:** TC-005\
**Title:** Verify checkout process and order confirmation

**Objective:**\
Verify that user can complete checkout process and receive order confirmation

**Preconditions:**

-   User is on demoblaze.com website

-   Product is added to cart

-   User is not logged in (optional)

**Steps:**

1.  Open demoblaze.com

2.  Add product to cart

3.  Open Cart page

4.  Click “Place Order”

5.  Fill required fields:

    -   Name: John Smith

    -   Country: Canada

    -   City: Coquitlam

    -   Card Number: 1234567891234561

    -   Month: 01

    -   Year: 01

6.   Click “Purchase”

7.  Verify confirmation popup appears

8.  Verify order details are displayed (order id, amount, card number, name, date)

9.  Click “OK”

**Expected Result:**\
Order is successfully placed and confirmation message is displayed

**Actual Result:**\
Order is successfully placed and confirmation message is displayed with order details
