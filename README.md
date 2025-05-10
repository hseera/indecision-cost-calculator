# 🕰️ Indecision Cost Calculator

**Estimate the hidden cost of indecision in meetings.**  
This simple, interactive web app calculates the financial impact of delayed decisions by estimating time and salary wastage in meetings.

![screenshot](https://github.com/hseera/indecision-cost-calculator/blob/main/assets/indecision.png) 
## 🔍 Features

- 🎚 Adjustable parameters: number of attendees, hourly rates, and meeting duration
- 💸 Instant calculation of minimum, maximum, and average cost of indecision
- 📈 Real-time trend charts to visualize cumulative costs over time
- 🗂 Tabbed interface to switch between **Enterprise** and **Greenfield** project graphs
- ⚠️ Input validation to ensure Min Daily Rate is not more than Max Daily Rate
- 🧹 Reset button to clear historical data
- 📱 Responsive and clean UI – works well on desktop

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/indecision-cost.git
cd indecision-cost
```

### 2. Open in Browser

Just open the `indecision-cost-tabs-final-with-validation.html` file in any modern browser:

```bash
open indecision-cost-tabs-final-with-validation.html
```

Or double-click the file in your file explorer.

> No build tools or dependencies required. Pure HTML, CSS, and JavaScript!

## 🧠 How It Works

The app assumes each participant in a meeting has a daily rate. Based on the meeting length and number of attendees, it estimates a range of costs for the wasted time if a decision isn’t made efficiently.

```text
Hourly Rate = Daily Rate / 8
Cost = Hourly Rate × Meeting Duration × Number of People
```

It plots these estimates over time per project type so teams can track ongoing costs of indecision.

## 📊 Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for dynamic graphing

## ✨ Use Cases

- Product/Engineering meetings with slow decision-making
- Retrospectives or post-mortems to assess meeting efficiency
- Budget-conscious teams tracking value loss over time
- Comparing decision-making efficiency between project types (e.g., Enterprise vs. Greenfield)


## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

