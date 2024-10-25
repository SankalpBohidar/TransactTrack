# TransactTrack

## Objective:

The main objective is to design and implement an Online Payment
System that supports an E-Commerce platform that allows
customers to purchase products and services through a secure and
user-friendly platform. The system will include a database
management system to store and manage information related to
users, products, orders, shipments, and reviews.


## Description:

The first step in using an Online Payment System is User Registration. When a
user registers with the system, they provide personal information, such as their
FullName, Email Address, PhoneNumber, Username, Password, Age and is
associated with a unique User ID.

Whenever a user initiates a transaction, such as making a payment for an
order, the user’s UserID is also associated with an unique Transaction ID, and
features like Transaction Date and Time, Transaction Amount are also noted.
Each Transaction ID is associated with an Order ID , as the products ordered by
the user may be from multiple sellers therefore having different Order IDs, and
features like Order Status(Confirmed, Preparing, Shipped, Out for Delivery,
Returned), Shipping ID , Fee ID, Coupon ID, TotalAmount are noted.

Furthermore, to know the payment method opted by the user, each
Transaction ID is also associated with a PaymentMethod (Credit, Debit, UPI,
E-Wallet) and Transaction Status (Completed, Failed , Declined).

Additionally, every Order’s Shipping ID is associated with the User’s Shipping
Address which include attributes like Country, State, City, Pin Code, Delivery
Area and Shipping Date. Further every Order’s Fee ID is associated with a
complete breakdown of the Order, which can include details like Order Total,
GST, Delivery Fee, Shipping Fee. And the Coupon ID is associated with details of
the coupon applied to the order such as Coupon Code, Discount Type,
Discounted Amount.

To know more about the Order Details , such as all the product details, we try
to associate OrderID with Product ID, Quantity, Total Price respectively. In
addition to that if the user wants to know the details such as but not limited
to the availability of a particular product , we try to associate Product ID with
Product Description which includes details like Product Name,
Stock/Availability, Product Type/Category, Average Purchase Price, Product
Rate.

Online payment systems require robust database management systems to
handle the large volumes of data so there should be an authority who should
administer all these transactions, so we have Admins who have their own
Admin ID, Admin Username assigned to monitor multiple Transaction ID and
the Order IDs associated with it.

Another important aspect of this system are the reviews of the product by the
users, thereby each review i.e, Review ID is associated with the Order ID and
the respective Product ID which also has attributes such but not limited to
Rating (on a scale of 1-5) and Feedback. Further we also try to include a Refund
Process into this system which has features like Refund ID, Refund Amount,
Refund Date, Reason of Refund associated with the Transaction ID.

## Entity-Relationship (ER) Diagram

![Entity_Relationship_Diagram(ERD)](https://github.com/Harsh62004/Online-Payment-System/assets/94214306/50664b1d-b07a-42ea-b51c-9cee3c8abc50)

## Relational Schema
![Relational_Schema](https://github.com/Harsh62004/Online-Payment-System/assets/94214306/7031c376-6127-4918-8570-87b62cd90493)

 

