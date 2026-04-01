
🎧 Spotify Listening Behavior Analysis

⸻

📌 Business Problem

Music streaming platforms like Spotify operate in a highly competitive environment where user engagement and retention are critical.

However, key questions remain:
	•	Do users follow trends or personal taste?
	•	What time patterns drive engagement?
	•	Are popular tracks actually driving listening time?
	•	How concentrated is listening across artists and tracks?

👉 Without understanding these patterns, platforms risk:
	•	Weak recommendation systems
	•	Lower retention rates
	•	Poor content targeting

⸻

🎯 Objective

To analyze user-level listening behavior and uncover:
	•	Engagement drivers
	•	Temporal listening patterns
	•	Artist & genre preferences
	•	Relationship between popularity vs actual consumption

⸻

🛠️ Tech Stack
	•	Power BI → Dashboard & visualization
	•	KNIME → Data pipeline & preprocessing
	•	Power Query → Data transformation
	•	Excel / CSV → Raw data handling

⸻

⚙️ End-to-End Workflow

🔹 1. Data Collection
	•	Personal Spotify listening dataset
	•	Fields include:
	•	artist_name
	•	track_name
	•	genre
	•	minutes_played
	•	timestamp

⸻

🔹 2. Data Processing (KNIME)
	•	Data ingestion (CSV / JSON)
	•	Cleaning & filtering
	•	Feature engineering:
	•	Time of day buckets
	•	Day & month extraction
	•	Genre mapping
	•	Structured dataset creation

👉 Final dataset prepared for analytics

⸻

🔹 3. Data Modeling (Power BI)
	•	Created relationships between:
	•	Fact table (listening events)
	•	Artist table
	•	Track table
	•	Time dimension

👉 Star-schema style modeling for performance

⸻

🔹 4. Dashboard Development

Multiple analytical views created to analyze behavior from different angles.

⸻

📸 Dashboard Insights

🔹 Overview

	•	43.86K total minutes
	•	4038 unique tracks
	•	248 active listening days
	•	Listening concentrated among top artists

⸻

🔹 Time-Based Analysis

	•	Peak: Morning & Early Afternoon
	•	Low activity: Late night
	•	Stable weekday patterns
	•	Mid-year peak → gradual decline

👉 Indicates habit-driven consumption

⸻

🔹 Artist-Level Analysis

	•	Listening concentrated among a few artists
	•	Strong repeat behavior
	•	Long-tail exploration exists

👉 Shows loyalty + selective discovery

⸻

🔹 Behavioral Insights

	•	Weak correlation between popularity vs listening time
	•	Mid-popularity tracks perform strongly

👉 Users prefer personal taste over mainstream trends

⸻

🔹 Track-Level Analysis

	•	Few tracks dominate total listening
	•	Strong repeat consumption patterns

👉 Indicates high engagement with specific content

⸻

🔹 KNIME Workflow

	•	Modular pipeline design
	•	Separate table creation:
	•	Fact
	•	Artist
	•	Track

👉 Structured data ready for BI analysis

⸻

📊 Key Insights

🔥 Repeat Behavior Dominates

A small number of artists and tracks contribute most of the listening time.

⸻

🔥 Personal Taste > Popularity

Listening behavior does not strongly depend on track popularity.

⸻

🔥 Time Patterns are Predictable

Users follow consistent listening habits aligned with daily routines.

⸻

🔥 Genre Preference is Stable

Clear dominance of specific genres like Melodic House and Electronic.

⸻

🔥 Consumption is Habit-Driven

Behavior remains stable across days and months.

⸻

📦 Data Availability

This project uses a personal dataset, which is not publicly uploaded.

📌 Dataset or sample data can be shared upon request.

⸻

🚀 Business Impact
	•	Improve recommendation systems
	•	Increase user engagement
	•	Optimize notification timing
	•	Enable personalized experiences

⸻

🚀 Future Enhancements
	•	SQL-based analysis layer (to be added)
	•	Recommendation system
	

⸻

📌 Final Takeaway

Listening behavior is preference-driven, consistent, and repeat-focused rather than trend-driven.

