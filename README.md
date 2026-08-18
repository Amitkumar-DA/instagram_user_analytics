<h1><strong>Instagram User Analytics</strong></h1>
<p>A practical <strong>data analytics project</strong> demonstrating an end-to-end workflow: loading an Instagram dataset into MySQL, performing EDA and data cleaning, running SQL analysis, extracting business insights, and communicating results through a professional report and Gamma presentation.</p>
<h2><strong>Overview</strong></h2>
<p>The project analyzes Instagram user data to derive insights related to:</p>
<ul>
<li>User engagement</li>
<li>Marketing strategy</li>
<li>Content performance</li>
<li>Hashtag usage</li>
<li>Registration trends</li>
<li>Platform activity</li>
<li>Suspicious/fake account detection</li>
</ul>
<p>The supplied project material identifies MySQL Workbench and SQL as the core analysis environment and describes the workflow from database creation through business insights and report/PPT preparation.</p>
<h2><strong>Dataset</strong></h2>
<p>The project uses an <strong>Instagram Database Dataset</strong> with relational tables including:</p>
<ul>
<li>users</li>
<li>photos</li>
<li>likes</li>
<li>tags</li>
<li>photo_tags</li>
</ul>
<p>These tables support analysis of users, photos, likes, and hashtag usage.</p>
<h2><strong>Tools &amp; Technologies</strong></h2>
<table>
<tbody>
<tr>
<td>
<p><strong>Tool / Technology</strong></p>
</td>
<td>
<p><strong>Purpose</strong></p>
</td>
</tr>
<tr>
<td>
<p><strong>MySQL</strong></p>
</td>
<td>
<p>Database management and SQL analysis</p>
</td>
</tr>
<tr>
<td>
<p><strong>MySQL Workbench</strong></p>
</td>
<td>
<p>Database loading and querying</p>
</td>
</tr>
<tr>
<td>
<p><strong>SQL</strong></p>
</td>
<td>
<p>Data analysis and business queries</p>
</td>
</tr>
<tr>
<td>
<p><strong>Python / Pandas</strong></p>
</td>
<td>
<p>EDA and analytical support</p>
</td>
</tr>
<tr>
<td>
<p><strong>Matplotlib</strong></p>
</td>
<td>
<p>Data visualization</p>
</td>
</tr>
<tr>
<td>
<p><strong>Gamma</strong></p>
</td>
<td>
<p>Presentation / PPT creation</p>
</td>
</tr>
<tr>
<td>
<p><strong>PowerPoint / PDF</strong></p>
</td>
<td>
<p>Final reporting</p>
</td>
</tr>
</tbody>
</table>
<h2><strong>Project Workflow</strong></h2>
<h3><strong>1. Load the Dataset</strong></h3>
<ul>
<li>Create the MySQL database using the provided SQL file.</li>
<li>Import the tables into MySQL Workbench.</li>
<li>Verify the database structure and table relationships.</li>
</ul>
<h3><strong>2. Perform EDA</strong></h3>
<p>Explore the dataset to understand:</p>
<ul>
<li>Table structure</li>
<li>Record counts</li>
<li>Columns and data types</li>
<li>User activity</li>
<li>Photo activity</li>
<li>Likes and engagement</li>
<li>Hashtag usage</li>
<li>Relationships between tables</li>
</ul>
<h3><strong>3. Clean and Prepare the Data</strong></h3>
<p>Check and prepare the data before analysis:</p>
<ul>
<li>Missing values</li>
<li>Duplicate records</li>
<li>Data types</li>
<li>Invalid or inconsistent values</li>
<li>Date/time fields</li>
<li>Primary and foreign-key relationships</li>
</ul>
<h3><strong>4. Run SQL Analysis</strong></h3>
<p>Use SQL techniques such as:</p>
<ul>
<li>JOIN</li>
<li>GROUP BY</li>
<li>ORDER BY</li>
<li>Aggregate functions</li>
<li>HAVING</li>
<li>Subqueries</li>
<li>Date functions such as DAYNAME()</li>
</ul>
<p>The project specifically uses these techniques to answer business questions.</p>
<h3><strong>5. Extract Business Insights</strong></h3>
<p>Translate SQL results into practical recommendations for marketing, product, and investor stakeholders.</p>
<h3><strong>6. Create the Report</strong></h3>
<p>Document the methodology, SQL analysis, results, insights, and conclusions.</p>
<h3><strong>7. Create the Presentation</strong></h3>
<p>Use <strong>Gamma</strong> to convert the analysis into a concise, visually engaging presentation for project reviews, portfolio demonstrations, and interviews.</p>
<h2><strong>Analysis Performed</strong></h2>
<h3><strong>Marketing Analysis</strong></h3>
<ol>
<li><strong> Loyal User Reward</strong><strong><br /></strong>Identify the five oldest users to support loyalty or reward campaigns.</li>
<li><strong> Inactive User Engagement</strong><strong><br /></strong>Identify users who have never posted a photo so they can be considered for re-engagement campaigns.</li>
<li><strong> Contest Winner</strong><strong><br /></strong>Find the user whose single photo received the most likes, helping identify high-performing content and popular creators.</li>
<li><strong> Hashtag Research</strong><strong><br /></strong>Find the five most commonly used hashtags to identify popular hashtag patterns.</li>
<li><strong> Ad Campaign Launch</strong><strong><br /></strong>Identify the weekday with the highest number of registrations to support campaign timing.</li>
</ol>
<h3><strong>Investor Metrics</strong></h3>
<ol start="6">
<li><strong> User Engagement</strong><strong><br /></strong>Calculate the average number of posts per user as a high-level platform activity metric.</li>
<li><strong> Bots &amp; Fake Accounts</strong><strong><br /></strong>Identify users who liked every photo as a suspicious-behavior signal for further investigation.</li>
</ol>
<h2><strong>Results &amp; Business Insights</strong></h2>
<h3><strong>Marketing Insights</strong></h3>
<ul>
<li>Loyal users can be rewarded.</li>
<li>Inactive users can be targeted through campaigns.</li>
<li>Trending hashtags can support reach and content strategy.</li>
<li>Registration patterns can help identify effective campaign timing.</li>
<li>Popular content creators can be identified through engagement.</li>
</ul>
<h3><strong>Investor / Product Insights</strong></h3>
<ul>
<li>Average posting rate provides an engagement indicator.</li>
<li>Abnormal like behavior can help identify potentially suspicious accounts.</li>
<li>Popular content provides insight into platform activity.</li>
</ul>
<p>These are the key insights documented in the supplied project report.</p>
<h2><strong>Project Outcomes</strong></h2>
<p>The project demonstrates practical experience with:</p>
<ul>
<li>Relational databases</li>
<li>SQL joins</li>
<li>Aggregations</li>
<li>Grouping and ranking</li>
<li>Subqueries</li>
<li>Business analytics</li>
<li>Data-driven decision-making</li>
<li>Analytics storytelling and presentation</li>
</ul>
<p>The supplied report specifically highlights real-world SQL analysis, joins, aggregations, subqueries, and actionable business insights as project achievements.</p>
<h2><strong>How to Run</strong></h2>
<h3><strong>Prerequisites</strong></h3>
<p>Install or have access to:</p>
<ul>
<li>MySQL Server</li>
<li>MySQL Workbench</li>
<li>Python 3.x</li>
<li>Python analytics libraries</li>
<li>Gamma for presentation creation</li>
</ul>
<h3><strong>MySQL Setup</strong></h3>
<ol>
<li>Start MySQL Server.</li>
<li>Open MySQL Workbench.</li>
<li>Create/load the Instagram database using the provided SQL file.</li>
<li>Verify that the required tables exist.</li>
<li>Run the SQL analysis queries.</li>
</ol>
<p>Example:</p>
<p>USE ig_clone;</p>
<p>SELECT *</p>
<p>FROM users</p>
<p>LIMIT 10;</p>
<h3><strong>Python Setup</strong></h3>
<p>Create a virtual environment if desired:</p>
<p>python -m venv venv</p>
<p>Activate it:</p>
<p><strong>Windows</strong></p>
<p>venv\Scripts\activate</p>
<p><strong>macOS / Linux</strong></p>
<p>source venv/bin/activate</p>
<p>Install dependencies:</p>
<p>pip install pandas matplotlib sqlalchemy pymysql openpyxl</p>
<p>Run the Python analytics script:</p>
<p>python instagram_user_analytics.py</p>
<p>Configure your MySQL connection details before running the script.</p>
<h2><strong>Deliverables</strong></h2>
<ul>
<li>MySQL database</li>
<li>SQL analysis queries</li>
<li>EDA / data-preparation work</li>
<li>Analytics results</li>
<li>Visualizations</li>
<li>PDF / analytical report</li>
<li>Gamma presentation</li>
<li>Python analytics script</li>
</ul>
<h2><strong>Recommended Repository Structure</strong></h2>
<p>instagram-user-analytics/</p>
<p>│</p>
<p>├── data/</p>
<p>│ └── dataset / SQL files</p>
<p>│</p>
<p>├── sql/</p>
<p>│ └── analysis_queries.sql</p>
<p>│</p>
<p>├── python/</p>
<p>│ └── instagram_user_analytics.py</p>
<p>│</p>
<p>├── notebooks/</p>
<p>│ └── eda.ipynb</p>
<p>│</p>
<p>├── reports/</p>
<p>│ └── Instagram_User_Analytics.pdf</p>
<p>│</p>
<p>├── presentation/</p>
<p>│ └── Gamma_Presentation</p>
<p>│</p>
<p>├── visualizations/</p>
<p>│ └── charts/</p>
<p>│</p>
<p>└── README.md</p>
<h2><strong>Key Takeaway</strong></h2>
<p><strong>Dataset &rarr; MySQL &rarr; EDA &rarr; Data Cleaning &rarr; SQL Analysis &rarr; Business Insights &rarr; Report &rarr; Gamma Presentation</strong></p>
<p>This project demonstrates the ability to work with relational data, prepare data for analysis, write analytical SQL queries, derive business insights, and communicate findings through professional data storytelling.</p>
<h2><strong>Author</strong></h2>
<p><strong>[Amit Kumar]</strong><strong><br /></strong><em>Data Analyst | SQL | Python | MySQL | Data Visualization</em></p>
