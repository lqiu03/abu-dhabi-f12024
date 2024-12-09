# abu-dhabi-f12024
**McLaren Racing &amp; Scuderia Ferrari Head to Head | F1 Constructor Championship in numbers**

# McLaren vs. Ferrari: Constructor Points Battle

This repository visualizes the season-long battle between the McLaren and Ferrari Formula 1 teams, culminating in the final race of the year. We use real F1 race data (via the open-source [FastF1](https://theoehrly.github.io/Fast-F1/) API) to chart how both teams’ points have evolved from the start of the season to the end.

## Racing Terms

- **Constructor:** In Formula 1, a constructor is essentially the team that builds the car. Each constructor fields two cars (drivers) in each race, and points scored by both drivers count toward the constructor’s total.
- **Points:** Points are awarded to the top finishers in each Grand Prix. The standard scoring system grants points to the top 10 positions (25 for 1st, 18 for 2nd, etc.), accumulating over the season.
- **Cumulative Points:** By adding points earned from each race, we track how the teams’ totals grow, giving us a clear picture of performance trends throughout the season.

## Python Libraries Used

- **FastF1:** Fetches race session data, including positions, teams, drivers, and timing info.
- **Matplotlib & Seaborn:** For creating visually appealing and insightful charts.
- **NumPy & Pandas:** For handling numerical computations and dataset manipulation.

## Context: The McLaren vs. Ferrari Duel

Throughout the season, McLaren and Ferrari have been locked in a fierce contest for a top spot in the constructors’ standings. Both have seen peaks and troughs—some races favored McLaren’s consistent scoring, while others saw Ferrari’s drivers pushing them back. By the final race, the points difference is razor-thin, making this showdown a compelling narrative for F1 fans and data enthusiasts alike.

## Data Source

All race data used in this project is retrieved from the publicly available FastF1 API, which uses official F1 data under open-source conditions. 
