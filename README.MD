<img src="./banner.svg" width="100%" alt="Ehab Abdalla — backend engineer, NYC. 300M records/week, 320ms query p50, 50+ cloud run jobs." />

I design and run large-scale data pipelines at [Base Layer](https://www.baselayer.com). Off the clock I'm building [real-swe.com](https://www.real-swe.com) — practice software engineering the way it actually works: real codebases, real debugging, no puzzles.

### The system, roughly

```mermaid
flowchart LR
    subgraph ingest [" ingest "]
        A[50 states of<br/>business filings] --> B[Playwright fleet<br/>Cloud Run · proxies]
    end
    subgraph transform [" transform "]
        B --> C[Apache Beam<br/>Dataflow · Pydantic]
    end
    subgraph serve [" serve "]
        C --> D[(PostgreSQL<br/>1.2 TB)]
        D --> E[FastAPI<br/>12k req/day]
    end
    C -. "200–300M records/week" .-> D
    F([me, on call<br/>sentry · incident.io]) -.-> B & C & D & E
```

### Shipped

|  |  |
|---|---|
| [**real-swe**](https://www.real-swe.com) | full-stack SWE practice platform — FastAPI, Postgres, Redis, Monaco IDE, Judge0 sandboxed execution, Stripe billing |
| [**Karika Motors**](https://karikamotors.com) | luxury car-rental fleet in Cairo — filterable fleet, WhatsApp reservation flow |
| [**JavaLens**](https://github.com/ehab20011/java-lens-mac) | JavaFX packet sniffer with a Wireshark-style UI; port-mirrored a managed switch to capture a whole home network into Postgres |
| [**PPP Data Analyzer**](https://github.com/ehab20011/baselayer) | containerized ETL over millions of PPP loans, natural-language → SQL querying |

### Reach me

[LinkedIn](https://www.linkedin.com/in/ehab-abdalla-04ab411b3/) · [ehababdalla03@gmail.com](mailto:ehababdalla03@gmail.com)
