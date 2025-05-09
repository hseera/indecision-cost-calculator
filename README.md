# 🕰️ Indecision Cost Calculator

**Estimate the hidden cost of indecision in meetings.**  
This simple, interactive web app calculates the financial impact of delayed decisions by estimating time and salary wastage in meetings.

![screenshot](https://github.com/hseera/indecision-cost-calculator/blob/main/assets/indecision.png) 

## 🔍 Features

- 🎚 Adjustable parameters: number of attendees, hourly rates, and meeting duration
- 💸 Instant calculation of minimum, maximum, and average cost of indecision
- 📈 Real-time trend chart to visualize cumulative costs over time
- 🧹 Reset button to clear historical data and start fresh
- 📱 Responsive and clean UI – works well on desktop and tablet

## 🚀 Getting Started

### 1. Clone the repo

> git clone https://github.com/hseera/indecision-cost-calculator.git

### 2. Open in Browser

Just open the **indecision-cost.html** file in any modern browser:

Or double-click the file in your file explorer.

> No build tools or dependencies required. Pure HTML, CSS, and JavaScript!

## 🧠 How It Works

The app assumes each participant in a meeting has a daily rate. Based on the meeting length and number of attendees, it estimates a range of costs for the wasted time if a decision isn’t made efficiently.

```
Hourly Rate = Daily Rate / 8
Cost = Hourly Rate × Meeting Duration × Number of Attendees
```

It plots these estimates over time so teams can track ongoing costs of indecision.

## 📊 Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for dynamic graphing

## ✨ Use Cases

- Product/Engineering meetings with slow decision-making
- Retrospectives or post-mortems to assess meeting efficiency
- Budget-conscious teams tracking value loss over time

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.
