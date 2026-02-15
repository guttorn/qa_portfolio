# Demoblaze Bug Reports

---

## 🐞 BUG-001
### Title:
System allows placing order with invalid customer information

### Environment:
- Website: demoblaze.com
- Browser: Chrome
- OS: Windows 11

### Preconditions:
Product added to cart

### Steps to Reproduce:
1. Open demoblaze.com
2. Add product to cart
3. Open Cart page
4. Click “Place Order”
5. Enter invalid data:
   - Name: A
   - Country: A
   - City: A
   - Month: 00
6. Click “Purchase”

### Expected Result:
System should validate input fields and prevent order submission until valid data is provided

### Actual Result:
System allows order to be placed with invalid customer information

### Severity:
High

### Priority:
High

---

## 🐞 BUG-002
### Title:
Checkout form accepts invalid card details and allows purchase submission

### Environment:
- Website: demoblaze.com
- Browser: Chrome
- OS: Windows 11

### Preconditions:
Product added to cart

### Steps to Reproduce:
1. Open demoblaze.com
2. Add product to cart
3. Open Cart page
4. Click “Place Order”
5. Enter invalid card details (e.g. letters or short number)
6. Click “Purchase”

### Expected Result:
System should validate card input and block purchase with invalid card data

### Actual Result:
System accepts invalid card details and allows purchase

### Severity:
High

### Priority:
High

