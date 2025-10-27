# On_line Gaming Insight
# 📊 Power BI Dashboard: Gaming Player Behavior & Monetization Insights

# 1. Executive Summary & Dashboard Objective

Live Dashboard Link: https://app.powerbi.com/links/EqQUF5W8Qz?ctid=a4879b4c-e3d0-4db9-a4e6-2c806df65037&pbi_source=linkShare

This Power BI dashboard provides an interactive view of the gaming player base, focusing on key metrics that drive user acquisition (UA), retention, and monetization strategy.

The dashboard's core value lies in its Game Genre Filter. By segmenting the data, stakeholders can immediately compare the performance, habits, and monetization effectiveness of different player cohorts.

# 🎯 Key Performance Indicators (KPIs)

The dashboard features three primary KPI cards providing instant business context:

KPI Metric Strategic Importance

Total Players	Market Reach: Measures the total size of the player base for scaling and acquisition planning.

In-Game Purchase %	Monetization: The percentage of the player base that converts to paying users—a vital metric for Lifetime Value.

Average Playtime Hours	Engagement Depth: Indicates the overall time commitment, which is crucial for retention and advertising inventory.

# 2. Core Strategic Insights

The following insights are derived from filtering the data by Game Genre, providing immediate direction for content and marketing teams:

# A. Acquisition & Market Strategy

●	Game genre Dominance: Sports is the most successful game genre by volume, consistently attracting the highest count of players. This suggests a powerful market fit that should be leveraged.

●	Gender Skew: The player base exhibits a distinct demographic tilt, with Male Players consistently out numbering Female Players. This requires targeted advertising creatives and feature development to address the dominant audience while identifying opportunities to broaden appeal.

●	Geographic Focus: The Distribution of Players by Location confirms the USA as the primary market, validating current geo-targeting strategies and providing a benchmark for international expansion.

# B. Game Design & Retention

●	Universal Accessibility: Across all game genre types, 'Easy' is reported as the most common game difficulty level. This is a critical finding: players overwhelmingly prefer accessible experiences. Future content should prioritize onboarding and early-game success over steep difficulty curves to minimize early churn.

●	Critical Habit Finding (sessions): The visual comparing Sessions Per Week vs. Engagement Level reveals a non-linear trend: the Medium Engagement level cohort logs the highest average number of sessions per week (surpassing the High group). This indicate the most habitual players are currently categorized as ‘Medium’.
We analyze the boundary between Medium and High to determine what key milestone or incentive is missing that prevents these highly frequent players from graduating to the ‘High’ status

●	Complex Progression (Playtime vs Level): The Correlation between Playtime and Player Level shows a nuanced relationship rather than a simpler linear one. Specifically, I observed some high-level players with surprisingly low playtime and some low-level players with unusually high playtime.
This suggests progression is not purely time-based. Leveling must be influenced by other factors (skill, efficiency, or potentially in-game purchases). Design teams should investigate if the progression system is too easily bypassed or if there is a population of dedicated, but inefficient, players who need feature guidance.

# C. Monetization Efficiency

●	Genre Purchase Parity: Unexpectedly, the Simulation and Sports genres exhibit the exact same In-Game Purchase Percentage. This is a powerful insight. While Sports has more players, Simulation's monetization mechanics are just as effective on a per-player basis. This suggests a high-yield opportunity to scale the Simulation genre's content and marketing.

●	Duration Value: The Relationship between AVG Session Duration and Player Level shows that some higher-level players does not have longer session durations. This ties player loyalty to ad inventory value and feature consumption, justifying investment in all-level content.

# 3. How to Interact with the Dashboard

The dashboard is designed for self-service analysis.

The Game Genre Slicer

●	Function: The single, most powerful interactive tool on the report.

●	Use Case: Use the slicer to select any single genre (e.g., "Strategy") to see how its unique player population changes all 6 primary visuals and the 3 KPIs simultaneously.

●	Scenario Example: Select "Simulation" to see its Purchase Percentage, then quickly select "Sports" to visually confirm the percentage parity while noting the vast difference in the Total Players KPI.

# 4. Modeling & Data Integrity

The report is powered by a single, optimized Fact Table sourced directly from the provided gaming dataset.

This modeling approach ensures that every slicer and filter maintains full relational integrity, guaranteeing that all measures (like the In-Game Purchase %) are dynamically recalculated based on the specific player subset you are viewing. This eliminates the "modeling errors" associated with using pre-aggregated tables.

