# gcd-euclidean-algorithm-cpp
A simple C++ program that calculates the Greatest Common Divisor (GCD) of two numbers using the Euclidean Algorithm. This project demonstrates basic C++ concepts such as functions, loops, and user input while implementing an efficient mathematical algorithm.
# 📌 GCD Using Euclidean Algorithm (C++)

A simple C++ program that calculates the **Greatest Common Divisor (GCD)** of two numbers using the **Euclidean Algorithm**.
This project is useful for beginners learning **C++ programming and basic algorithms**.

---

## 📖 What is GCD?

The **Greatest Common Divisor (GCD)** of two integers is the largest positive integer that divides both numbers without leaving a remainder.

**Example:**

GCD of 12 and 18 = **6**

---

## ⚙️ Algorithm Used

This program uses the **Euclidean Algorithm**, which works as follows:

1. Take two numbers `a` and `b`
2. Replace `a` with `b`
3. Replace `b` with `a % b`
4. Repeat until `b = 0`
5. The remaining value of `a` is the **GCD**

This method is very efficient and widely used in mathematics and computer science.

---

## 💻 Technologies Used

* C++
* Standard Library (`iostream`)

---

## 📂 Project Structure

```
gcd-euclidean-algorithm-cpp
│
├── main.cpp
└── README.md
```

---

## ▶️ How to Run

1️⃣ Clone the repository

```
git clone https://github.com/your-username/gcd-euclidean-algorithm-cpp.git
```

2️⃣ Go to the project directory

```
cd gcd-euclidean-algorithm-cpp
```

3️⃣ Compile the program

```
g++ main.cpp -o gcd
```

4️⃣ Run the program

```
./gcd
```

---

## 🖥 Example Output

```
Enter two numbers: 24 36
GCD of 24 and 36 is: 12
```

---

## 🎯 Learning Objectives

* Understand the **Euclidean Algorithm**
* Practice **C++ functions and loops**
* Learn how to create and manage **GitHub repositories**

---

⭐ If you like this project, consider giving it a **star** on GitHub!

