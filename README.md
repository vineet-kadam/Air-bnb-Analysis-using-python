# Air bnb Data analysis Chatbot

Interactive Python chatbot for analyzing hotel booking data from `cleaned_air.csv`. Ask 10 predefined questions or request visualizations using simple keywords like "bar", "hist", "scatter".

## ✨ Features

- **10 Statistical Questions**: Basic stats, top hotels, averages, distributions
- **Interactive Visualizations**: Bar charts, histograms, scatter plots
- **Pandas + Seaborn + Matplotlib**: Professional data analysis & plotting
- **Beginner-friendly**: Simple number inputs (1-10) or keywords
- **Real CSV Support**: Loads your `cleaned_air.csv` file directly

## 📊 10 Questions Available

```
1. Dataset statistics     5. Superhost prices
2. Top 10 hotels          6. Stars vs price correlation
3. Avg price by city      7. Guests by room type
4. Room types count       8. Hotels by city
9. Price histogram        10. Exit
```

## 🚀 Quick Demo

```
Type: 2 → Top 10 hotels table
Type: "top hotel bar" → Bar chart
Type: "price hist" → Price histogram
Type: "scatter" → Stars vs Price scatter
```

## 📁 File Structure

```
hotel-chatbot/
├── cleaned_air.csv     # Your hotel data (11 columns)
├── hotel_chatbot.py    # Main script
└── README.md          # This file
```

## 🛠️ Tech Stack

```
pandas     # Data manipulation
numpy      # Numerical operations
matplotlib # Basic plotting
seaborn    # Statistical visualizations
```

## 🎯 How to Run

1. Place `cleaned_air.csv` in same folder
2. Run: `python hotel_chatbot.py`
3. Type `1-10` or plot keywords
4. Press `10` to exit

## 🔮 Example Outputs

**Question 2**: Top 10 hotels table with name, stars, price  
**"top hotel bar"**: Bar chart of top 10 hotels by stars  
**"price hist"**: Price distribution histogram

## 🎓 Perfect For

- Data analysis interviews
- Hotel booking EDA projects
- Learning pandas + visualization
- Interactive data exploration demos

**⭐ Star this repo if you find it useful!**  
**📈 Built for beginners, loved by data analysts**[11]
