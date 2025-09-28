📊 Netflix 1990s Movie Analysis
🔎 Overview

This project uses Netflix movie data to explore trends in movies released during the 1990s (1990–1999).
The goal is to answer two simple questions:

What was the most common movie duration in the 1990s?

How many short action movies (less than 90 minutes) were released in that decade?

Even if you don’t know coding, this README explains the logic and findings in plain language.

🗂️ Dataset

The analysis is based on netflix_data.csv, which contains:

type – Movie or TV Show

title – Name of the show

director / cast / country – Basic production details

release_year – Year the movie/show was released

duration – Movie length in minutes

genre – Main genre (Action, Comedy, etc.)

⚙️ Steps Performed

Filter the data to include only movies (not TV shows).

Select movies released between 1990 and 1999.

Visualize movie durations to find the most frequent length.

Filter Action movies and count how many are short (<90 min).

🧮 Key Results
Question	                               Answer
Most frequent movie duration (approx.)	100 minutes
Number of short Action movies (< 90 min)	(calculated value stored in short_movie_count)

(Values may vary slightly if the dataset updates.)

💻 Tools Used

Python (pandas, numpy, matplotlib) – For data filtering, counting, and visualization.

Jupyter Notebook – To write code and display graphs step by step.

📂 Repository Contents

netflix_data.csv – Original dataset.

netflix_1990s_analysis.ipynb – Python notebook with code and graphs.

README.md – This explanation file.
