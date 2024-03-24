# Web-Scraping-Data-Extraction-and-NLP

**Instructions for Running the Web Crawler Jupyter Notebook:**


1. **Approach to the Solution:**
   - **Problem Understanding:**
     - The initial step involved understanding the problem statement, which likely required extracting article text from specified URLs, performing sentiment analysis, and analyzing             readability metrics.
   
   - **Research and Planning:**
     - Researching relevant libraries and tools suitable for web scraping, natural language processing (NLP), and data analysis.
     - Planning the project structure, including the organization of code into functions, to ensure modularity and reusability.

   - **Web Scraping:**
     - Utilizing the `requests` library to fetch HTML content from the provided URLs.
     - Employing `BeautifulSoup` for parsing the HTML and extracting relevant article text from the web pages.Doble check the class and tags of html document.
     - Save the extraxt articles in .txt format inside "Output Extract" Folder.

   - **Data Preprocessing:**
     - Performing text preprocessing tasks such as tokenization, removing stopwords, and handling punctuation to prepare the text data for analysis.
     - Cleaning the extracted text by removing unnecessary HTML tags, special characters, and formatting artifacts.
     - Saving the cleaned txt file inside "Output Clean" Folder for easy access

   - **Sentiment Analysis:**
     - Utilizing sentiment analysis techniques to assess the sentiment polarity of the extracted article text.
     - Assigning positive and negative scores to words using predefined lexicons or dictionaries, such as the provided "positive-words.txt" and "negative-words.txt".
     - Create function for this process.

   - **Readability Analysis:**
     - Analyzing readability metrics to assess the complexity of the article text.
     - Calculating metrics such as average sentence length, percentage of complex words, and Fog Index to gauge readability.

   - **Data Analysis:**
     - Analyzing the sentiment and readability metrics to derive insights from the data.

   - **Documentation and Comments:**
     - Providing detailed documentation and comments throughout the code to explain the purpose of each function, logic, and major steps.
     - Including markdown cells in Jupyter Notebook to provide explanations, instructions, and analysis interpretations.

   - **Output Generation:**
     - Generating structured output, such as an Excel file, containing the analyzed data for further analysis or reporting purposes.

By following this approach, the solution aims to effectively extract, analyze, and interpret article text from the provided URLs, enabling informed decision-making based on sentiment and readability insights.

2. **How to Run the Notebook to Generate Output:**
   - Ensure you have Jupyter Notebook installed on your system. You can install it as part of the Anaconda distribution or using pip.
   - Open a terminal or command prompt.
   - Navigate to the directory where the "Web_Crawler_script.ipynb" file is located using the `cd` command.
   - Start the Jupyter Notebook server by running the command:
     ```
     jupyter notebook
     ```
   - This will open the Jupyter Notebook interface in your web browser.
   - Navigate to the "Web_Crawler_script.ipynb" file and open it.
   - Execute each cell in the Notebook sequentially by selecting the cell and pressing Shift + Enter.
   - Follow any instructions or prompts within the Notebook to provide input or make selections.
   - The Notebook will execute the code cells and display outputs, including any visualizations or text outputs.

3. **Dependencies Required:**
   - The dependencies required are likely similar to those for the Python script, including libraries like pandas, requests, BeautifulSoup, and nltk.
   - Ensure you have these libraries installed in your Python environment. You can install them using pip if not already installed:
     ```
     pip install pandas requests beautifulsoup4 nltk
     ```
   - Additionally, make sure to download the necessary NLTK resources by running the following Python code once within the Notebook:
     ```python
     import nltk
     nltk.download('punkt')
     nltk.download('stopwords')
     ```

By following these instructions, you should be able to run the Jupyter Notebook and execute the web crawling and analysis tasks described within it.
