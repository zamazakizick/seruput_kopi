![image](https://user-images.githubusercontent.com/25179703/145503745-540eb284-b25e-4fab-973d-c0ef50e92adc.png)

How to run :
- make sure .env config is same like your new database.
- composer install.
- php artisan migrate.
- php artisan command:checkout {product}
- example : php artisan command:checkout CL1 CL1 FR1 CL1

Here is the list of the products and it prices, depends on the location
![image](https://user-images.githubusercontent.com/25179703/145393933-f29be21a-5c9b-443b-b3c3-63fd1350db28.png)

Feature :
1. Free 1 coffee latte when buying 1 coffee latte (the free event is once, per transaction only)
2. Discount 20% continuely if the transaction contain more than 3 of the same products.

Upcoming feature :
1. Employees can buy the drinks with 15% discount per day (once per transaction, in a day);
2. Handling confirmation and order log system.
