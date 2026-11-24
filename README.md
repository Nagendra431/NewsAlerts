# NewsAlerts – Automated Financial News Alert System

**An intelligent financial news monitoring and personalized email notification system built using UiPath RPA.**

## 📌 Project Overview

NewsAlerts is a Robotic Process Automation (RPA) project developed using UiPath to automate financial news monitoring and deliver relevant news updates to subscribers.

The automation collects financial news from RSS feeds, identifies articles based on subscriber interests, tracks previously processed articles, and sends personalized email notifications.

The goal is to reduce manual news monitoring and help subscribers stay updated with important financial market information.

## 🚀 Key Features

- **Automated News Monitoring:** Collects financial news from configured RSS feeds.
- **Interest-Based Filtering:** Identifies news relevant to subscriber preferences.
- **Financial Market Coverage:** Supports topics such as Gold (XAUUSD), Bank Nifty, and Forex.
- **Personalized Email Alerts:** Sends relevant news notifications to subscribers.
- **Duplicate Prevention:** Tracks previously processed articles to avoid repeated alerts.
- **Excel Integration:** Uses Excel files to manage subscribers, news sources, settings, and processing records.
- **Audit Logging:** Maintains processing and delivery information for tracking.

## ⚙️ Technologies Used

- UiPath Studio
- Robotic Process Automation (RPA)
- RSS Feeds
- Microsoft Excel
- Email Automation
- XML-based UiPath Workflows (XAML)

## 🔄 How It Works

1. Reads configuration settings and subscriber information from Excel.
2. Retrieves financial news from configured RSS sources.
3. Extracts and processes news articles.
4. Matches articles against subscriber interests.
5. Checks processed article records to prevent duplicate notifications.
6. Sends relevant news alerts through email.
7. Updates processing and delivery logs.

## 📁 Project Structure

```text
NewsAlerts/
│
├── Data/
│   ├── AuditLog.xlsx
│   ├── DeliveryLog.xlsx
│   ├── NewsSources.xlsx
│   ├── ProcessedArticles.xlsx
│   ├── Settings.xlsx
│   └── Subscribers.xlsx
│
├── Main.xaml
├── project.json
├── project.uiproj
├── WORKFLOW_REPAIR_NOTES.md
├── README.md
└── .gitignore
```

## ▶️ How to Run

1. Install **UiPath Studio**.
2. Clone or download this repository.
3. Open the project using UiPath Studio.
4. Verify the Excel files and RSS source configurations in the `Data` folder.
5. Configure the required email settings.
6. Open `Main.xaml`.
7. Run the automation.

## 🎯 Project Objective

To demonstrate how Robotic Process Automation can simplify financial news monitoring, automate repetitive tasks, process structured data, and deliver personalized information efficiently.

## 👨‍💻 Developer

**M. Nagendra Prasad**

GitHub: [Nagendra431](https://github.com/Nagendra431)

---

⭐ If you find this project interesting, feel free to explore the repository.
