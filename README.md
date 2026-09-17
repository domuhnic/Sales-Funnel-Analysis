# Sales-Funnel-Analysis

### Background/Scenario
Management requests that we analyze our sales funnel using SQL to calculate conversion rates, time spent in stages, and other important metrics. Based on our findings, we should give recommendations on how we could potentially increase profits.

<img width="937" height="517" alt="image" src="https://github.com/user-attachments/assets/0cd83ada-0208-458f-871c-c90fd5a8ccc4" />

<img width="933" height="523" alt="image" src="https://github.com/user-attachments/assets/c5981946-cc7f-4114-81a8-3bb3723f15b9" />


### Conversion Rates
<img width="1222" height="550" alt="image" src="https://github.com/user-attachments/assets/31219cee-3ffa-4d5c-850c-d50e334a27df" />
<img width="1217" height="555" alt="image" src="https://github.com/user-attachments/assets/3f2c9c75-4df3-44e0-9fca-7884bc7f0740" />

<img width="926" height="567" alt="image" src="https://github.com/user-attachments/assets/60c66f62-c434-4a23-af4b-456c011fad34" />


We first use a CTE to query the count of all stages, then divide each count by the previous stage to get the conversion rate. Based on our findings, we can see that we are having a hard time getting customers to add products to their carts, which is normal since many users tend to browse around. We can see that once products are added to the cart, conversion rates increase significantly. The checkout to payment rate is 81%, and the chances of a user going from payment to purchase are 91%, which is extremely high. ***It seems that our website allows for users to make easy purchases, so I would not recommend making any changes.***

### Traffic Sources
<img width="710" height="99" alt="image" src="https://github.com/user-attachments/assets/600d627d-cd5a-45c0-891e-031633c07d9b" />
<img width="1216" height="551" alt="image" src="https://github.com/user-attachments/assets/412c1383-81a7-40f0-9c96-590ee4a394ef" />


Although emails have the least amount of views, the cart and purchase rates are the highest among the four sources, and it has the second highest cart to purchase rate among the four sources. ***Our marketing budget should be used to invest in capturing more users from emails.*** Social media is a very weak source, with the lowest rates besides the cart to purchase conversion rate (tied with organic). Although it gains many views, ***it is not worth investing into social media ads. We can instead use the money we spend on ads for emails.***

### Totals & Averages
<img width="552" height="50" alt="image" src="https://github.com/user-attachments/assets/75029354-d4b3-4f33-ac0d-93dcbdfdcac8" />

The main thing that I would like to focus on is the average order value. We must ensure that we are spending under this amount to be able to make a profit. ***If we are spending more on marketing to gain one customer than they spend on our products, we would be losing a significant amount of money. This ties back to our marketing budget. We must determine if keeping social media as a form of marketing is truly worth it.***

### My recommendations
- The website should remain the same, or changes should be minimal. Overall conversion rates are strong.
- Reconsider our marketing budget. Spend more on emails and less on social media.
- Consider removing social media as a whole from our marketing strategy.


