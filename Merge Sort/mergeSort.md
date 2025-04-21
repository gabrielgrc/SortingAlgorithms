# Merge Sort Algorithm

## 📌 Overview

Merge Sort is a **divide-and-conquer** algorithm that divides the input array into two halves, recursively sorts each half, and then merges the sorted halves to produce the final sorted array.

It's known for its **predictable O(n log n)** time complexity and is a **stable** sorting algorithm, meaning it maintains the relative order of equal elements.

---

## ⚙️ How It Works

1. **Divide** the array into two halves.
2. **Recursively** sort both halves.
3. **Merge** the two sorted halves into one sorted array.

This process continues until the array is broken down into single elements, which are inherently sorted.

---

## 🧠 Example

Let's say we want to sort the array:  
`[38, 27, 43, 3, 9, 82, 10]`

Here's how Merge Sort would work step-by-step:

[38, 27, 43, 3, 9, 82, 10] => [38, 27, 43] + [3, 9, 82, 10] => [38] + [27, 43] ... and so on until => Merge all back into a sorted array: [3, 9, 10, 27, 38, 43, 82]


---

## ⏱️ Time and Space Complexity

| Complexity | Performance |
|------------|-------------|
| Best Time  | O(n log n)  |
| Avg Time   | O(n log n)  |
| Worst Time | O(n log n)  |
| Space      | O(n)        |

- **Stable:** Yes
- **In-place:** No (requires auxiliary space for merging)
