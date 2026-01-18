<h2> Hi, I'm Kunal Sarpe! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230">
<p><em>Software Enginner at <a href="https://www.crisil.com/">Crisil</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30"></em></p>

[![Linkedin: kunal-sarpe]](https://www.linkedin.com/in/kunal-sarpe-bb6ba0341/)
[![GitHub kunalsrp5]](https://github.com/kunalsrp5)

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

