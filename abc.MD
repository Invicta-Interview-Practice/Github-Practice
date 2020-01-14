use online_shopping_system_fashion_house;
/*SELECT product.name, COUNT(order_details.order_id) AS NumberOfOrders
FROM product
INNER JOIN order_details ON order_details.product_id = product.product_id
WHERE product.name = 'White Sleeveless Frock'
GROUP BY product.name
HAVING COUNT(order_details.order_id) > 5;*/

/*SELECT order_details.order_id, COUNT(order_details.order_id) AS NumberOfOrders
FROM order_details
GROUP BY order_details.order_id
HAVING COUNT(order_details.order_id);*/

/*SELECT COUNT(order_details.order_id), order_details.order_id
FROM order_details
GROUP BY order_details.order_id
HAVING COUNT(order_details.order_id) > 0
ORDER BY COUNT(order_details.order_id) DESC;*/


