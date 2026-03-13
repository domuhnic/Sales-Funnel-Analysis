# Sales-Funnel-Analysis

### Background
Management requests that we analyze our sales funnel using SQL to calculate conversion rates, time spent in stages, and other important metrics. Based on our findings, we should give recommendations on how we could potentially increase profits.

### Conversion Rates
<img width="1029" height="48" alt="image" src="https://github.com/user-attachments/assets/9515591e-46fe-442c-bb71-bd39c6d7df67" />

We first use a CTE to query the count of all stages, then divide each count by the previous stage to get the conversion rate. Based on our findings, we can see that we are having a hard time getting customers to add products to their carts, which is normal since many users tend to browse around. We can see that once products are added to the cart, conversion rates increase significantly. The checkout to payment rate is 81%, and the chances of a user going from payment to purchase are 91%, which is extremely high. ***It seems that our website allows for users to make easy purchases, so I would not recommend making any changes.***

### Traffic Sources
<img width="710" height="99" alt="image" src="https://github.com/user-attachments/assets/600d627d-cd5a-45c0-891e-031633c07d9b" />

Although emails have the least amount of views, the cart and purchase rates are the highest among the four sources, and it has the second highest cart to purchase rate among the four sources. ***Our marketing budget should be used to invest in capturing more users from emails.*** Social media is a very weak source, with the lowest rates besides the cart to purchase conversion rate (tied with organic). Although it gains many views, ***it is not worth investing into social media ads. We can instead use the money we spend on ads for emails.***

### Totals & Averages
<img width="552" height="50" alt="image" src="https://github.com/user-attachments/assets/75029354-d4b3-4f33-ac0d-93dcbdfdcac8" />

The main thing that I would like to focus on is the average order value. We must ensure that we are spending under this amount to be able to make a profit. ***If we are spending more on marketing to gain one customer than they spend on our products, we would be losing a significant amount of money. This ties back to our marketing budget. We must determine if keeping social media as a form of marketing is truly worth it.***

### My recommendations
- The website should remain the same, or changes should be minimal. Overall conversion rates are strong.
- Reconsider our marketing budget. Spend more on emails and less on social media.
- Consider removing social media as a whole from our marketing strategy.


