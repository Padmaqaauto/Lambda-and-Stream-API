
# 🚀 Java Functional Programming & Stream API

## 📌 Overview
Practice Java Functional Programming and Stream API using a `Person` class and sample data. Explore functional interfaces, lambda expressions, method references, filtering, mapping and sorting collections.

## 🛠️ Concepts Covered

### 1. Functional Programming
- ✅ `Predicate<Person>` – Define and test conditions.
- ✅ `Consumer<Person>` – Perform actions such as printing names and sending emails.
- ✅ `Function<T, R>` – Transform data from one type to another.
- ✅ Lambda Expressions and Method References.
- ✅ Rule Composition using `and()`, `or()` and `negate()`.

### 2. Stream API
| Operation | Purpose |
|---|---|
| `filter()` | Select people matching conditions |
| `map()` | Transform person objects into names, emails and details |
| `count()` | Count matching people |
| `sorted()` | Sort people by age |
| `distinct()` | Remove duplicate cities and first letters |
| `findFirst()` | Find the first matching person |
| `toList()` | Collect stream results into a list |
| `forEach()` | Perform an action on each element |

## 💻 Practical Exercises

- 🔹 Filter active people, adults and Stockholm residents.
- 🔹 Combine multiple conditions using AND, OR and NOT.
- 🔹 Print names and generate email addresses.
- 🔹 Find the first active person living in Stockholm.
- 🔹 Sort people by age using `Comparator`.
- 🔹 Find unique and sorted cities.
- 🔹 Extract unique first letters of names.
- 🔹 Format person details as `Name (age) - city`.

## 🧠 Reflection

### 1. Which solutions were easier to read: loop-based or stream-based?

Stream-based solutions were easier to read because they express what I want to achieve without writing explicit loops or creating temporary result lists. Operations like `filter()`, `map()` and `sorted()` make the processing logic clearer and more concise.

### 2. Which operations felt like transformations and which felt like side effects?

- **Transformations:** `filter()`, `map()`, `sorted()` and `distinct()` process data and produce stream results without modifying the original list.
- **Terminal operations:** `toList()`, `count()` and `findFirst()` produce final results.
- **Side effects:** `forEach()` performs actions such as printing names and displaying email messages.

### 3. Where did Predicate, Function and Consumer fit naturally?

- **Predicate:** Used with `filter()` to check conditions such as active status, adult age and city.
- **Function:** Used with `map()` to transform a `Person` object into a name, email address or formatted person detail.
- **Consumer:** Used with `forEach()` to perform actions such as printing names and email messages.

## 🎯 Key Learning Outcomes

- Understand the difference between loop-based and stream-based processing.
- Use Java's built-in functional interfaces.
- Combine conditions using Predicate composition.
- Transform and filter collections using Stream API.
- Apply Comparator for sorting.
- Distinguish between data transformations and side effects.

---

**📚 Main takeaway:** Functional interfaces and Stream API help write reusable, readable and maintainable Java code.
