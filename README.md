# YOUTUBE-ANALYTICS
Analyzed 339K+ YouTube trending videos and 478K+ comments (Python, Pandas, NLTK, Plotly) to study sentiment, emoji trends, and category performance; built an engagement-rate metric showing viral videos average only 4.2% audience engagement, and visualized results via interactive dashboards, exporting data to CSV/JSON/SQLite.
HIGHLIGHTS :
Cleaned and merged multi-country YouTube trending data (339,525 records) and 478,707 user comments using Pandas
Performed sentiment analysis on user comments with NLTK's VADER model to classify audience response polarity
Extracted and ranked emoji usage trends across comments (top: 😂 27.2K, ❤️ 22.1K, 😍 22.1K) using the emoji library
Engineered an engagement-rate metric (likes + comments)/views to test whether high-view videos truly drove audience interaction — found average engagement of only 4.2% despite Music generating 220B+ views
Identified category-level view/engagement trends (Music, Entertainment, Film & Animation led views; Howto & Style, Science & Tech led engagement)
Built interactive Plotly visualizations (bubble, treemap, area, box plots) and exported processed data to CSV, JSON, and SQLite via SQLAlchemy
