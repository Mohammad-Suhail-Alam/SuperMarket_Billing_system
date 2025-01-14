# SuperMarket Billing System

Welcome to the **SuperMarket Billing System**!  
This project is a simple Python program designed to handle billing for a supermarket. It allows customers to select products, calculate the total cost, apply discounts, and generate a detailed receipt.

---

## Features:
- Displays a list of available products and their prices.
- Allows customers to purchase multiple products in desired quantities.
- Calculates the total amount and applies discounts based on the total.
- Generates an itemized bill/receipt with details of each product.
- Supports handling multiple customers in a single session.

---

## Workflow:
1. A customer enters their name and contact details.
2. The program displays the available products and their prices.
3. The customer selects the product(s) they want to buy and specifies the quantity.
4. The program calculates the total amount and applies a discount based on the following criteria:
   - **No Discount**: Total ≤ ₹500  
   - **2% Discount**: ₹500 < Total ≤ ₹2000  
   - **5% Discount**: ₹2000 < Total ≤ ₹5000  
   - **7% Discount**: ₹5000 < Total ≤ ₹10000  
   - **10% Discount**: Total > ₹10000  
5. An itemized bill is generated and displayed for the customer.
6. The program continues for the next customer until no more customers are left.

---

## Products List:
The available products and their prices are as follows:
- **Cashew**: ₹460 per kg
- **Rice**: ₹580 per kg
- **Atta**: ₹400 per kg
- **Oil**: ₹160 per liter
- **Maida**: ₹40 per kg

---

## How to Run:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Mohammad-Suhail-Alam/SuperMarket_Billing_system.git
