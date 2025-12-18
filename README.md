<h1> Olist E-Commerce Sales Analytics (SQL + Power BI + ETL)</h1>

<p>
This project demonstrates a complete <strong>end-to-end data analytics workflow</strong> using real-world Brazilian Olist e-commerce data. 
The objective was to simulate real business analytics tasks including data extraction, transformation, SQL case studies, data modeling, and dashboard creation.
</p>

<h2> Tech Stack</h2>

<ul>
  <li><strong>Data Extraction:</strong> Kaggle</li>
  <li><strong>Data Cleaning:</strong> Python, Pandas</li>
  <li><strong>Database:</strong> MySQL</li>
  <li><strong>Data Modeling:</strong> Power Query</li>
  <li><strong>Visualization:</strong> Power BI</li>
  <li><strong>Languages:</strong> SQL, DAX</li>
  <li><strong>Version Control:</strong> Git & GitHub</li>
</ul>

<h2> Project Workflow Overview</h2>

<h3>1️. Dataset Extraction (Kaggle)</h3>
<ul>
  <li>Downloaded the full Olist dataset from Kaggle.</li>
  <li>Stored the dataset in a structured <code>/data/</code> directory.</li>
  <li>Verified relational tables such as orders, order_items, payments, customers, and products.</li>
</ul>

<h3>2️. Data Cleaning & Preparation (Python)</h3>
<ul>
  <li>Inspected data using <code>.info()</code>, <code>.describe()</code>, and exploratory checks.</li>
  <li>Handled missing values and null timestamps.</li>
  <li>Converted date columns to datetime format.</li>
  <li>Engineered new fields:
    <ul>
      <li><code>delivery_days</code></li>
      <li><code>late_delivery</code></li>
    </ul>
  </li>
  <li>Validated schema and primary key relationships.</li>
</ul>

<h3>3️. ETL & Database Loading (MySQL)</h3>
<ul>
  <li>Created relational schema for loading cleaned tables.</li>
  <li>Imported datasets using SQL.</li>
  <li>Ensured referential integrity and normalization.</li>
  <li>Executed analytical queries using JOINs, GROUP BY, and WINDOW FUNCTIONS.</li>
</ul>

<h3>4️. Analytical Case Studies (SQL)</h3>
<p>Answered business-critical questions using:</p>
<ul>
  <li>Monthly revenue trends</li>
  <li>New vs returning customer segmentation</li>
  <li>Top product categories and sellers</li>
  <li>Delivery performance and delays</li>
  <li>Payment preference analysis</li>
</ul>

<pre>
JOIN, COUNT, SUM, AVG, NTILE, RANK, DENSE_RANK
</pre>

<h3>5️. Data Modeling (Power Query & BI)</h3>
<ul>
  <li>Consolidated five normalized tables into a single analytical olist table.</li>
  <li>Established relationships (Star Schema).</li>
  <li>Created calculated columns and DAX measures including:</li>
    <ul>
      <li>Total Revenue</li>
      <li>AOV</li>
      <li>Late Delivery %</li>
      <li>Month-over-Month Growth</li>
    </ul>
</ul>

<h3>6️. Power BI Dashboard Design</h3>
<ul>
  <li><strong>Executive KPIs:</strong> Revenue, Orders, AOV, Monthly Trend</li>
  <li><strong>Customer Analysis:</strong> New vs Returning, Pareto 80/20, AOV comparison</li>
  <li><strong>Products & Sellers:</strong> Category and seller ranking</li>
  <li><strong>Delivery:</strong> Avg Delivery Days, Late % by State</li>
  <li><strong>Payments:</strong> Methods & Installments</li>
  <li><strong>Scatter Analysis:</strong> Weight vs Freight cost correlation</li>
</ul>

<h2> Key Insights</h2>

<ul>
  <li>Returning customers generate a higher AOV — retention is crucial.</li>
  <li>Freight cost correlates strongly with product weight.</li>
  <li>Delivery delays vary significantly by region indicating logistics issues.</li>
  <li>Top 20% of customers account for the majority of revenue.</li>
  <li>Specific product categories dominate marketplace revenue.</li>
</ul>


<h2> Demonstrated Skills</h2>

<ul>
  <li>ETL (Extract • Transform • Load)</li>
  <li>SQL querying & window functions</li>
  <li>Data cleaning & preprocessing</li>
  <li>Power Query modeling</li>
  <li>DAX calculations</li>
  <li>Power BI dashboarding</li>
  <li>Business insight generation</li>
  <li>Documentation & Version control</li>
</ul>

```mermaid
flowchart TD
    A[Kaggle Dataset] --> B[Download via Kaggle API]
    B --> C[Python: Data Loading & Exploration]
    C --> D[Data Cleaning & Preparation]
    D --> E[Feature Engineering]
    E --> F[Load into MySQL]
    F --> G[SQL Case Studies & Business Insights]
    G --> H[Power Query Data Modeling]
    H --> I[Power BI Dashboard & Visualizations]


