import pandas as pd
import plotly.express as px

# Create a Pandas DataFrame with the data
df = pd.DataFrame({
    "Country": ["CAN", "USA", "MEX"],
    "Population": [38005238, 331900000, 128932753]
})

# Create a Plotly map
fig = px.choropleth(df, locations="Country", color="Population",
                    scope="north america",
                    color_continuous_scale="Viridis",
                    locationmode='ISO-3')

# Display the map
fig.show()
