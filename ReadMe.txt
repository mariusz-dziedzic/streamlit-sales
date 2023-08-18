The application analyzes sales data from an Excel file. It displays them in a clear form in the web application. It allows you to filter data by city, gender, membership card, product category, and payment type.
Then, the main statistics on sales value, net income and average customer rating are displayed. Below are the charts in which hours the most transactions are made and in which category they occur. Data and charts change dynamically based on currently selected filters.


Before starting you need:
pip install openpyxl
pip install plotly
pip install pandas
pip install streamlit


Then run below command in your consol.
The application will launch in your browser default on http://localhost:8501/

streamlit run streamlit_app.py