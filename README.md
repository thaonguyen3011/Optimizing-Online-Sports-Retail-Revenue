# Optimizing Online Sports Retail Revenue
# Purpose: 
To analyze product data of big brand for an online sports retail company to maximize revenue.

# Analyze and make suggestion: 
1. Count data non-missing values
The database contains 3,179 products in total. 
- Only one — last_visited — is missing more than five percent of its values
2. Nike vs Adidas pricing
- For Adidas, listing_price is in 9$-300$ range
- For Nike, listing_price is in 30$-200$ range
3. Labeling price ranges
Grouping products by brand and price range
- Adidas items generate more total revenue regardless of price category
- "Expensise" Adidas products priced from $74-$129 typically generate the highest revenue,
=> To increase revenue by shifting their stock to have a larger proportion of these products!
4. Average discount by brand
- No discount is offered on Nike products.
- In comparison, not only do Adidas products generate the most revenue, but these products are also heavily discounted
=> To reduce the amount of discount offered on Adidas products
and monitor sales volume to see if it remains stable in order to improve revenue further
=> To offering a small discount on Nike products. This would reduce average revenue for these products, 
but may increase revenue overall if there is an increase in the volume of Nike products sold
5. Correlation between revenue and reviews
- There is a strong positive correlation between revenue and reviews. 
=> Potentially, if we can get more reviews on the company's website, 
it may increase sales of those items with a larger number of reviews.
=> To run experiments with different sales processes encouraging more reviews from customers about their purchases, 
such as by offering a small discount on future purchases
6. Ratings and reviews by product description length
- There doesn't appear to be a clear pattern between the length of a product's description and its rating
7. Reviews by month and brand
- Product reviews are highest in the first quarter of the calendar year
=> There is scope to run experiments aiming to increase the volume of reviews in the other nine months
8. Footwear product performance
- In 3,117 products, 2,700 are footwear products, which accounts for around 85% of the company's stock. 
- They also generate a median revenue of over $3000 dollars.
17. Clothing product performance
- The remaining one is clothing products with 417 items that generate a median revenue of over $500 dollars
