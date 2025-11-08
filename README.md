# S2.04MongoDB-Queries 🌵🌵 

## 🧾 Task Objectives
 - Learn how to **query, filter, and organize** data using `MongoDB`.
 - Understand how to interact with large collections and nested structures in a NoSQL environment.
 - Practice **data exploration and manipulation** with a real dataset (restaurants.json).
 - Reinforce skills in **projection, filtering, sorting, and conditional operators**.
 - This activity focuses on mastering **MongoDB’s query language** and improving your ability to analyze and extract meaningful insights from complex data collections.

---

## 💻 Suggested Technologies

 - MongoDB (v6.0 or higher)
 - MongoDB Compass
 - Visual Studio Code/ IntelliJ IDEA
 - Git & GitHub

---

## 📋 Requirements

 - `MongoDB` version 6.0 or higher installed locally.
 - Access to the dataset located in the folder:
    ```bash
    /resources/restaurants.json
   ```
 - Basic knowledge of `MongoDB` syntax and operators (`find`, `projection`, `sort`, etc.).
 - **MongoDB Compass** or terminal access for executing queries.

---

## 🛠️ Installation

 1. Clone the repository:
    ```bash
    git clone https://github.com/andyrouge81/S2.04MongoDB-Queries.git
    ```
    
 2. Navigate to the project folder:
    ```bash
    cd S2.04MongoDB-Queries
    ```
 3. Import the dataset into MongoDB:
    ```bash
    mongoimport --db ny_restaurants --collection restaurants --file resources/restaurants.json --jsonArray
    ```
 4. Verify that the collection was created:
    ```bash
    show dbs
    use ny_restaurants
    show collections
    ```
    
---

## ▶️ Execution
 - Open **MongoDB Compass** or your preferred client.
 - Connect to the local instance and select the `restaurants` database.
 - Explore the `restaurants` collection and practice running queries using filters, projections, and sorting operations.
 - The goal is to **understand how MongoDB queries work** and how to manipulate JSON-like documents effectively.

---

## 🤝 Contributions

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/NewFeature
   ```
3. Commit your changes:
    ```bash
    git commit -m "feat: improve MongoDB import instructions"
   ```
   
4. Push the branch:
    ```bash
    git push origin feature/NewFeature
    ```
   
5. Open a Pull Request for review.

---

## 💌Contact

For questions or feedback, fell free to open an Issue or reach out via [GitHub Profile](https://github.com/andyrouge81)