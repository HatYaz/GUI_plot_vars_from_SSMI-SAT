# GUI_plot_vars_from_SSMI-SAT
Plot Satellite Variables from Special Sensor Microwave/Imager

This Python script provides a GUI to download and visualize satellite data. Key components include:

1. **GUI for Inputs**: 
   - Allows the user to select the year, month, latitude, longitude, radius, variable, and save directory.
   - Includes buttons for browsing the save directory and running the script.

2. **Data Download**:
   - Fetches data from the NOAA SSMI/SSMIS Hydrological Products API based on the selected year, month, and variable.
   
3. **Bounding Box Calculation**:
   - Computes a bounding box around the specified coordinates with a given radius (in kilometers).

4. **Data Plotting**:
   - Extracts data from the downloaded NetCDF file and visualizes the selected variable using `matplotlib` and `cartopy`.
   - The map includes a black cross marker at the specified latitude and longitude.

5. **Visualization**:
   - Displays a plot of the variable with the corresponding data, including a color bar and map features (land, coastline).

### Key Features:
- Select year, month, latitude, longitude, and radius.
- Choose from a list of variables (e.g., cloud fraction, sea ice cover, rainfall).
- Download and plot the data directly.
- Interactive map and plot generation using `matplotlib` and `cartopy`.

This tool is ideal for analyzing satellite data for various environmental variables over specific geographic areas.
