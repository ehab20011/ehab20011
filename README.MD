```sql
psql (16.4, ehab build)
Connected to database "ehab" as user "visitor".
SSL connection (TLSv1.3) ✓ — read-only session. SELECT freely.

ehab=# \whoami
```

```
 name     | Ehab Abdalla
 role     | Software Engineer II @ Base Layer
 base     | New York City
 focus    | data pipelines · postgres performance · cloud infrastructure
 volume   | 200–300M records/week
 dataset  | 1.2 TB
 latency  | 1.4s → 320ms
(1 row)
```

```sql
ehab=# SELECT * FROM currently_shipping;
```

```
 -- large-scale Secretary of State & lien data pipelines
 -- python · apache beam · dataflow · pydantic
 -- postgres schemas tuned to hold terabytes and answer in milliseconds
 -- 50+ cloud run jobs collecting state business data around the clock
```

```sql
ehab=# SELECT name, what, link FROM projects ORDER BY pride DESC;
```

| name | what | link |
|------|------|------|
| **real-swe** | practice real-world software engineering — debugging challenges, daily project generators, repo quizzes. FastAPI · Postgres · Redis · Monaco · Judge0 | [real-swe.com](https://www.real-swe.com) |
| **Karika Motors** | premium car-rental fleet site, Cairo — filterable fleet, WhatsApp booking flow | [karikamotors.com](https://karikamotors.com) |
| **PPP Data Analyzer** | containerized ETL over millions of PPP loans, with natural-language → SQL querying | [repo](https://github.com/ehab20011/baselayer) |
| **JavaLens** | JavaFX packet sniffer with a Wireshark-style UI, captures streamed into Postgres | [repo](https://github.com/ehab20011/java-lens-mac) |

```sql
ehab=# \d skills
```

```
      Column      |  Type  |  Values
------------------+--------+--------------------------------------------------
 languages        | text[] | {Python, Java, C++, TypeScript, JavaScript, SQL, Bash}
 frameworks_tools | text[] | {FastAPI, React, Next.js, SQLAlchemy, Docker, Redis, Playwright, Pytest}
 cloud_devops     | text[] | {GCP (Cloud Run, Dataflow, VMs), AWS, Linux, GitHub Actions}
 databases        | text[] | {PostgreSQL, MongoDB, Firebase}

Indexes: "postgres_is_home" PRIMARY KEY, btree (languages)
```

```sql
ehab=# INSERT INTO connections (channel, address) VALUES
```

> [LinkedIn](https://www.linkedin.com/in/ehab-abdalla-04ab411b3/) · [Email](mailto:ehababdalla03@gmail.com) · [Portfolio](https://github.com/ehab20011/portfolio)

```sql
ehab=# DROP TABLE ehab;
ERROR:  permission denied — role "visitor" is read-only. nice try though.

ehab=# \q
-- connection to server closed. thanks for stopping by.
```
