# Exploring the Sakila Database: A Journey Through Data

## Project Purpose
The purpose of this project is to explore the Sakila database, answer common business questions, and extract actionable insights. This demonstrates my ability to work with SQL queries, aggregate data, and provide business-relevant analysis. My goal wasn’t just to run queries, but to understand the story behind the numbers. Here’s what I discovered along the way.

## What I Set Out to Learn

Stepping into the Sakila database felt like exploring a small movie rental universe, customers, films, actors, payments, stores… so much happening all at once.  

I wanted to answer questions like:

- Which customers are truly active, and who could use a nudge?  
- Which films are hits, and which sit on the shelves unnoticed?  
- How does revenue and performance vary across stores and categories?  
- And importantly, how can I use SQL, especially **window functions** to uncover trends I might otherwise miss?

---

## Lessons from Window Functions

Working with window functions completely changed how I think about SQL.  

- **Window functions don’t collapse rows.** They let you see trends while keeping all the original data visible, that's a huge shift in mindset.  
- **ROW_NUMBER, RANK, and DENSE_RANK** behave differently, testing them on real data made the distinctions crystal clear.  
- **LAG** is a lifesaver. Accessing the previous row without joins or subqueries felt almost magical.  
- **CTEs simplify everything.** Breaking queries into stages makes complex logic easier to read and debug.  
- **Running totals teach precision.** ORDER BY inside the window frame controls progression, once understood, cumulative calculations became intuitive.  
- Multi-window analyses, joining tables, ranking, aggregating, and filtering,  **showed how window functions fit into real workflows**, not just theory.  

By the end, I realized that window functions aren’t just SQL features; they’re tools for **telling the story hidden in the data**.

---

## Practical Tips I Picked Up

- Start with **questions, not queries**. Know what you want to learn before writing SQL.  
- Break complex logic into **CTEs** instead of one long query.  
- Test similar functions side-by-side. ROW_NUMBER vs. RANK vs. DENSE_RANK clicks when you see them in action.  
- Use **LAG and LEAD** for previous or next row logic, it avoids messy joins.  
- Pay attention to **window frames**. ORDER BY and PARTITION BY can completely change your results.  
- Export or visualize results to spot patterns. Numbers are one thing; charts make trends obvious.  
- Document assumptions and double-check each step. It saves headaches later.  

---

## Key Takeaways

1. **Data tells stories.** Look beyond aggregates to see what’s really happening.  
2. **Window functions unlock insights.** They reveal trends, rankings, and previous values without collapsing data.  
3. **Break it down.** Stepwise queries, CTEs, and logical ordering make analysis manageable.  
4. **Insights lead to action.** Knowing your high-value customers, best-performing films, and seasonal patterns lets you make smarter decisions.  

---

## Technologies Used

- **SQL (MySQL)** – querying, aggregation, and window functions  
- **Sakila Database** – sample dataset for films, customers, rentals, and staff  

---

This README tells the story of my **journey through Sakila**, from raw data to actionable insights. It’s not just about queries, it’s about **learning to think with data**.
