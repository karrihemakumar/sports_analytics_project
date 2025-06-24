# Cricket Player Form & Worth Prediction
This project presents a data-driven application that predicts the form and estimated market worth of cricket players based on their historical performance data. Using a dataset spanning IPL cricket matches from 2008 to 2023, the system analyzes player-level trends centered around "Player of the Match" awards — a strong indicator of standout performance.

The core idea revolves around calculating a form score that captures:

The total number of "Player of the Match" awards a player has received.

The recency of these awards — recent performance is weighted more.

A decay function that penalizes long gaps since the last award.

The application also includes a machine learning–inspired heuristic that predicts:

Future form using time-based decay and reward trends.

Estimated monetary worth, derived from the predicted form and scaled using domain knowledge assumptions.

The frontend is built using Streamlit, providing an interactive dashboard where users can:

Select a player and view detailed metrics (form score, days since last award, total awards).

See predicted form and worth values.

View a bar chart of the top 10 players by predicted form for quick comparison.

 Results / Outcomes:
 The model successfully ranks players based on their projected future form, helping fans, analysts, or fantasy league participants understand current form dynamics.

 Estimated worth predictions add a commercial insight dimension to player performance.

 Visual analysis reveals consistent high-performing players and rising stars.

 The interactive dashboard offers an accessible way to explore the model’s predictions for over 100 players from historical IPL data.
