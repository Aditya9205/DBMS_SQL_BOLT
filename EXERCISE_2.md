# Exercise-2

---

## 1. Find the movie with a row id of 6
```sql
SELECT * FROM film
WHERE id = 6;
```

---

## 2. Find the movies released in the years between 2000 and 2010
```sql
SELECT * FROM film
WHERE year BETWEEN 2000 AND 2010;
```

---

## 3. Find the movies not released in the years between 2000 and 2010
```sql
SELECT * FROM film
WHERE year NOT BETWEEN 2000 AND 2010;
```

---

## 4. Find the first 5 Pixar movies and their release year
```sql
SELECT title, year FROM movies
WHERE year <= 2003;
```

---