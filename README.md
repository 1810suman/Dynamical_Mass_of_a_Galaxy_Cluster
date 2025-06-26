<!DOCTYPE html>
<html lang="en">

<body>

<h1>🌌 Dynamical Mass of a Galaxy Cluster - SDSS Data Analysis</h1>

<p>This project estimates the <b>dynamical mass</b> of a galaxy cluster using <b>observational data from SDSS DR16</b>. The mass estimation follows astrophysical principles, including redshift dispersion and physical size analysis, based on data extracted via SQL queries from the SDSS SkyServer.</p>

<h2>📂 Project Contents</h2>
<ul>
  <li><b>Dynamical_Mass_of_a_Galaxy_Cluster.ipynb</b> - Jupyter Notebook with full calculations, plots, and interpretations</li>
  <li><b>sdss_cluster_data.csv</b> - Contains the SQL script used to extract the galaxy data from SDSS SkyServer</li>
  <li><b>requirements.txt</b> - List of Python dependencies</li>
  <li><b>README.md</b> - Project overview and instructions</li>
</ul>

<h2>🧪 Project Workflow</h2>
<ol>
  <li><b>Data Retrieval:</b> Extract galaxy data around a known cluster candidate using the provided SQL query from SDSS DR16</li>
  <li><b>Cluster Member Identification:</b> Filter galaxies based on redshift proximity using knowledge of typical cluster velocity dispersions</li>
  <li><b>Velocity Dispersion:</b> Compute the characteristic velocity spread (in km/s) of cluster members</li>
  <li><b>Physical Size Estimation:</b> Calculate the cluster's characteristic size in Megaparsecs (Mpc) based on angular separation and redshift</li>
  <li><b>Dynamical Mass Calculation:</b> Estimate total cluster mass using the virial theorem approximation</li>
  <li><b>Interpretations:</b> Compare the calculated dynamical mass with expected luminous mass and discuss any discrepancies, highlighting the role of dark matter</li>
</ol>

<h2>🛰️ SDSS SQL Query (Included)</h2>
<p>The <b>SDSS_Cluster_SQL_Query.txt</b> file provides the exact SQL script to extract necessary galaxy data within a 10-arcminute radius of the specified coordinates:</p>
<ul>
  <li>Center: RA = 258.1294, Dec = 64.0926</li>
  <li>Redshift Range: 0.05 < z < 0.20</li>
  <li>Photometric and spectroscopic details of potential cluster members</li>
</ul>
<p>Visit: <a href="http://skyserver.sdss.org/dr16/en/tools/search/sql.aspx" target="_blank">SDSS SQL Search Tool</a></p>

<h2>📊 Included Visualizations</h2>
<ul>
  <li>Histogram of redshift (velocity) distribution of galaxies</li>
  <li>Angular separation histogram with selected physical size marked</li>
  <li>Scatter plots showing cluster structure and spatial distribution</li>
</ul>

<h2>⚡ Requirements</h2>
<pre>
numpy
matplotlib
pandas
astropy
scipy
</pre>

<h2>🚀 Getting Started</h2>
<ol>
  <li>Clone the repository</li>
  <li>Install dependencies using <code>pip install -r requirements.txt</code></li>
  <li>Run the Jupyter notebook for full analysis</li>
</ol>

<h2>📚 References</h2>
<ul>
  <li>SDSS DR16 SkyServer</li>
  <li>Virial theorem mass estimation in galaxy clusters</li>
  <li>Basic cosmological distance and mass conversion formulas</li>
</ul>

</body>
</html>
