🚌 LA 2028 Sustainable Transit Optimization

This repository contains the datasets, notebooks, and distance matrices used to model and optimize sustainable public transportation routes for the Los Angeles 2028 Olympics. The focus is on reducing car dependency and improving bus transit planning to ensure smooth mobility during the Games, in alignment with the “No Car Games” policy.

📂 Repository Structure

🔧 Main Notebooks
	•	FLP_1_Leo.ipynb / FLP_2_Clara.ipynb: Facility Location Problem models exploring optimal terminal placement.
	•	VRP1.0.ipynb / VRP2.0.ipynb: Vehicle Routing Problem models for optimizing bus routes to and from accommodations and venues.
	•	data cleaning.ipynb: Preprocessing and preparation of raw datasets.
	•	venues_merging.ipynb: Script to merge and clean venue data.

📁 Folders
	•	datasets/: Additional Data.
	•	matrixes/: Precomputed distance/time matrices used in the optimization models, and how have been computed.
	•	Legacy/: Deprecated or older versions of scripts and data.

📄 Key CSV Files
	•	new_matrix.csv: Main distance/time matrix (in seconds) used for routing.
	•	bus_terminals.csv: List and metadata of all bus terminals.
	•	bus_divisions_cleaned_capacity.csv: Cleaned capacity data for bus divisions.
	•	accomodations.csv / hotels.csv: Accommodation locations and capacities.
	•	updated_venues.csv / venues.csv: Lists of Olympic venues.
	•	clusters_central_location.csv: Clustered central points of accommodation zones.
	•	Metro.csv: Metro network data.

🚀 Objective

Design a temporary, optimized bus network that:
	•	Starts and ends each route at a terminal (B- prefix).
	•	Minimizes route duration (≤ 2 hours).
	•	Serves both accommodation clusters and Olympic venues.
	•	Balances load and coverage across multiple depots.

🛠️ Tools & Libraries
	•	Python (3.8+)
	•	Google OR-Tools for optimization
	•	Pandas & NumPy for data manipulation
	•	Jupyter Notebooks for development and experimentation

📈 Outputs
	•	Optimal facility placement (FLP)
	•	Bus route planning (VRP)
	•	Route maps and descriptive statistics
