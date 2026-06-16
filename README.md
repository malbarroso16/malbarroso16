# Hi, I'm Maverick 👋

**Data Analyst & Data Engineer** · Davao City, Philippines

I build end-to-end data solutions — from cleaning and analyzing business data to engineering real-time pipelines and BI dashboards. I focus on work that's complete and deliverable: every project ships with documented findings, reproducible code, and a clear output for stakeholders.

---

## 🛠️ Tech Stack

**Languages:** Python · SQL · TypeScript · JavaScript

**Data Analysis & BI:** Pandas · NumPy · Matplotlib · Seaborn · Plotly · Power BI · Looker Studio · Excel

**Data Engineering:** FastAPI · TimescaleDB · asyncpg · PostgreSQL · SQL Server · SQLite · Docker · Docker Compose · REST APIs

**Tools & DevOps:** Git · GitHub Actions CI/CD · Poetry · Postman

**Backend:** Django · DRF · NestJS · Express · Redis · MongoDB · Celery · WebSockets

---

## 📊 Data Analysis Projects

### [Sales Performance Dashboard](https://github.com/malbarroso16/Sales-Performance-Dashboard) — Python · pandas · Power BI · Excel
Analyzed 9,800 Superstore sales records to surface performance drivers across regions, categories, and customer segments.
- Solved a mixed date format problem (MM/DD/YYYY vs DD/MM/YYYY) with a custom conversion function, then built 7 visualizations across regional, category, and customer dimensions
- Delivered dual stakeholder outputs — an interactive Power BI dashboard and an Excel companion — surfacing that the West region led sales, Technology drove top revenue, and high-value "whale" customers warranted a dedicated VIP strategy

### [Marketing ROI Analysis](https://github.com/malbarroso16/Marketing-Campaign-ROI-Analysis) — Python · pandas · SQLite · matplotlib · seaborn
Diagnosed an attribution gap in a simulated marketing dataset by merging messy campaign cost data with a Kaggle e-commerce dataset stored in SQLite.
- Channel-level ROAS appeared healthy at 4–7x, but campaign-level ROAS fell below 1x — revealing an 85% revenue attribution gap
- Identified 3 loss-making campaigns for immediate pausing and recommended a full attribution system overhaul

### [A/B Test Analysis for a Marketing Campaign](https://github.com/malbarroso16/A-B-Test-Analysis-for-Marketing-Campaign) — Python · SciPy · Excel
Evaluated whether a new landing page design significantly improved conversion rates across 294,480 balanced users.
- Applied a Chi-Squared test (p=0.2177, α=0.05) and correctly interpreted a null result — no statistically significant difference between the 12.04% control and 11.89% treatment groups
- Recommended retaining the current design, avoiding unnecessary implementation costs and risk

---

## ⚙️ Data Engineering Projects

### [APEX](https://github.com/malbarroso16/apex-f1-telemetry) — FastAPI · TimescaleDB · NumPy · asyncpg · Docker
A real-time F1 telemetry ingestion and race strategy engine with a live Textual TUI dashboard.
- Ingested real-time telemetry via FastAPI async workers into a TimescaleDB hypertable with auto-compression; non-blocking asyncpg writes kept the event loop free under high throughput
- Monte Carlo strategy engine running 10,000 vectorized NumPy simulations per driver with exponential tyre decay, safety car modifiers, and clean-air pit window constraints — producing named race recommendations

### [Real-Time Weather Data Pipeline](https://github.com/malbarroso16/Real-Time-Weather-Data-Pipeline-with-Power-BI-Dashboard) — Python · SQL Server · Power BI · REST API
A complete extract → store → visualize pipeline pulling live weather data for multiple cities.
- Automated multi-city weather ingestion from the OpenWeatherMap API, storing structured time-stamped records in SQL Server
- Visualized results in a live Power BI dashboard with current conditions and historical trends


---

## 🤖 Data Science Projects

### [AI-Assisted Pneumonia Detection](https://github.com/malbarroso16/AI-Assisted-Pneumonia-Detection) — TensorFlow · Keras · Streamlit
Trained a CNN on a chest X-ray dataset achieving 94% accuracy; deployed as an interactive Streamlit web app for real-time image-upload predictions.

### [Online Retail Customer Segmentation](https://github.com/malbarroso16/Online-Retail-Customer-Segmentation) — Python · Scikit-learn · SQL
Performed RFM analysis on a SQL database and applied K-Means clustering to segment customers into distinct personas for targeted marketing strategies.

### [Health Insurance Cost Predictor](https://github.com/malbarroso16/Health-Insurance-Cost-Predictor) — Scikit-learn · Streamlit
Built and evaluated Linear Regression and Random Forest models to predict insurance costs; deployed as a Streamlit app for real-time estimation.

---

## 🔧 Backend Development Projects

### [Logbook](https://github.com/malbarroso16/logbook) — Django · DRF · Celery · Redis · PostgreSQL · GitHub Actions · Docker
A production-grade personal finance REST API with async PDF report generation, a Textual TUI client, and a full CI/CD pipeline.
- Advanced Django patterns: `django-simple-history` audit trails, ContentTypes polymorphic tagging, DB-driven Celery Beat recurring schedules, SHA-256 hash-based CSV import deduplication
- Full GitHub Actions pipeline: ruff · mypy · pytest with 80% coverage gate · Docker image build and push on merge to `main`

### [TermChat](https://github.com/malbarroso16/termchat) — NestJS · Socket.io · Redis · PostgreSQL · Prisma · Docker
A Discord-inspired real-time terminal chat app with a NestJS WebSocket gateway and Ink-based CLI client.
- Redis Pub/Sub for cross-instance Socket.io broadcasting; sliding window rate limiter enforcing 5 msg/s per user
- Composite index on `(channelId, createdAt)` for message history queries; 8-second grace-period disconnect handler for presence tracking

### [AI Recipe Meal Planner](https://github.com/malbarroso16/ai-recipe-planner) — TypeScript · Express · MongoDB · Claude API · Zod · Docker
A TypeScript monorepo meal planning app using the Claude API to generate, scale, and customize recipes on demand.
- Forced Claude tool use with Zod schema validation; single structured retry on failure prevents malformed data from reaching the database
- MongoDB aggregation pipeline producing a de-duplicated grocery list with combined, by-day, and by-recipe views across any date range

---

## 🎓 Education & Recognition

**B.S. Computer Engineering** — Ateneo de Davao University (2020–2025)
🏆 ICpEP Regional Programming Competition (Python) 2022 — **Champion**
**PROCESSOR** — Club President 2023–2024

---

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/maverickadrianbarroso/) · [Email](mailto:maverickadrianbarroso@gmail.com)
