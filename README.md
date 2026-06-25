# BangaloreNow

### Everything a techie in Bangalore needs, in one place.

BangaloreNow is a real-time dashboard for Bangalore's tech and startup scene. Hackathons, meetups, demo days, talks, workshops, job boards, communities — the things builders actually care about are scattered across dozens of sites, Discords, calendars, and feeds. BangaloreNow pulls them into a single live view.

If it matters to someone building in Bangalore, the goal is for it to be here.

🔗 Live: [https://bangalorenow.live](https://bangalorenow.live)

---

## Beta Release: Events

The first module is **tech and startup events**.

Right now the city's event data lives across Luma, Meetup, Eventbrite, community Discords, Twitter, and countless individual sites. There's no single place to see what's on this week. BangaloreNow fixes that. An automated pipeline collects, filters, and enriches event data from across these sources and surfaces it in one continuously updated feed.

Things you'll find:

* **Startup pitch nights & demo days** (e.g. Koramangala)
* **Hackathons & build weekends**
* **Tech meetups & talks** (e.g. Indiranagar)
* **Design / product / engineering workshops** (e.g. Jayanagar)
* **Founder and community gatherings**

One feed, all the sources, no tab-hopping.

---

## Acknowledgements

The pipeline builds on the open-source work of **@captn3m0** and the **blr-today** project. Their open dataset, `events.db`, provided the initial foundation for organizing the city's event data. We're grateful for their contribution.

Source: [https://github.com/blr-today/dataset](https://github.com/blr-today/dataset)

---

## Architecture

The system is a **fully automated, cloud-native pipeline** deployed on **Google Cloud Platform (GCP)**.

* **Continuous ingestion** from across the web — sites, feeds, and community sources
* **Automated filtering and enrichment** for data quality and relevance
* **Scalable infrastructure** designed for city-scale load
* **High reliability**, engineered to run continuously without manual intervention

The result is a dashboard that reflects what's happening in the scene in real time, with minimal lag and minimal gaps.

---

## Contributing

The project is built in the open and the entire system will be open-sourced — no closed components, no hidden APIs. It's built by builders, for builders.

We're looking for contributors in the following areas, listed by current priority:

1. **Frontend Developers** — Building the interface for viewing the scene.
2. **Designers** — Turning raw data into a clean, fast, usable interface.
3. **Backend / Cloud Engineers** — Hardening the pipelines, scaling the architecture, and improving reliability.
4. **ML / MLOps Engineers** — Building data processing for dedup, relevance ranking, anomaly detection, and automated insights.

### Why contribute

* You'll be building infrastructure used by Bangalore's tech and startup community.
* Your work will be **fully open-source** and credited to you.
* Early contributors join as part of the project's founding group.

---

## Contact

**Siddartha A Y**
* Email: [siddartha_ay@protonmail.com](mailto:siddartha_ay@protonmail.com)

**Kushal B Gowda**
* Email: [kushalb2005@gmail.com](mailto:kushalb2005@gmail.com)

**Anish Kasetty**
* Email: [anishkasetty@gmail.com](mailto:anishkasetty@gmail.com)

---

## License

Licensed under the **Open Data Commons Open Database License (ODbL) v1.0**.

The project and its data remain free and open. You can use, remix, and build upon it, provided you share derivative data back under the same terms. This keeps the project from being closed off or privatized.

---

<div align="center">

# Know your scene. Build its future.

[https://bangalorenow.live](https://bangalorenow.live)

</div>
