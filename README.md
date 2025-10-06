# Coding-Questions-and-Solutions

Welcome to my collection of **coding questions and solutions**!  
This repository is designed to track my learning progress and help others prepare for **technical interviews**, focusing on **Java**, **Python**, and **Data Structures & Algorithms (DSA)**.

About Me
👩‍💻 Deepika J

B.E. in Computer Science | MBA 

Skills: C, Java, Python, Frontend Development, Data Science, Project Management

Interests: Software Engineering | Data Analysis | AI | Project Coordination

🌐 Follow my journey in coding and continuous learning!

## 🧩 Topics Covered
- 🧠 **Arrays**
- 🔤 **Strings**
- 🔗 **Linked List**
- 🧱 **Stack & Queue**
- 🌳 **Trees & Graphs**
- 🔄 **Recursion**
- 📊 **Sorting & Searching**
- 💡 **Miscellaneous Problems**# 

## 📂 Folder Structure


---

## 🧠 Example Problem Format

Each file includes:
1. **Question description**
2. **Example input/output**
3. **Solution code**
4. **Time and Space complexity**

### Example — `Arrays/reverse_array.java`
```java
/*
💡 Question:
Reverse an array of integers.

🧠 Example:
Input: [1, 2, 3, 4, 5]
Output: [5, 4, 3, 2, 1]

✅ Solution:
Time Complexity: O(n)
Space Complexity: O(1)
*/
public class ReverseArray {
    public static void main(String[] args) {
        int[] arr = {1, 2, 3, 4, 5};
        for(int i = arr.length - 1; i >= 0; i--) {
            System.out.print(arr[i] + " ");
        }
    }
}



