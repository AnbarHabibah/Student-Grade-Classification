# Student-Grade-Classification
Categorized exam scores using Python logic structure (if-elif-else)

### Student Grade Classification Program
In this project, I developed a simple Python-based program to classify student exam grades into categories using conditional logic. This task was designed to strengthen foundational Python skills, especially in user input handling, data type identification, and control flow using `if-elif-else` statements.

The program requests input from users, including student name, student ID (NIM), and exam score, then:
- Displays the data type of each input
- Categorizes the score based on predefined grade brackets
- Outputs a structured evaluation report

---

### 💡 Program Specifications

#### **Input:**
- Student Name (`str`)
- Student ID / NIM (`str`)
- Exam Score (0–100) (`int`)

#### **Grade Classification Logic:**
| Score Range | Grade | Description      |
|-------------|--------|------------------|
| 85–100      | A      | Sangat Baik |
| 75–84       | B      | Baik      |
| 60–74       | C      | Cukup     |
| 40–59       | D      | Kurang    |
| < 40        | E      | Sangat Kurang |

#### **Sample Output:**
```
Masukkan nama mahasiswa: Sarah
Masukkan NIM: 12345678
Masukkan nilai ujian (0-100): 81

Nama: Sarah (type: <class 'str'>)
NIM: 12345678 (type: <class 'str'>)
Nilai: 81 (type: <class 'int'>)

Hasil Evaluasi:
Mahasiswa: Sarah (NIM: 12345678)
Nilai Ujian: 81
Kategori Nilai: B (Baik)
```

---

## Insight
From this simple classification program, I learned:
1. How to effectively handle user input in Python.
2. The importance of data type checking during input validation.
3. The use of `if-elif-else` control structures for decision-making.
4. How to build a user-friendly, readable console interface for basic evaluations.

---

## Advice
This project can be extended in several ways:
1. Add validation to handle non-integer inputs or out-of-range scores.
2. Integrate a loop to allow batch input for multiple students.
3. Export the evaluation results to a `.csv` file or database for academic records.
4. Create a GUI version using libraries like Tkinter or PyQt.

---

If you have any suggestions or feedback, feel free to reach out:

📧 anbarhabibah2@gmail.com  
🔗 [LinkedIn – Anbar Habibah](https://www.linkedin.com/in/anbarhabibah)

#Python #BeginnerProject #PythonProgramming #ConditionalLogic #LearningPython #GradeClassification #DataScienceBeginner #DataScience
