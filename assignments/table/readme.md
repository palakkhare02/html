# HTML Time Table – Learning Progress

This folder contains two HTML timetable implementations created during my HTML learning journey.

The purpose of uploading both files is to **show the difference between basic table usage and best-practice semantic HTML**.

---

## 📄 Files Included

### 1️⃣ time_table1.html
This version uses a simple HTML table structure.

**Concepts used:**
- `<table>`, `<tr>`, `<th>`, `<td>`
- `rowspan` and `colspan`
- `caption`, `thead`, `tbody`, `tfoot`

**Limitations:**
- No `scope` attribute
- Less accessible
- Table meaning (row vs column headers) is not clearly defined

This file represents my **initial understanding** of HTML tables.

---

### 2️⃣ table_2.html
This version follows **HTML best practices**.

**Improvements made:**
- Used `scope="col"` for time (horizontal headers)
- Used `scope="row"` for days (vertical headers)
- Added `Day \ Time` cell to clearly represent table axes
- Improved accessibility and semantics
- Cleaner and more professional structure

This file represents my **improved understanding and learning progress**.

---

## 🎯 Key Learning Outcomes

- Difference between basic and semantic HTML tables
- Importance of `scope="row"` and `scope="col"`
- How accessibility improves with proper table structure
- Real-world and recruiter-friendly HTML practices

---

## 🚀 Next Improvements (Future Plan)

- Add CSS styling instead of HTML attributes
- Make the table responsive
- Highlight lunch break using CSS
