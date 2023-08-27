# Food-Order-Cancellation-Visualization-

-----------------------------INTRODUCTION---------------------------------
The project revolves around a food ordering platform featuring a nuanced cancellation policy spanning various food item categories. 

This encompasses packaged items, buffet items, and non-MRP items. Users are empowered to cancel packaged and buffet items, but for non-MRP items, cancellation is permissible only before the restaurant accepts the order. 

Additionally, restaurants can cancel orders until they are prepared, with reasons for cancellation collected for analysis. 

The endeavor leverages two tables: "Cancelled Orders" and "Product Details," delving into cancellations' patterns and insights to enhance the platform's operational efficiency and user experience.


-----------------------------Procedding and Findings------------------------------------

-> We begin with combining our tables and then going to further steps

=>Step 1: Data Preparation, Exploration, and Metric Calculation 
                     In the pursuit of extracting valuable insights and recommendations, a meticulous process is employed, beginning with data preparation, exploration, and                      calculation of key performance metrics (KPIs). By consolidating "Cancelled Orders" and "Product Details" tables through a shared "Order ID," a holistic                      dataset for analysis is curated.



->Exploratory Data Analysis (EDA): Unearthing Patterns and Patterns

      > Cancellation Modes Analysis:

                   - Examination of "Cancellation Mode" uncovers distinct patterns:
                    -78% of cancellations are customer-initiated through the app.
                    -22% are restaurant-initiated cancellations.

                                --Notable reasons for restaurant cancellations include "Stock Shortage," "Item Unavailable," and "Customer Refusal."--



             
                   ->Focused Observation: Seven restaurants contribute to nearly 50% of cancellations.
                                          A subset of five restaurants (IDs 1135, 1084, 1002, 1282, 1129) accounts for half of restaurant-initiated cancellations.
                                        
                                        --Priority Areas: Mitigating cancellations in cases of "Stock Shortage" and "Item Unavailable."--
  

        > Product Type Analysis: Segmentation reveals cancellation prevalence:
                                Cancellations concentrated in the Buffet Food category, leading to food wastage.
                                Non-MRP items cancellable until restaurant acceptance.


          
          
        > Quantity Wise Analysis: Quantitative analysis demonstrates:
                                  Orders with larger quantities exhibit reduced cancellation likelihood.
                                  --Suggestion: Implement "Buy More, Save More" promotions to minimize cancellations.--
            


        > Revenue Based Analysis:Total revenue loss over five days: Rs 5,81,000.
                                  Highlighted Restaurants: Cancellations at key restaurants contribute significantly to losses.
                                      --Recommendations: Optimizing Policy and Practices--
            



        > Cancellation Policy Reform: Revise the cancellation policy, addressing buffet cancellations that lead to food waste.
                                    Restructure cancellation criteria for non-MRP items based on restaurant acceptance stage.


        > Restaurant Engagement: Engage with restaurants identified as major cancellation contributors (IDs 1135, 1084, 1002, 1282, 1129).
                                Collaborate on addressing "Stock Shortage" and "Item Unavailable" issues.


        > Product Optimization: Introduce strategic offers to encourage larger order quantities.
                                Focus on promoting products with lower cancellation rates.
                              


        > Revenue Protection Strategy:Initiate revenue protection strategies to minimize Rs. 5,80,140 losses over five days.
                                      Prioritize actions targeting significant cancellation-prone restaurants.
