<h1>📚 Web Scraping Project</h1>

<h2>1. Project Overview</h2>
<p>
This project aims to extract book data from a public website using Python web scraping techniques.
The collected data is stored in a CSV file for analysis.
</p>

<h2>2. Objectives</h2>
<ul>
  <li>Extract data from public web pages</li>
  <li>Understand HTML structure</li>
  <li>Handle website pagination</li>
  <li>Create a custom dataset</li>
  <li>Save data into a CSV file</li>
</ul>

<h2>3. Technologies Used</h2>

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="50"/>
  <img src="https://www.crummy.com/software/BeautifulSoup/bs4/doc/_static/6.1.jpg" width="60"/>
</p>

<ul>
  <li>Python</li>
  <li>Requests</li>
  <li>BeautifulSoup</li>
  <li>Pandas</li>
</ul>

<h2>4. Dataset Source</h2>

<p>
The dataset was collected from:
</p>

<a href="https://books.toscrape.com/" target="_blank">

  
<h2>5. Project Workflow</h2>

<ol>
  <li><strong>Fetch HTML</strong> : Download web pages using the Requests library.</li>
  <li><strong>Parse HTML</strong> : Analyze the HTML structure with BeautifulSoup.</li>
  <li><strong>Extract Data</strong> : Collect book titles, prices, and ratings.</li>
  <li><strong>Handle Pagination</strong> : Navigate through multiple pages automatically.</li>
  <li><strong>Create DataFrame</strong> : Store extracted data in a Pandas DataFrame.</li>
  <li><strong>Export CSV</strong> : Save the dataset as a CSV file.</li>
</ol>

<h2>6. Data Collected</h2>

<table>
  <tr>
    <th>Attribute</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Book Title</td>
    <td>Name of the book</td>
  </tr>
  <tr>
    <td>Price</td>
    <td>Book price in pounds (£)</td>
  </tr>
  <tr>
    <td>Rating</td>
    <td>Book rating from One to Five stars</td>
  </tr>
</table>

<h2>7. Project Structure</h2>

<pre>
Web-Scraping-Project/
│
├── web_scraping_books.ipynb
├── books_dataset.csv
├── README.md
</pre>

<h2>8. Results</h2>

<ul>
  <li>Successfully scraped all available book pages.</li>
  <li>Collected approximately 1000 books.</li>
  <li>Generated a structured CSV dataset for analysis.</li>
</ul>

<h3>Sample Dataset</h3>

<table>
  <tr>
    <th>Title</th>
    <th>Price</th>
    <th>Rating</th>
  </tr>
  <tr>
    <td>A Light in the Attic</td>
    <td>£51.77</td>
    <td>Three</td>
  </tr>
  <tr>
    <td>Tipping the Velvet</td>
    <td>£53.74</td>
    <td>One</td>
  </tr>
</table>

<h2>9. How to Run</h2>

<pre>
pip install requests beautifulsoup4 pandas

python main.py
</pre>

  Books to Scrape
</a>


<h2>10. Future Improvements</h2>

<ul>
  <li>Implement web scraping using Scrapy for better scalability.</li>
  <li>Store collected data in a SQL database (MySQL, PostgreSQL).</li>
  <li>Create interactive data visualizations and dashboards.</li>
  <li>Schedule automatic data collection.</li>
  <li>Perform advanced data analysis on the collected dataset.</li>
</ul>

<h2>11. Author</h2>

<div align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" width="120">
  
  <h3>Hicham Bakaz</h3>

  <p>
    Master's Student in Intelligent Web and Data Science
  </p>

  <p>
    Passionate about Data Science, Artificial Intelligence,
    Machine Learning, and Web Development.
  </p>
</div>


