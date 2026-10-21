# 📊 Customers Analysis Report – Power BI Dashboard

An interactive Power BI dashboard connected to a database, designed to analyze B2B customer bookings in the travel & hospitality industry. It gives a complete view of booking performance, customer behavior, and demand patterns across markets and properties.

![Dashboard Preview]https://github.com/ahmed-saker/Customers-Analysis-Report-Power-BI-Dashboard/blob/main/Customers%20Analysis%20Reprot.pdf

---

## 📌 What Does This Dashboard Do?

The dashboard transforms raw booking and traffic data into clear, interactive visuals so teams can monitor performance, understand customers, and make faster decisions. It brings together:

- Year-over-year comparison of bookings and sales
- Customer-level performance and traffic efficiency
- Demand analysis by country, province, and guest nationality
- Hotel-level performance
- Booking behavior: length of stay and booking lead time

## 💡 How Does It Help?

- **Track performance:** compare current vs. previous year bookings and sales, month by month, to spot growth or decline early.
- **Understand customers:** see which customers contribute the most bookings and how efficiently their requests convert into bookings (look-to-book).
- **Monitor service quality:** follow average API response time per customer to detect slow connections or technical issues.
- **Identify key markets:** discover which destinations and source nationalities drive demand, and how value differs between them.
- **Evaluate properties:** find top-performing hotels by booking share, average booking value, and average daily rate.
- **Learn booking behavior:** understand how long guests stay and how far in advance they book, to support pricing, inventory, and marketing decisions.
- **Support decision-making:** gather everything in one place with interactive filters and drill-down, replacing manual reports.

## 🗂️ Dashboard Pages

| Page | Purpose |
|------|---------|
| **Overview** | KPI cards, monthly bookings & sales comparison, length of stay, and lead time analysis |
| **Customers** | Bookings, booking share, requests, look-to-book, and response time per customer |
| **Country** | Booking share, ABV, and ADR by destination country |
| **Province** | Regional drill-down within each country |
| **Nationality** | Guest source markets with booking share, ABV, and ADR |
| **Accommodation** | Hotel-level performance by property |

## 📐 Key Metrics

| Metric | Description |
|--------|-------------|
| **Bookings** | Total number of bookings |
| **Sales** | Total sales value |
| **%Customer Bookings** | Share of a customer / country / hotel in total bookings |
| **Requests** | Total search requests sent by each customer |
| **L2B (Look-to-Book)** | Ratio of search requests to actual bookings |
| **AVG Response Time** | Average API response time per customer |
| **ABV** | Average Booking Value |
| **ADR** | Average Daily Rate |
| **LOS** | Length of Stay |
| **Lead Time** | Time between booking date and check-in |

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design & visualization |
| DAX | Measures and calculations |
| Power Query (M) | Data cleaning & transformation |
| `[MySQL]` | Data source |

## 🗄️ Data Source

The dashboard connects directly to a relational database containing bookings, customers, geography, and accommodation data, modeled as a star schema with fact and dimension tables.

> ⚠️ Connection details and real data are **not** included in this repository.

## 📂 Repository Structure

```
├── Customers_Analysis_Report.pbix    # Power BI file
├── images/                           # Dashboard screenshots
├── sql/                              # SQL scripts / schema (optional)
└── README.md
```

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/[repo-name].git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Go to **Transform Data → Data Source Settings** and enter your own server and database details.
4. Click **Refresh** to load the data.

## 👤 Author

**[Your Name]**
- LinkedIn: [your-linkedin-link]
- GitHub: [@your-username](https://github.com/your-username)
- Email: [your-email]

---

⭐ If you find this project useful, feel free to give it a star!
