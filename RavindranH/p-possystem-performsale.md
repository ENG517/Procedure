
# Performing Sales in a POS System

## System Requirements

The POS workstation must have the following requirements:

- Supported OS: Windows 10 or later 
- Minimum 8GB RAM, 256 GB SSD, and dual core-processor
- Barcocde scanner, receipt printer, cash drawer compliant with OPOS standards. 
- Active internet connection for cloud-based POS setup.
- Database access with appropriate user role permissions. 

---
## Prerequisites
- User account created with *Cashier* role and login credentials  
- POS application installed and running  
- Items added to product catalog with barcodes configured  
- Payment methods (cash, card, digital wallet) enabled in the POS system  
- Cash drawer initialized with starting cash amount (if applicable)  

---
## Device Requirements
- **Barcode Scanner**: USB or Bluetooth-enabled, capable of reading 1D/2D codes  
- **Receipt Printer**: Thermal or impact printer with OPOS drivers (e.g., Epson, Star Micronics)  
- **Cash Drawer**: Electrically connected to the receipt printer for automatic opening  
- **Payment Terminal/Pin Pad**: EMV-compliant, NFC-enabled for contactless payments (Apple Pay, Google Pay)  
- **Customer Display (Optional)**: OPOS-supported pole display for showing item details and totals  
- **POS Terminal/Workstation**: Touchscreen or keyboard-operated system meeting minimum system specs  

# Step-by-Step Sales Procedure

1. **Login to POS**  
   - Launch the POS appplication by clicking the POS application shortcut in the Desktop. 
   - Enter the valid credentials.  
   - Select *Cashier* role from the **User Profiles** drop-down. 

2. **Scan Item(s)**  
   - Use the barcode scanner to scan the product barcodes or select the item from the **Order** screen. 
   - Verify that each item appears in the cart with correct name, price, and quantity.  
   - If barcode is unreadable, use *Search by Item Code/Name* feature.  

3. **Review Cart**  
   - Confirm items, quantities, and subtotal.  
   - Apply discounts, promo codes, or loyalty points (if applicable).  

4. **Select Payment Method**  
   - Tap **Checkout** → Choose payment type (cash, card, digital wallet, split payment).  
   - For **cash payments**: Enter the amount tendered.   
   - For **card payments**: swipe/insert/tap the card on connected payment terminal.  
   - For **digital wallet**: Scan QR or confirm payment through linked gateway.  

5. **Complete Transaction**  
   - Confirm payment success on POS screen.   

6. **Print or Send Receipt**  
   - Print physical receipt. 
   - Optionally, send e-receipt via email or SMS if customer details exist.  

7. **End-of-Sale Confirmation**  
   - POS displays transaction summary with transaction ID.  
   - Return change (if cash) and thank the customer.  

   ---

## Notes
- Always verify product prices against displayed catalog to prevent billing errors.  
- If network drops during transaction, POS queues the offline and syncs them when reconnected.  

---

## References – OPOS Documentation 

Here are key resources:  
- [OPOS Common Control Objects Download](https://www.microsoft.com/en-us/download/details.aspx?id=42095)  
- [UnifiedPOS (UPOS) Specification – CCO](https://www.omg.org/upos/)  
- [OPOS Developer Resources](https://www.posforsystem.com/opos/)  