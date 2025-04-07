# 📊 Twitter Activity Analysis with Power BI

This project provides an exploratory data analysis of a Twitter dataset using Power BI. It aims to visualize user behavior, tweet patterns, and message types from a structured dataset, showcasing how simple transformations and visuals can bring out key trends in social media data.

## 📁 Dataset

The dataset includes the following key columns:
- `author_id`: Unique identifier of the Twitter user.
- `created_at`: Timestamp of the tweet.
- `text`: Content of the tweet.
- `tweet_id`: Unique tweet ID.
- `response_tweet_id`: ID of the tweet being responded to (if any).
- `inbound`, `inresponseto`: Message directionality.
- Parsed columns added during cleaning: `parsed_date`, `hour`, `Day of week`, `month`, `time`.

## 🛠️ Tools Used
- **Power BI**: Data transformation, visualization
- **Power Query**: Date-time parsing and feature extraction
- **Microsoft Excel**: Exporting charts and final analysis
- **CSV**: Raw data format

## 📈 Visualizations

1. **Tweet Volume by Hour** *(Line Chart)*
   - **X-axis**: Hour of the day (0–23)
   - **Y-axis**: Number of tweets

2. **Tweet Volume by Hour and Type** *(Clustered Column Chart)*
   - **X-axis**: Hour of the day
   - **Y-axis**: Number of tweets
   - **Legend**: Tweet Type (Inbound / Outbound)

3. **Tweet Volume by User** *(Bar Chart)*
   - **X-axis**: Author ID (Top 10)
   - **Y-axis**: Number of tweets

4. **Tweet Distribution by Type** *(Donut Chart)*
   - Shows proportions of Inbound vs Outbound messages.

## 📄 Outputs

- **CSV**: Cleaned and transformed dataset.
- **PDF Report**: Visual summary of all insights generated using Power BI.

## 🚀 Getting Started

1. Clone this repository or download the files.
2. Open Power BI Desktop.
3. Load the `Tweet.csv` file.
4. Use the `Transform Data` panel to parse and create new time-based fields.
5. Recreate the visuals or refer to the Power BI report/PDF.

## ✅ Future Improvements

- Incorporate sentiment analysis using Python.
- Add language and device metadata if available.
- Automate refresh using Power BI service.

---

**Author**: Abhay Rajesh  
📧 abhay_rajesh@outlook.com  
