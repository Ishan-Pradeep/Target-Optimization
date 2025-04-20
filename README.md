# Target-Optimization
Distribute sales targets across product groups to meet a given revenue or sales budget while maximizing overall profit.
Sales Target Optimization for Trade Companies

In the trade sector, companies often plan their sales over extended timeframes and set strategic targets aligned with overall business goals. These targets are typically distributed across multiple product groups, each with varying profit margins. As a result, evenly splitting targets may not yield optimal profitability.

This project aims to optimize the distribution of sales targets to maximize overall profit while meeting a predefined budget. It accounts for several real-world constraints such as current demand, stock in hand, stock at the customer, and desired stock balances at both ends. The goal is to strike the best balance between profit achievement and target fulfillment.

The optimization is performed using differential optimization techniques in scipy.optimize, which allow for precise handling of complex constraints and nonlinear relationships. By evaluating the contribution of each product group based on profit margins and stock availability, the model allocates targets where they deliver the highest return.

This solution supports strategic planning by identifying the most profitable and feasible mix of product group targets, ensuring efficient use of inventory, alignment with sales goals, and maximized profitability.
