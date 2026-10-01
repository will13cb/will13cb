# Hi, I'm William 👋

Third-year **Computer Science student at Université de Montréal** and incoming **Data Scientist Intern — Optimisation at BRP** for Winter 2027.

I build data pipelines and software systems with an emphasis on correctness, reproducibility, and measured results. My interests include **machine learning, optimization, quantitative finance, and systems programming**.

## 🛠️ Technical Skills

- **Languages:** Python, C, Java, SQL, Bash, JavaScript/TypeScript
- **Data & ML:** PostgreSQL, Pandas, NumPy, scikit-learn, Matplotlib
- **Systems:** Linux, POSIX, pthreads, CMake, gdb, Valgrind
- **Backend & Web:** asyncio, FastAPI, REST APIs, Docker, React, Next.js
- **Testing & Tools:** pytest, JUnit, JaCoCo, PIT, GitHub Actions, Git, Make, Maven

## 📌 Selected Projects

### [Event-Driven Market Probability Engine](https://github.com/will13cb/edmp_engine)

A **Python and PostgreSQL research pipeline** for evaluating next-day ETF forecasts.

- Built a layered warehouse covering **15 ETFs and 32,000+ daily observations**, with concurrent ingestion and SQL feature engineering.
- Implemented **five expanding walk-forward folds** with a 60-trading-day gap between training and evaluation.
- Added **36 pytest cases and database invariants** to check temporal alignment, ingestion, and backtest arithmetic.
- Compared positioning rules against an always-invested benchmark with transaction costs. **The tested strategies did not outperform the benchmark.**

The price-only baseline is complete; event ingestion is a planned extension.

### [Operating System Components in C](https://will13cb.github.io/projects/en/project-operating-systems-c-en.html)

University coursework implementing a **Unix shell, concurrent scheduler, virtual memory manager, FAT32 reader, and Turing machine interpreter**.

Worked with process creation, pipes, thread synchronization, page replacement, and raw filesystem structures, using **gdb and Valgrind** for debugging.

### [Implementing & Benchmarking Classic Algorithms](https://will13cb.github.io/projects/en/project-classic-algorithms-en.html)

Implemented stable matching, dynamic programming, and closest-pair algorithms in **Python**. Compared runtime and solution quality, investigated implementation costs, and identified a validation routine that contaminated benchmark timings.

### [Software Testing & CI Quality Gate](https://github.com/will13cb/graphhopper)

University project extending a GraphHopper fork with targeted **JUnit tests, JaCoCo coverage analysis, and PIT mutation testing**.

Built a **GitHub Actions quality gate** that compares mutation scores against a persisted baseline and fails builds when the score regresses.

### [MaVille](https://will13cb.github.io/projects/en/project-maville-en.html)

A **Java municipal management application** with resident and contractor profiles, REST API integration, persistence, notifications, and JUnit tests.

## 🌱 Currently Learning

Deepening my knowledge of **machine learning, probability calibration, and AI agents**, with a focus on evaluating their outputs and integrating them into reliable data pipelines.

## 📫 Connect

[Portfolio](https://will13cb.github.io) · [LinkedIn](https://linkedin.com/in/william-caron-bastarache) · [Email](mailto:will13cb@gmail.com)
