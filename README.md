# Civic Seismograph

The **Civic Seismograph** is a public-interest project that measures the political "tremors" within the United States.  
Just like an earthquake seismograph records spikes in seismic activity, this tool tracks **spikes and dips in political rhetoric and events** that raise or lower the risk of instability and violence.

---

## 🌍 Project Overview

- **Purpose:** Provide a transparent, data-driven visualization of the U.S. political climate.  
- **Approach:** Analyze public rhetoric, media amplification, and real-world events; classify them as **escalatory (+)** or **de-escalatory (–)**; and calculate a daily index.  
- **Output:** A live seismograph line that shows when political tensions are rising or cooling, supported by a feed of source material.  

---

## 📊 The Seismograph Index

- **0 = Baseline**  
- **Positive values = Inflammatory rhetoric or violent events**  
- **Negative values = Cooling rhetoric, unity calls, or stabilizing events**  

The index is weighted by the **influence of the speaker** (e.g., the President’s words carry more weight than a local pundit) and smoothed over time to reduce noise.

---

## 📂 Repository Structure

This repo serves as the **overview hub** for the Civic Seismograph project.  
It links to open-source components and provides governance, methodology, and documentation.

- `/docs` — methodology, scoring rubric, governance  
- `/core` (public or linked subrepo) — scoring engine, Next.js frontend, visualization code  
- `/data` (public or linked subrepo) — sanitized JSON/CSV of daily indices and feeds  
- `/ops` (private) — ingestion pipelines, API keys, scrapers (not public)

---

## 🔎 Transparency & Neutrality

The Civic Seismograph is designed to be **auditable**:

- All scoring rules, lexicons, and weights are open.  
- Datasets are published under open licenses for replication and critique.  
- Pull requests and issues are welcome for refining methodology.  
- A clear separation exists between **open logic** and **private ops** to ensure both transparency and operational safety.

---

## 📈 Planned Features

- Live **national seismograph** with spikes/dips  
- Historical seismographs for **Obama, Trump (I), Biden, Trump (II)** eras  
- Left vs Right sub-indexes to show where rhetoric originates  
- Annotated feeds of recent rhetoric and events with context  
- Methodology and scoring rubric open for community feedback

---

## 🛠️ Tech Stack

- [Next.js](https://nextjs.org/) + [Vercel](https://vercel.com/) for frontend + deployment  
- [Prisma](https://www.prisma.io/) + PostgreSQL (Supabase/Neon) for data  
- [Recharts](https://recharts.org/) for seismograph visualization  
- GitHub Actions for automation and data publishing

---

## ⚖️ Licensing

- **Code:** MIT License (free to use/modify with attribution)  
- **Data:** CC BY 4.0 (free to share/adapt with attribution)  

See [LICENSE](./LICENSE) for details.

---

## 🤝 Contributing

We welcome contributions, especially in:

- Improving phrase lexicons and scoring weights  
- Enhancing visualization components  
- Providing academic or civic-tech review of methodology  

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## 📬 Contact

- **Project Maintainer:** [Your Name or Org]  
- **Issues & Feedback:** Please open a [GitHub Issue](../../issues)  

---

### ⚠️ Disclaimer

The Civic Seismograph is an **experimental civic-technology project.**  
It is not predictive, but **descriptive**: a tool to monitor rhetoric and events in order to foster transparency, accountability, and resilience.  
It should not be interpreted as a guarantee of future outcomes.
