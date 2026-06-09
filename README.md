# Hi, I'm Maverick Adrian 👋

**Backend Systems Engineer** · Davao City, Philippines

I build production-grade backend systems — REST APIs, real-time WebSocket services, task queues, and CLI-first tools — primarily in Python and TypeScript. I focus on deliberate architecture: every project ships with documented design decisions, Docker Compose orchestration, and a clean API contract.

---

## 🛠️ Tech Stack

**Languages:** Python · TypeScript · JavaScript · SQL

**Frameworks:** FastAPI · Django · Django REST Framework · NestJS · Express

**Backend & Databases:** PostgreSQL · Redis · MongoDB · TimescaleDB · Prisma · Mongoose · asyncpg · Node.js · REST APIs · WebSockets · Socket.io · Celery · Celery Beat

**AI:** Claude API (Anthropic SDK) · Tool Use / Function Calling · Prompt Engineering · YOLOv8

**Tools & DevOps:** Docker · Docker Compose · GitHub Actions CI/CD · Poetry · Zod · Git · Postman

---

## 🚧 Backend Projects

### [APEX](https://github.com/malbarroso16/apex) — FastAPI · TimescaleDB · NumPy · asyncpg · Textual · Docker
A real-time F1 telemetry and race strategy engine with a live Textual TUI dashboard.
- Monte Carlo strategy engine running 10,000 vectorized NumPy simulations per driver, with tire grip decay, safety car modifiers, and pit window analysis
- TimescaleDB hypertable with auto-compression on `telemetry_points`; async writes via asyncpg without blocking the FastAPI event loop

### [Logbook](https://github.com/malbarroso16/logbook) — Django · DRF · Celery · Redis · PostgreSQL · GitHub Actions · Docker
A production-grade personal finance REST API with a Textual TUI client and a full CI/CD pipeline.
- Advanced Django patterns: `django-simple-history` audit trails, ContentTypes polymorphic tagging, DB-driven Celery Beat recurring schedules, SHA-256 hash-based CSV import deduplication
- Full GitHub Actions pipeline: ruff · mypy · pytest with 80% coverage gate · Docker image build and push on merge to `main`

### [TermChat](https://github.com/malbarroso16/termchat) — NestJS · Socket.io · Redis · PostgreSQL · Prisma · Docker
A Discord-inspired real-time terminal chat app with a NestJS WebSocket gateway and Ink-based CLI client.
- Redis Pub/Sub for cross-instance Socket.io broadcasting; sliding window rate limiter (INCR/EXPIRE) enforcing 5 msg/s per user
- Composite index on `(channelId, createdAt)` for message history queries; 8-second grace-period disconnect handler for presence tracking

### [AI Recipe Meal Planner](https://github.com/malbarroso16/ai-recipe-planner) — TypeScript · Express · MongoDB · Claude API · Zod · Ink · Docker
A TypeScript monorepo meal planning app that uses the Claude API to generate, scale, and customize recipes.
- Forced Claude tool use (`tool_choice`) with Zod schema validation; single structured retry on failure prevents malformed data from reaching the database
- MongoDB aggregation pipeline (unwind → group by `normalizedName` + `canonicalUnit` → sum) producing a de-duplicated grocery list across any date range

---

## 📊 Data Analysis & Data Science Projects

A collection of end-to-end data projects spanning business intelligence, EDA, statistical analysis, and machine learning — built with Python, SQL, and Power BI.

### Data Analysis

**[Marketing ROI Analysis](https://github.com/malbarroso16/Marketing-Campaign-ROI-Analysis)** — Python · SQL · Excel
Cleaned and merged messy Excel and SQL data to calculate true ROAS for paid campaigns, identifying attribution errors and opportunities to improve ROAS by 25%.

**[Sales Performance Dashboard](https://github.com/malbarroso16/Sales-Performance-Dashboard)** — Python · SQL · Power BI · Excel
Analyzed sales data with advanced SQL and Python, delivering an interactive Power BI dashboard and an Excel companion report with PivotTables and KPI trend analysis.

**[E-commerce Purchase Funnel Analysis](https://github.com/malbarroso16/E-commerce-Purchase-Funnel-Analysis)** — Python · Plotly · Excel
Constructed a multi-stage purchase funnel from a user event log, identifying the biggest drop-off point and producing a recommendation projected to improve conversion by 15%.

**[A/B Test Analysis for a Marketing Campaign](https://github.com/malbarroso16/A-B-Test-Analysis-for-Marketing-Campaign)** — Python · SciPy
Applied a Chi-Squared test with proper significance testing and confidence intervals to deliver a definitive, data-driven recommendation on a new landing page.

**[Movie Ratings Analysis](https://github.com/malbarroso16/Movie-Ratings-Analysis)** — Python · TMDB API · Pandas
Queried the TMDB API, cleaned nested JSON data, and engineered financial metrics (Profit, ROI) to analyze genre performance and budget optimization strategies.

### Machine Learning & Deep Learning

**[AI-Assisted Pneumonia Detection](https://github.com/malbarroso16/AI-Assisted-Pneumonia-Detection)** — TensorFlow · Keras · Streamlit
Trained a CNN on a chest X-ray dataset achieving 94% accuracy, deployed as an interactive Streamlit web app for real-time predictions.

**[Online Retail Customer Segmentation](https://github.com/malbarroso16/Online-Retail-Customer-Segmentation)** — Python · Scikit-learn · SQL
Performed RFM analysis on a SQL database, then applied K-Means clustering to segment customers into distinct personas for targeted marketing strategies.

**[Health Insurance Cost Predictor](https://github.com/malbarroso16/Health-Insurance-Cost-Predictor)** — Scikit-learn · Streamlit
Built and evaluated Linear Regression and Random Forest models to predict insurance costs, deployed as a Streamlit app for real-time estimation.

---

## 🎓 Education & Recognition

**B.S. Computer Engineering** — Ateneo de Davao University (2020–2025)
🏆 ICpEP Regional Programming Competition (Python) 2022 — **Champion**
**PROCESSOR** — Club President 2023–2024

---

## 📬 Connect

[LinkedIn](https://www.linkedin.com/in/maverickadrianbarroso/) · [Email](mailto:maverickadrianbarroso@gmail.com)
