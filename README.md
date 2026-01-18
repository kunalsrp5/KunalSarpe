<h2> Hi, I'm Kunal Sarpe! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230">
<p><em>Software Enginner at <a href="https://www.crisil.com/">Crisil</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30"></em></p>

[![Linkedin: kunal-sarpe]](https://www.linkedin.com/in/kunal-sarpe-bb6ba0341/)
[![GitHub kunalsrp5]](https://github.com/kunalsrp5)

WITH profile AS (
    SELECT
        'Kunal Sarpe'::text           AS name,
        'Data Engineer'::text         AS role,

        ARRAY[
            'Python',
            'SQL'
        ]::text[]                     AS languages,

        ARRAY[
            'Pentaho Data Integration',
            'Custom Python ETL',
            'Data Validation',
            'Data Reconciliation',
            'Analytics Engineering'
        ]::text[]                     AS tools,

        ARRAY[
            'Batch Pipelines',
            'Incremental Loads',
            'DAG-Based Orchestration',
            'Analytics-Ready Modeling'
        ]::text[]                     AS architecture,

        ARRAY[
            'Banking & Risk Analytics',
            'Regulatory Reporting',
            'Early Warning Signals',
            'Music Streaming Analytics'
        ]::text[]                     AS domains,

        JSONB_BUILD_OBJECT(
            'flagship_project', 'Earcandy – Music Streaming Analytics Platform',
            'learning_focus',   'Advanced SQL, pipeline design, system architecture'
        )                              AS projects_and_learning,

        'Turning raw data into decision-ready insights'::text
                                        AS mission
)

SELECT *
FROM profile;

