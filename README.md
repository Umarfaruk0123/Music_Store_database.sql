# 🎵 Music Store SQL Analysis Project

A complete SQL analysis project on a Music Store database. The project covers beginner to advanced SQL queries including JOINs, CTEs, Window Functions, Subqueries, and Aggregations.

---

## 📁 Project Structure

```
Music-Store-SQL-Project/
│
├── Music_Store_database.sql   # Original database schema & data
├── SQL_Queries.sql            # All solved queries (Easy → Moderate → Advanced)
└── README.md                  # Project documentation
```

---

## 🗄️ Database Schema

The Music Store database contains the following key tables:

- `employee` — Store staff and their job levels
- `customer` — Customer information
- `invoice` — Purchase records per customer
- `invoice_line` — Individual items per invoice
- `track` — Song/track details including duration
- `album` — Album information
- `artist` — Artist details
- `genre` — Music genres

---

## 📊 Questions Solved

### 🟢 Question Set 1 — Easy

| # | Question |
|---|----------|
| Q1 | Who is the senior most employee based on job title? |
| Q2 | Which countries have the most Invoices? |
| Q3 | What are the top 3 values of total invoice? |
| Q4 | Which city has the best customers (highest invoice total)? |
| Q5 | Who is the best customer (most money spent)? |

---

### 🟡 Question Set 2 — Moderate

| # | Question |
|---|----------|
| Q1 | Return email, first name, last name & Genre of all Rock Music listeners (ordered by email) |
| Q2 | Top 10 rock bands by track count |
| Q3 | Tracks with song length longer than the average |

---

### 🔴 Question Set 3 — Advanced

| # | Question |
|---|----------|
| Q1 | How much amount spent by each customer on artists? |
| Q2 | Most popular music Genre for each country |
| Q3 | Customer who spent the most on music for each country |

---

## 🛠️ Tools & Technologies

- **Database:** PostgreSQL
- **Concepts Used:** JOINs, GROUP BY, ORDER BY, LIMIT, Subqueries, CTEs (`WITH`), Window Functions (`ROW_NUMBER`, `PARTITION BY`), Aggregate Functions

---

## 🚀 How to Run

1. Import `Music_Store_database.sql` into your PostgreSQL client (e.g., pgAdmin)
2. Open `SQL_Queries.sql`
3. Run each query individually to see results

---

## 👤 Author

> Feel free to connect on [LinkedIn](https://www.linkedin.com/in/umarfaruk-shaikh/) | [GitHub](https://github.com/Umarfaruk0123)

---

⭐ If you found this project helpful, give it a star!
