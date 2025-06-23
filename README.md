## ⚙️ Take-Home Assignment – Python Automation Engineer

### 🎯 Objective

Build a **modular web scraper** using **Playwright** (or Selenium) that extracts product data from a public e-commerce site and simulates human-like browsing behavior. This exercise demonstrates your skills in automation, anti-detection, and scalable code design.

---

### 🧩 Task

Create a Python CLI tool that:

1. **Navigates a public product listing site**
   Suggested: [https://books.toscrape.com](https://books.toscrape.com)

2. **Scrapes the following per product**:

   * Title
   * Price
   * Star rating
   * Product detail URL

3. **Simulates human behavior**:

   * Randomized wait times
   * User-agent rotation
   * Headless mode with optional toggle

4. **Stores output** in:

   * JSON or CSV format
   * Bonus: SQLite DB with SQLAlchemy

5. **Handles edge cases**:

   * Pagination (at least 3 pages)
   * Empty/invalid pages gracefully
   * Reusable session/cookies

---

### ✅ Bonus Points (Not Mandatory)

* CLI args: `--max-pages`, `--output-format`, `--headless`
* Async scraping using `asyncio` + Playwright
* Dockerfile with working `CMD`
* Tests (e.g., with `pytest`)
* Optional integration with `ProxyMesh` or other rotating proxy services

---

### 💡 Expectations

| Area             | Expectation                                 |
| ---------------- | ------------------------------------------- |
| Code Quality     | Modular, clean, and readable                |
| Structure        | Separation of logic, config, and CLI        |
| Anti-Bot Tactics | Realistic human simulation (no brute speed) |
| Documentation    | `README.md` with setup & usage              |

---

### 🗂 Submission Format

* GitHub repo or ZIP file
* Include:

  * `scraper/` directory with Python source
  * `requirements.txt` or `pyproject.toml`
  * `README.md`
  * Sample output file (`output.json` or `.csv`)

---

### 🕐 Time Estimate

Designed to take **\~4–6 hours** depending on bonus features.

---

### ✉️ Submit

Send your submission to **[careers@preplink.ai](mailto:careers@preplink.ai)**
Subject: **Senior Python Scraper — \[Your Name]**

---

Would you like me to generate a matching `README.md` scaffold or file layout for this repo as well?
