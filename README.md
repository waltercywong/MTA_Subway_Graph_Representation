# MTA_Subway_Graph_Representation

## Purpose

The MTA transit system is an expansive subway system that connects the boroughs 
of New York City. The code in `representation.ipynb` creates a graph 
representation of the subway system and its rider traffic, along with some 
queries that are useful for analysis and solving problems regarding optimizing 
riders' experience.

## Data

### MTA Station Dataset

This dataset contains information about each individual station complex, including features like a unique ID, borough, coordinates, line information, and station structure type.

Full description: https://data.ny.gov/Transportation/MTA-Subway-Stations/39hk-dx4f/about_data

### MTA Ridership Dataset

This dataset contains information about ridership across different days, times, origin, and destination stations.

Full description: https://data.ny.gov/Transportation/MTA-Subway-Origin-Destination-Ridership-Estimate-2/jsu2-fbtj/about_data

## Setup Instructions

### Step 1: Clone the Repository

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/waltercywong/MTA_Subway_Graph_Representation
cd MTA_Subway_Graph_Representation
```

### Step 2: Download Required Files

Download the MTA ridership data at the following Google Drive link:

https://drive.google.com/drive/folders/1fV47SWGv5_AFPR_gRfvK1ra1LfSFCgOw

Place the downloaded csv file into the `data` folder.

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Notebook

Run code cells in `representation.ipynb` to create representation and query network. Markdown files with annotations explain data, graph schema, and queries.


## File Structure

- `README.md`: Overview and instructions for the project.
- `requirements.txt`: List of Python dependencies required for the project.
- `data/`: Contains datasets used or produced by the project.
- `docs/`: Additional documentation and resources.
- `src/`: Main source code for the project.