# StrideStats 🏃‍♂️📊

![StrideStats Logo](logo.webp)

**StrideStats** is a web application designed to visualize relay race results from past events. It provides users with detailed analytics on team and individual performances, offering insights into trends and statistics. The app is built using **React** and deployed on **GitHub Pages**.

## 🚀 Features

- 📊 **Historical Relay Data** – Explore past relay race results.
- 📈 **Performance Analytics** – Visualize trends and statistics over time.
- 🔄 **Team & Individual Insights** – Compare different teams and athletes.
- 🖥 **Interactive Charts** – Engage with dynamic data visualizations.
- 🌍 **Web-Based & Static** – No data uploads, just a seamless viewing experience.

## 🛠️ Tech Stack

- **Frontend:** React
- **Deployment:** GitHub Pages

## 📦 Installation & Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/stridestats.git
   cd stridestats
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   npm start
   ```

4. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## 🚀 Deployment on GitHub Pages

1. Build the project:

   ```sh
   npm run build
   ```

2. Deploy to GitHub Pages:

   ```sh
   npm run deploy
   ```

3. The app will be available at:

   ```
   https://your-username.github.io/stridestats/
   ```

## 🎯 Usage

1. **Browse Relay Results** – Explore past relay events and view performance data.
2. **Analyze Trends** – Compare different years, teams, and runners.
3. **Interactive Visualizations** – Engage with dynamic charts and relay simulations for deeper insights.

## 🏗️ Future Enhancements

- Additional filtering options for results.
- Mobile-friendly UI improvements.
- More detailed athlete performance breakdowns.

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to your branch: `git push origin feature-name`
5. Open a pull request.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

🔗 **StrideStats – Bringing Relay History to Life!** 🏃‍♀️📊🏆

### Changes & Improvements:
- The app now focuses on **historical relay results** rather than user uploads.
- **Deployment method** updated to **GitHub Pages**.
- **Tech stack** simplified to just React.
- **Usage & features** refined to match a static data visualization app.
- **GitHub Pages deployment steps** added.
- **Updated 22/04/2025**: Added 25t1 data. Fixed several bugs: event number was calculated incorrectly for year > 24; new pb shouldnt show if latest result == past pb; fixed incorrect 25t1 data (wrong positions, duplicate name needing a custom change)
- **Updated 03/05/2025**: added pace in km/hr and min/km in relay results and player; fixed bug in group in players where all players were the same group;replace volunteers in Results page with distance
- **Updated 05/08/2025**: Added 25t2 data. Some players ran a discrepancy of laps that did not match 4. I applied Riegel's Model taking k = 1.2 for Jackie Tran, Sabrina and Heejae and k = 1.0 for Will to approximate their 4 lap results.