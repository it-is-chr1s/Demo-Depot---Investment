# Demo Depot - Investment

Overview of All Services and Functionalities

## Learning Objectives

- Gain hands-on experience with scalable backend technologies such as Redis, GraphQL, and caching.

## Project Overview

Stock Prices:

- Fetch real-time stock prices via public APIs.
- Implement caching for performance while allowing access to the current price for orders.
- Provide Buy/Sell functionaliy for user orders.

User Profiles:

- Manage user depots with authentication (username & password)
- Configure transaction fees per user:
  ~ Basic fee
  ~ Percentage-based fee
  ~ Fee cap
  ~ Custody account management fee

Order Management:

- Store Orders per User:
  ~ Creation date
  ~ Trigger date
  ~ Stock reference
  ~ Amount
  ~ Trigger type (buy-limit, sell-limit, stop-loss-sell, start-buy)
- List and manage active orders.

Depot:

- Display a user's portfolio of stocks.

Project Approach:

- Architecture plans for all services will be collected for future implementation
- Start with Stock Prices service using mocked data to focus on GraphQL and Netflix DGS implementations.
- Gradually expand to other services, applying GraphQL and Netflix DGS.
