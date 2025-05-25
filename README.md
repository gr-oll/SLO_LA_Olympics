# 🚌 LA 2028 Sustainable Transit Optimization

This repository contains datasets, notebooks, and distance matrices to model and optimize sustainable public transportation routes for the Los Angeles 2028 Olympics. The focus is on reducing car dependency and improving bus transit planning to ensure smooth mobility during the Games, in alignment with the "No Car Games" policy.

## 📂 Repository Structure

### 🔧 Main Notebooks
- **FLP_1_Leo.ipynb / FLP_2_Clara.ipynb**: Facility Location Problem models exploring optimal terminal placement.
- **VRP1.0.ipynb / VRP2.0.ipynb**: Vehicle Routing Problem models for optimizing bus routes to and from accommodations and venues.
- **data_cleaning.ipynb**: Preprocessing and preparation of raw datasets.
- **venues_merging.ipynb**: Script to merge and clean venue data.

### 📁 Folders
- **datasets/**: Contains additional data files, including accommodations, venues, and bus terminal data.
- **matrixes/**: Precomputed distance/time matrices used in the optimization models, along with computation details. The `new_matrix.csv` file is the final matrix used for routing.
- **Legacy/**: Deprecated or older versions of scripts and data.

### 📄 Key CSV Files
- **new_matrix.csv**: Final distance/time matrix (in seconds) used for routing.
- **bus_terminals.csv**: List and metadata of all bus terminals.
- **bus_divisions_cleaned_capacity.csv**: Cleaned capacity data for bus divisions.
- **accomodations.csv / hotels.csv**: Accommodation locations and capacities.
- **updated_venues.csv / venues.csv**: Lists of Olympic venues.
- **clusters_central_location.csv**: Clustered central points of accommodation zones.
- **Metro.csv**: Metro network data.

## 🚀 Objective

Design a temporary, optimized bus network that:
- Starts and ends each route at a terminal (B- prefix).
- Minimizes route duration (≤ 2 hours).
- Serves both accommodation clusters and Olympic venues.
- Balances load and coverage across multiple depots.

## 🛠️ Tools & Libraries

- **Python (3.8+)**
- **Google OR-Tools**: For optimization.
- **Pandas & NumPy**: For data manipulation.
- **Jupyter Notebooks**: For development and experimentation.

## 📈 Outputs

- **Optimal Facility Placement (FLP)**: Identifies the best locations for bus terminals.
- **Bus Route Planning (VRP)**: Optimized routes for buses to serve accommodations and venues.
- **Route Maps and Descriptive Statistics**: Visualizations and insights into the optimized network.

## 🌟 Highlights

- **Sustainability Focus**: Aligns with the "No Car Games" policy to reduce carbon emissions.
- **Scalability**: Models can be adapted for other large-scale events.
- **Data-Driven Decisions**: Utilizes real-world data for accurate and actionable insights.


## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements or suggestions.
