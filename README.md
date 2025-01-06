# vext_titanic_streamlit_app

# Vext Titanic Query Interface

This Streamlit app allows users to query the Titanic dataset via a custom API. Users can input natural language queries to retrieve insights or visualizations related to the Titanic dataset.

## Features
- User-friendly query interface for the Titanic dataset.
- Connects to a custom API to process user queries.
- Executes Python code (if returned by the API) and displays visualizations.
- Handles error scenarios gracefully, ensuring a smooth user experience.

## How It Works
1. Users enter a query about the Titanic dataset (e.g., "What is the distribution of male and female survivors?").
2. The app sends the query to a specified API.
3. The API processes the query and may return a text response or Python code for data visualization.
4. If Python code is included in the response, the app executes it and displays the resulting output or plot.

## Technologies Used
- **Streamlit**: For building the user interface.
- **Python**: Core programming language.
- **Requests**: For making API calls.
- **Matplotlib** and **Seaborn**: For visualizations.
- **Pandas**: For data manipulation.

## How to Use
### Online Version
Access the hosted app here: [Streamlit App Link](#)  
(*Replace `#` with the actual link after deployment.*)

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Titanic-Streamlit-App.git
   cd Titanic-Streamlit-App
