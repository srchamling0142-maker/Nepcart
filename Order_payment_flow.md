# NepCart Order, Payment & Commission Flow

## Customer Order
Customer selects a product and places an order.

## Payment Methods
- Cash on Delivery (COD)
- eSewa
- Khalti
- Bank Payment

## Example

Product Price: Rs. 1,000
Delivery Fee: Rs. 100
Customer Total: Rs. 1,100

## Commission

If NepCart commission is 10%:

Product Price: Rs. 1,000
NepCart Commission: Rs. 100
Seller Amount: Rs. 900

## Delivery Flow

Customer
→ NepCart
→ Seller
→ Delivery Partner
→ Customer

## COD Flow

Customer places COD order
→ Seller prepares product
→ Delivery Partner picks up product
→ Delivery Partner delivers product
→ Customer pays cash
→ COD collection is recorded
→ Settlement is made to seller

## Order Status

Pending
→ Confirmed
→ Processing
→ Shipped
→ Out for Delivery
→ Delivered

Other statuses:
- Cancelled
- Returned
- Refunded

## Seller Settlement

Seller settlement is calculated after successful delivery and according to NepCart commission rules.

## Refund

If an order is returned or cancelled, the system calculates the refund and adjusts the seller settlement and commission accordingly.
