# AlgoNova: Data Structure Visualizer (Java Swing)

AlgoNova is a **Java Swing-based desktop application** that provides interactive visualizations of core data structures and their operations. It includes support for:

* Stack
* Queue
* Linked List
* Binary Search Tree (BST)
* BFS and DFS visualizations

This application is designed to help students and interviewees demonstrate how these fundamental data structures work visually.

---

## 🚀 Features

### 1. **Stack Visualizer**

* Dynamic or fixed-size stack
* Push, Pop, Undo, Reset operations
* Clearly labeled TOP pointer

![Stack1](./stack1.png)
![Stack2](./stack2.png)
![Stack3](./stack3.png)

---

### 2. **Queue Visualizer**

* Supports Push (enqueue), Pop (dequeue), Undo, Reset
* Tracks Front and Rear indices

![Queue1](./Queue1.png)
![Queue2](./Queue2.png)

---

### 3. **Linked List Visualizer**

* Create random or custom lists
* Insert or Remove by index
* Shows directional pointers

![LL1](./LL1.png)
![LL2](./LL2.png)

---

### 4. **Binary Search Tree (BST)**

* Insert and delete nodes
* Tree traversal (inorder, preorder, postorder)
* Live dry-run code viewer
* Adjustable animation speed

![BST1](./BST1.png)
![BST2](./BST2.png)
![BST3](./BST3.png)

---

## 💻 Technologies Used

* Java 8+
* Java Swing (AWT for canvas rendering)
* Maven for build automation

---

## 🛠 How to Run

### Prerequisites:

* Java JDK 8 or later
* Maven

### Build:

```bash
mvn clean package -DskipTests
```

### Run:

```bash
java -jar target/staqueue-1.0-SNAPSHOT.jar
```

---

## 🌐 Run in Browser (CheerpJ + Netlify)

We use [CheerpJ](https://leaningtech.com/cheerpj/) to deploy the `.jar` directly in a web browser via WebAssembly — no Java install needed.

**Live demo**: [https://algonova-dsa-app.netlify.app/](https://algonova-dsa-app.netlify.app/)

> Note: GUI may lag or freeze in browser due to Swing rendering limits under CheerpJ. For the best experience, run locally.

---

## 🎓 Ideal For:

* Students learning data structures
* Interview candidates explaining logic
* Educators giving algorithm demos

---

## 📦 Project Structure

```
src/main/java/com/staqueue/  # Main source files
src/test/java/               # JUnit test cases
pom.xml                      # Maven project config
index.html                   # (Optional) For browser deployment via CheerpJ
```

---

## 🧑‍💻 Images


## 🧑‍💻 Author

**Harshal Sonawane**
Email: [harshal.sonawane21@pccoepune.org](mailto:harshal.sonawane21@pccoepune.org)

---

## 📜 License

This project is open for educational and demonstration purposes only.
