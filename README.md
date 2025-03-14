# SoccerSight Visualiza: Visual Analytics of Soccer Player Performance

# Introduction

SoccerSight Visualiza is a visual analytics system designed to evaluate soccer player performance using an objective rating system based on data-driven metrics. This project builds upon and extends the work presented by Evers et al., introducing advanced visualization techniques to provide detailed player performance analysis.

The system computes ratings for various performance aspects, including passes, duels, and shots, offering valuable insights for coaches, scouts, and analysts. Users can interactively adjust parameter weights, compare players, and analyze individual events through an intuitive dashboard.
![Alt text](https://github.com/priyaavijay/SoccerViz/blob/main/Soccer%20Visualization%20Dashboard.png)
# Visualization Techniques & Modules

# Radar Chart

Enables users to assign and adjust weights for passes, duels, and shots.

Generates an overall performance score.

Interactive axis adjustments and a reset button for ease of use.

# Bar Chart

Displays comparative ratings for all players in a selected match.

Highlights the selected player's rating in a distinct color based on user-defined weights.

# Parallel Coordinates Plot

Visualizes relationships between weighted parameters across matches.

Users can toggle axes to focus on specific performance metrics.

# Line Chart

Tracks a selected player's performance ratings across all matches in a tournament.

Helps identify performance trends over time.

# Heat Map (Two Types)

Player Presence Heatmap: Visualizes field density over time.

Defensive Pressure Heatmap: Highlights opposition pressure on the selected player.

Interactions

Dropdown menus for selecting tournament, season, match, and player.

Weight adjustments, hover tooltips, toggle buttons, and timestamp sliders for seamless user interaction.

# Results & Insights

The dashboard enhances player performance analysis by integrating novel visualization techniques.

Performance trend charts help track player patterns across a tournament, providing actionable insights.

# Use Case Example:

A coach selects a tournament, season, match, and player.

The radar chart highlights strengths and weaknesses.

The bar chart facilitates comparisons with other players.

The parallel coordinate plot shows metric dependencies and player involvement.

The line chart reveals performance trends, aiding in decision-making.

The heatmaps highlight spatial movement patterns and defensive pressures.

The new visualization capabilities improve usability and analytical depth, ensuring intuitive narrative flow for users unfamiliar with advanced soccer analytics tools.

# Dataset: StatsBomb Open Data (https://github.com/statsbomb/open-data)

Contains tournament, match, and player data essential for rating calculations.

Includes parameters such as passes, duels, shots, timestamps, and spatial data for player movements.

Provides player positions and timestamps for heatmap generation.

# Data Preprocessing

Data cleaning and structuring in the backend ensures accurate and efficient metric calculations.

Preprocessed data is stored and used for visualization representation.
