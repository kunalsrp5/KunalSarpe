<h2> Hi, I'm Kunal Sarpe! <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3dxMTNsN2lpeG1vcmlqYjNxM3FzNzk4b2N2YW5mejYyNmNxYnQyZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/S9RnJWRWoiRZlHgaHa/giphy.gif" width="50"></h2>
<img align='right' src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcGx5NnRvb2U1cGZyYm56Zjhham85YXE2em5za3o1bm1mOTV4enYyZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/QDjpIL6oNCVZ4qzGs7/giphy.gif" width="80" height="80">
<p><em>Software Enginner at <a href="https://www.crisil.com/">Crisil</a></em></p>

[![Linkedin: kunal-sarpe](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/kunal-sarpe-bb6ba0341/)](https://www.linkedin.com/in/kunal-sarpe-bb6ba0341/)
[![GitHub kunalsrp5](https://img.shields.io/github/followers/kunalsrp5?label=follow&style=social)](https://github.com/kunalsrp5)


```sql

WITH profile AS (
    SELECT
        'Kunal Sarpe'        AS name,
        'Data Engineer'      AS role,

        [
            'Python',
            'SQL'
        ]                    AS languages,

        [
            'Pentaho Data Integration',
            'Pentaho Report Designer',
            'Apache Spark',
            'Apache Airflow',
            'Snowflake',
            'Neon Postgres'
        ]                    AS tools,

        [
            'Batch Pipelines',
            'Incremental Loads',
            'DAG-Based Orchestration',
            'Analytics-Ready Modeling'
        ]                    AS architecture,

        [
            'Banking & Risk Analytics',
            'Regulatory Reporting',
            'Early Warning Signals'
        ]                    AS domains,

        {
            flagship_project : 'Earcandy – Music Streaming Analytics Platform',
            learning_focus   : 'Pandas, NumPy, Advanced SQL, pipeline design, system design, data structures and algorithms'
        }                    AS projects_and_learning,

        'Turning raw data into decision-ready insights'
                             AS mission
)

SELECT *
FROM profile;
```

