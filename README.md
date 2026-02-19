<body>

<header>
<h1>Customer Retention & Impact Analytics Warehouse</h1>
<p>Digital Allyship Toolkit – End-to-End SQL Data Warehouse Case Study</p>
</header>

<section>
<h2>Business Problem</h2>
<div class="card">
<p>The Digital Allyship Toolkit platform has growing user registrations but stakeholders require measurable impact.</p>
<ul>
<li>Are users returning after learning?</li>
<li>Which users create the most value?</li>
<li>What behaviour predicts certification completion?</li>
<li>Where do users drop off?</li>
</ul>
</div>
</section>

<section>
<h2>Project Overview</h2>
<div class="card">
<b>Project:</b> Customer Retention & Impact Analytics Warehouse<br>
<b>Team:</b> Lumera (Team 39)<br>
<b>Goal:</b> Transform learning activity data into measurable retention and engagement metrics.
</div>
</section>

<section>
<h2>Medallion Data Architecture</h2>

<div class="card">
<h3>Bronze Layer – Raw Data</h3>
<ul>
<li>User registrations</li>
<li>Module activity logs</li>
<li>Quiz attempts</li>
<li>Confidence surveys</li>
<li>Session activity</li>
<li>Certification records</li>
</ul>
</div>

<div class="card">
<h3>Silver Layer – Cleaned Data</h3>
<ul>
<li>Remove duplicates</li>
<li>Standardize timestamps</li>
<li>Validate quiz score ranges</li>
<li>Normalize module names</li>
<li>Handle missing values</li>
</ul>
</div>

<div class="card">
<h3>Gold Layer – Analytics Star Schema</h3>
<table>
<tr><th>Dimension Tables</th><th>Fact Tables</th></tr>
<tr><td>dim_user</td><td>fact_learning_activity</td></tr>
<tr><td>dim_module</td><td>fact_quiz_results</td></tr>
<tr><td>dim_date</td><td>fact_sessions</td></tr>
<tr><td>dim_content_type</td><td>fact_confidence</td></tr>
<tr><td></td><td>fact_certification</td></tr>
</table>
</div>
</section>

<section>
<h2>Key Business Metrics</h2>
<div class="card">
<table>
<tr><th>Corporate Metric</th><th>Allyship Equivalent</th></tr>
<tr><td>Revenue</td><td>Engagement Value</td></tr>
<tr><td>Customer Retention</td><td>Learning Retention</td></tr>
<tr><td>Conversion</td><td>Certification Completion</td></tr>
<tr><td>Product Usage</td><td>Module Participation</td></tr>
<tr><td>Customer Loyalty</td><td>Behaviour Change</td></tr>
</table>
</div>
</section>

<h2>Dashboard Outputs</h2>
<div class="card">
<ul>
<li>Monthly Active Users Trend</li>
<li>Learning Drop-off Funnel</li>
<li>Module Completion Rate</li>
<li>Confidence Growth vs Quiz Score</li>
<li>Cohort Retention Heatmap</li>
</ul>
</div>
</section>

<section>
<h2>Skills Demonstrated</h2>
<div class="card">
<ul>
<li>Star Schema Modeling</li>
<li>Analytical SQL</li>
<li>Product Analytics</li>
<li>Business Impact Measurement</li>
</ul>
</div>
</section>

<footer>
<p>Portfolio Case Study — Data Analytics & BI Engineering</p>
</footer>

</body>
</html>
