<h1>📊 People Analytics – Talent Headcount & Attrition Dashboard</h1>

<p>
This project focuses on analyzing <b>employee headcount (HC)</b> and <b>voluntary attrition</b> within an IT organization using a combination of <b>Python</b>, <b>Streamlit</b>, and <b>data visualization</b> techniques.
It helps HR &amp; Talent Management teams identify patterns, attrition drivers, and improvement areas using a fully interactive web dashboard.
</p>

<br>

<h2>🚀 Project Overview</h2>
<p>
The dashboard allows HR leaders to quickly explore workforce distribution, identify high-risk segments, and monitor attrition trends over time.  
Whenever a new HR data file is uploaded, the system can be refreshed to provide <b>up-to-date analytics</b>.
</p>

<br>

<h2>🗂️ Project Structure</h2>

<pre><code>├── app.py                       # Streamlit dashboard app
├── exploratory_analysis.py      # EDA: correlation, histograms, boxplots
├── People Analytics Report.docx # Full documentation &amp; detailed results
└── README.md                    # Project documentation
</code></pre>

<br>

<h2>🎯 Project Objective</h2>

<p>To provide HR leaders with data-driven insights into:</p>
<ul>
  <li>👥 Workforce distribution</li>
  <li>📉 Employee attrition patterns</li>
  <li>⌛ Tenure and job satisfaction impact</li>
  <li>🏢 Department-wise turnover</li>
  <li>🌍 Demographic breakdowns</li>
  <li>⏱️ Overtime effects on attrition</li>
</ul>

<br>

<h2>🔍 Key Features</h2>

<h3>✅ 1. Automated Data Cleaning &amp; Preprocessing</h3>
<ul>
  <li>Convert Yes/No and categorical fields into binary/numeric variables</li>
  <li>Column selection and renaming for clarity</li>
  <li>Null value checks and duplicate detection</li>
  <li>Creation of numeric-only dataframes for EDA</li>
</ul>

<h3>✅ 2. Exploratory Data Analysis (EDA)</h3>
<ul>
  <li>Correlation heatmaps to detect relationships between variables</li>
  <li>Histograms to understand distribution of age, income, tenure, etc.</li>
  <li>Boxplots for outlier detection</li>
  <li>Summary statistics (mean, median, skewness)</li>
</ul>

<h3>✅ 3. Headcount (HC) Analysis</h3>
<p>Interactive Streamlit charts show:</p>
<ul>
  <li>HC by department</li>
  <li>HC by age group</li>
  <li>HC by monthly income band</li>
  <li>HC by gender</li>
  <li>HC by years at company</li>
</ul>

<h3>✅ 4. Attrition Analysis</h3>
<p>The dashboard and report highlight:</p>
<ul>
  <li>High attrition in the <b>Sales</b> department</li>
  <li>Higher losses among employees with <b>0–2 years</b> tenure</li>
  <li>Young professionals in the <b>26–35</b> age group at highest risk</li>
  <li>Employees working <b>overtime</b> show significantly higher attrition</li>
  <li><b>Higher job satisfaction</b> = lower attrition</li>
  <li><b>Poor job satisfaction &amp; work-life balance</b> = higher attrition</li>
</ul>

<p>Streamlit visualizations include:</p>
<ul>
  <li>Attrition by department</li>
  <li>Attrition by education</li>
  <li>Attrition by age</li>
  <li>Attrition by gender</li>
  <li>Attrition by job role</li>
  <li>Attrition by tenure</li>
  <li>Attrition vs. job &amp; environment satisfaction</li>
  <li>Attrition vs. overtime</li>
</ul>

<br>

<h2>📊 Results – Key Findings</h2>

<ul>
  <li>🔥 <b>Sales department</b> shows the highest voluntary attrition.</li>
  <li>🧑‍🎓 <b>Early-career employees (0–5 years)</b> are more likely to leave.</li>
  <li>📅 <b>Age group 26–35</b> has the highest turnover.</li>
  <li>⏱️ Employees doing <b>overtime</b> leave at a higher rate.</li>
  <li>👩 Female employees have <b>lower attrition</b> compared to males.</li>
  <li>😕 <b>Low job satisfaction</b> and poor work-life balance significantly increase turnover risk.</li>
</ul>

<br>

<h2>🧠 Recommendations</h2>

<p>For HR &amp; Business Leaders:</p>
<ul>
  <li>🤝 Conduct deep-dive interviews in the <b>Sales</b> department to understand high turnover.</li>
  <li>🎓 Focus on retaining <b>new hires</b>, particularly university / early-career hires.</li>
  <li>⏰ Review workload &amp; <b>overtime policies</b> to prevent burnout.</li>
  <li>📈 Improve <b>job satisfaction</b> with growth plans, feedback loops, and coaching.</li>
  <li>🌈 Strengthen <b>diversity hiring</b> strategies — female attrition is lower and can support better stability.</li>
</ul>

<br>

<h2>🧰 Tools &amp; Technologies Used</h2>

<h3>🧮 Programming &amp; Analysis</h3>
<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>

<h3>🖥️ Interactive Dashboard</h3>
<ul>
  <li>Streamlit (UI layout, charts, filters)</li>
</ul>

<h3>📊 Statistical &amp; Visual Analysis</h3>
<ul>
  <li>Correlation analysis</li>
  <li>Summary statistics</li>
  <li>Distribution analysis</li>
  <li>Countplots, histograms, heatmaps, boxplots</li>
</ul>

<h3>📝 Documentation &amp; Reporting</h3>
<ul>
  <li>Microsoft Word – full People Analytics report</li>
  <li>Streamlit web app</li>
  <li>Python scripts / notebooks</li>
</ul>

<br>

<h2>🚀 How to Run the Dashboard</h2>

<h3>1️⃣ Install Dependencies</h3>
<pre><code>pip install streamlit pandas numpy seaborn matplotlib
</code></pre>

<h3>2️⃣ Run the Streamlit App</h3>
<pre><code>streamlit run app.py
</code></pre>

<p>The dashboard will open in your browser at <code>http://localhost:8501</code> by default.</p>

<br>

<h2>🏁 Summary</h2>

<p>This People Analytics project delivers:</p>
<ul>
  <li>✅ A complete end-to-end HR analytics workflow</li>
  <li>✅ A dynamic, interactive Streamlit dashboard</li>
  <li>✅ Deep insights into attrition &amp; workforce patterns</li>
  <li>✅ Recommendations backed by <b>data and visualizations</b></li>
</ul>

<p>
It is a strong demonstration of my skills in <b>data analysis</b>, <b>dashboarding</b>, <b>Python development</b>, and <b>HR domain analytics</b>.
</p>
