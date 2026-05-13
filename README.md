# Website: online orders for small business

## Project Overview

**Houseforms** is a website developed for a local blogger who creates handcrafted miniature architectural models (house models) for collectors. The site serves as both a portfolio and a simple showcase for the models.

The website is fully functional, dynamic, and includes an admin panel for easy content management.

---

## Team & Roles

The project was carried out by a team of three people:

| Role | Responsibility |
|------|----------------|
| **Database Manager** | Database structure, storing model data (name, description, price, area, category, photos), integration with the website |
| **Client Communication Manager** | Main point of contact with the blogger: gathering requirements, presenting progress, collecting feedback |
| **Frontend Developer** | User interface, filtering, photo galleries, admin panel interface |

---

## Technology & Hosting

- **SpaceWeb** – cloud service management platform used to deploy and host the website  
- **Custom domain** – purchased for a professional identity  
- **Dynamic website** – model data is stored in a database and displayed on the frontend

---

## Features

### 1. Main Page (Public Area)

- Displays all available house models (e.g., "Classical Estate 'Renaissance'" – 420 m², 34,500 ₽)
- **Photo gallery** – users can scroll through multiple photos of each model
- **Filtering options**:
  - By category (Modern, Classic, Eco‑design)
  - By price range (in RUB)
- Models are shown with area and price

### 2. Order Placement (Blogger's Request)

- When a user attempts to place an order, a **pop‑up notification** appears with the blogger's contact details:
  - Telegram
  - Work phone number
- This allows the blogger to communicate with customers directly, without needing a complex shopping cart or online payment system

### 3. Admin Panel

- Secure login page (demo access: `admin` / `admin123`)
- After login, the admin can **add new models** with:
  - Name, description, price, area, category
  - Multiple photos (upload supported)
- Initially, sample models are pre‑loaded from the database
- A table lists existing models with options to **edit** or **delete** (icon buttons)

---

## Current Status

Main page with dynamic model listing and filtering  
Pop‑up notification with blogger's contacts when placing an order  
Admin panel with full model management  
Initial models populated from the database  
All features work (filtering, adding models, photo uploads)

---

## Purpose

The site allows the blogger to easily showcase and manage their collection of miniature house models, while giving visitors a clean, filterable gallery. The contact notification simplifies direct communication with the blogger for orders – helping the blogger grow their audience and streamline model presentation.

---

## Tech Stack (Summary)

- Hosting: SpaceWeb  
- Domain: Custom  
- Backend / DB: Dynamic database‑driven architecture  
- Frontend: HTML/CSS/PHP with responsive design  
- Admin Panel: Secure login 

---

## License

This project was developed for educational / portfolio purposes as part of a team project.

---
