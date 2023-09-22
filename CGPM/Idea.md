# Main Idea
- Buyer
    + Info - Item
    + Dat Hang
    + Tra Hang
    + Add item to cart
    + List of item in Cart
    + Search
    + Account (login - signup / logout)
    + Profile
    + State of the package
    + After buy Info
- Seller
    + 
- Boss
    + Report




Xuat bao cao:

# Main Function
# FRONT END
- Buyer
    + Info - Item (color and size should be hidden and show when hover)
        * Size
        * color
        * quantity
        * price
        * Discription
        * Thong Tin Chi Tiet
    + Dat Hang (BUtton on item (lable: mua ngay) / button in List of Item in cart )
    + Tra Hang (WIP)
    + Add item to cart (button, label: Them Vao Gio hang)
    + List of item in Cart
        * Size
        * color
        * quantity
        * price (update with the current value in db)
        * Pick one to buy item (checkbox)
    + Trang Thanh Toan
        * Address
        * Shipping method (str + int (fee of different method))
        * Detail of purchase
            * Total price of item
            * Shipping fee
            * Total pay
    + Search
    + Account (login - signup / logout)
    + User Page
        * Profile
            ~ Name
            ~ Gender
            ~ DoB
            ~ Phone numb
            ~ Email
        * After buy info (WIP)
            ~ Item + price + quantity
            ~ Delivery info
            ~ Total pay
            ~ State of the package
        * Re-buy
- Seller 
    + Nhap san pham 
    + Kiem tra san pham (quatity/ what color/ what size)
    + Report 
        * Revenue
        * Visualization (SQL or Python)
# BACKEND
- Compare on-site quantity and db quantity ( can't be exceed)
# DB
- Infoitem
    * Item Id (primary key)
    * Name
    * Size
    * color
    * Stock quantity (update by HD)
    * price
    * Discription
    * Thong Tin Chi Tiet
- List of item in Cart 
    + User ID (primary key)
    + Item Id (KP)
- User Profile
    + User ID (Primary Key)
    + Name
    + Gender
    + DoB
    + Phone numb
    + Email
- Account
    + User ID (PK)
    + password
- HD
    + User ID (PK)
    + HD ID (PK)
    + Total
- CTHD
    + HD ID (PK)
    + Item ID
    + quantity
    + price
