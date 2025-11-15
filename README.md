# 📊 Learner Enrolment Analysis Using SQL

## 📌 Executive Summary

This project showcases a practical use case of SQL for analyzing learner enrolment and progression data within an educational institution. The database includes student demographics and enrolment history. Through a series of SQL queries, the project answers key business questions around learner retention, funding, enrolment activity, and program effectiveness.

---

## 🧩 Business Problem

The institution wants to better understand learner activity patterns, including:
- Identifying students still in programs but past their expected end dates
- Tracking enrolment and withdrawal trends for the academic year `23/24`
- Analyzing the impact of funding types on enrolment volume
- Determining learners who transferred but never re-enrolled

These insights are essential for improving student support services, resource allocation, and retention strategies.

---

## 🧪 Methodology

1. **Database Schema Design**:  
   Created two tables — `StudentDetail` and `Enrolment` — representing student information and enrolment records.

2. **Data Analysis Using SQL**:  
   Wrote targeted SQL queries to address real-world business questions.  
   - Used `JOINs`, `WHERE` filters, `GROUP BY`, `CASE`, and `WINDOW FUNCTIONS`
   - Incorporated `CURRENT_DATE` to calculate overdue durations
   - Leveraged `NOT EXISTS` to detect missing re-enrolments after transfers

3. **Query Breakdown**:  
   - Q1–Q7 each address a unique scenario related to student progression or funding insights.

---

## 🧠 Skills Demonstrated

- Relational Database Design  
- SQL Query Writing  
- Filtering and Aggregation  
- Analytical Functions (e.g., `ROW_NUMBER()`, `DATEDIFF`)  
- Business Logic Implementation in SQL  
- Data Auditing and Validation  

---

## 📈 Results & Business Recommendations

- **Learner Monitoring**: Identified students continuing in 2023/24 who are overdue past their expected end dates.
- **Retention Alerting**: Detected learners marked as transferred but never re-enrolled—prompting investigation.
- **Funding Optimization**: Revealed enrolment volume distribution by Funding ID, helping in future budgeting.
- **Data Quality Checks**: Ensured learners have complete and updated enrolment trails, reducing gaps in academic records.

**Recommendations:**
- Implement an automated SQL job to flag overdue learners weekly.
- Notify student services of transfer cases with no new enrolments.
- Reassess funding allocations based on enrolment data grouped by `FundingID`.

---

## 🚀 Next Steps

- Integrate this SQL logic into a BI dashboard (e.g., Power BI or Tableau)
- Automate reporting via stored procedures or scheduled tasks (SQL Agent or cron)
- Expand the schema to include course-level data and outcomes
- Apply Python for additional ETL and data validation workflows

---

💡 *This project is a demonstration of how SQL can be used for real-world educational data analytics and operational decision-making.*











<h1>Hi, I'm Yusuf! </h1>

<h2>Data Engineer Projects:</h2>

- <b>Data Structures and Algorithms Practice (AlgoExpert)</b>


- <b>C# (.NET Desktop Applications)</b>
  - [Ransomware Proof of Concept (Encrypter)](https://github.com/joshmadakor1/EncrypterPOC)

- <b>Python</b>
  - [Package Delivery Application (Datastructures and Algorithms Demo)](https://github.com/joshmadakor1/Package-Delivery-Pathfinding-Algorithm)

<h2>Certifications</h2>

- [How to get into Cybersecurity Starting From Zero](https://www.youtube.com/watch?v=a83ASGn_V_s)


<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="JoshMadakor | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="JoshMadakor | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="JoshMadakor | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/joshmadakor
[youtube]: https://www.youtube.com/c/joshmadakor
[instagram]: https://www.instagram.com/joshmadakor/
[linkedin]: https://linkedin.com/in/joshmadakor

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
