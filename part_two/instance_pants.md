**instance:**
jeans

**attributes**
* color = ["blue", "black", "gray"]
* size = [0, 2, 4, 6, 8, 10]
* number_in_stock (size: number) = { 0: 5, 2: 3, 4: 7, 6: 10, 8: 5, 10: 2 }
* total_stock (total up all pants in hash number_in_stock = 32)
* price = 30.99

**methods**
* sale_price (change price from 30.99 to 20.99 when total_stock is <= 5 pants)
* check_stock (use number_in_stock and print how many of that kind of pants are in stock: "You have 32 jeans")
* order_more (add 1 more pant of a certain size - changes hash)
* add_color (modify color array: add "white" pants to options available)
