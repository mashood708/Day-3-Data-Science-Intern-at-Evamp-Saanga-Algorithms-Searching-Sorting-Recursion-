# Day-3-Data-Science-Intern-at-Evamp-Saanga-Algorithms-Searching-Sorting-Recursion-
# Day 3 – Algorithms: Searching, Sorting, Recursion  
_As part of my role as a **Data Science Intern at Evamp & Saanga**_

## 📝 Summary  
This repository contains manual Python implementations of key algorithms that are fundamental for problem-solving in **data science**, **machine learning**, and **software development**.

---

## 🔹 Sorting Algorithms  
- **Bubble Sort** – Basic comparison-based sorting  
- **Merge Sort** – Divide-and-conquer sorting  
- **Quick Sort** – Efficient sorting using pivot partitioning  

## 🔹 Searching Algorithms  
- **Linear Search** – Simple sequential search  
- **Binary Search** – Fast search in sorted arrays  

## 🔹 Recursion  
- Factorial  
- Fibonacci sequence  

---

## 💻 Example Code  

```python
def bubble_sort(arr):
    for i in range(len(arr)):
        for j in range(0, len(arr) - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
    return arr
