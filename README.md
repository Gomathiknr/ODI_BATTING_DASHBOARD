# ODI Batting Dashboard (1972-2022)

This project includes the implementation of an ODI batting dashboard using Looker for analyzing player statistics in One Day International matches from 1972 to 2022. The dashboard provides various metrics on batting performance, such as total runs, batting average, centuries, and fifties across different time periods, players, and countries.

## Features

- **Total Runs**: Visualize top run-scorers in ODI history.
- **Batting Average**: Trend analysis of batting average for players over time.
- **Centuries & Fifties**: Comparison of players based on their centuries and fifties.
- **Player Comparison**: Compare batting stats between players.
- **Filters**: 
  - Filter by year (1972-2022).
  - Filter by player.
  - Filter by country.
  
## Data Source

The dataset consists of player performance data from all ODI matches played between 1972 and 2022. It includes the following information:

- Player ID
- Player Name
- Runs Scored
- Balls Faced
- Matches Played
- Centuries
- Fifties
- Date of Match
- Match Type (e.g., ICC tournaments, bilateral series)

## Setup

### Prerequisites

- Looker Account
- Access to the dataset (CSV, JSON, or SQL Database)

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/odi-batting-dashboard.git
    ```

2. Set up the LookML project in your Looker instance.

3. Upload the dataset to your Looker environment, or connect to the database where the dataset resides.

4. Define the views and explores as per the provided LookML files.

5. Create the dashboard in Looker by adding the various charts and tables.

6. Customize filters (year, player, country) to refine the analysis.

## Usage

Once the dashboard is set up, users can explore various metrics by interacting with the filters and visualizations. You can:

- View the total runs scored by players over time.
- Analyze the batting average of players.
- Filter stats based on years, players, or countries.
- Compare the batting performance of multiple players.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset was collected from publicly available ODI cricket match data.
- Special thanks to Looker for providing the platform to build this dashboard.

