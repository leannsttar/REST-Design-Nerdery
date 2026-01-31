# E-Commerce API 1.0.0

![Status](https://img.shields.io/badge/status-active-success.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg)

A production-ready, RESTful E-commerce API built with **OAS 3.1** standards. Features a normalized database for complex inventory, secure JWT authentication, and Stripe payment integration.

## ⚡ Key Features

* **Inventory:** Normalized variant system (Shopify-style) for complex attribute combinations (e.g., SKU for "Red/Large").
* **Security:** Stateless JWT authentication with HTTP-only Refresh Tokens.
* **Transactions:** Server-side cart calculations and strict order price snapshots.
* **Payments:** Full Stripe Payment Intent & Webhook integration.
* **Architecture:** Modular design separating **Client** and **Manager** roles.

## 🏗 Modules
1.  **Auth:** Sign-up, Sign-in, Token Rotation, Password Reset.
2.  **User:** Profile management and Address Book.
3.  **Catalog:** Products, Categories, Variants, and Images.
4.  **Shopping:** Singleton Cart and Favorites.
5.  **Orders:** Checkout lifecycle and Payment processing.

## 🗄️ Database

Uses a **Normalized Variant Strategy**

> **[🔗 View Interactive ERD](https://dbdiagram.io/d/T-shirts-w-variants-69726682bd82f5fce252613b)**

<img width="2316" height="1798" alt="image" src="https://github.com/user-attachments/assets/54cca5ff-3d88-48d6-b81b-b7ec6ef29e73" />
