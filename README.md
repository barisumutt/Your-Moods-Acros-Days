# Diary Tone Analysis
The "Diary Tone" application allows you to analyze the positivity and negativity of your diary entries over time. It utilizes the Streamlit framework, plotly.express library, and the Natural Language Toolkit (NLTK) sentiment analysis tool.

## Prerequisites
Ensure that you have the following dependencies installed in your Python environment:

- Streamlit
- plotly
- nltk
  
You can install these dependencies by running the following command:

```bash
pip install streamlit plotly nltk
```

You also need to download the NLTK sentiment analysis package. In a Python interpreter or script, run the following commands:

```bash
import nltk
nltk.download('vader_lexicon')
```
## Usage
1. Place your diary entries as separate text files in the "diary" directory. The files should have a ".txt" extension.
2. Run the Streamlit application by executing the following command in the project directory:
```bash
streamlit run app.py
```
3. The application will open in your browser and display a title "Diary Tone".
4. The application will generate two line charts: "Positivity" and "Negativity".
5. The "Positivity" chart displays the positivity score of each diary entry over time.
6. he "Negativity" chart displays the negativity score of each diary entry over time.
7. You can hover over the data points on the charts to view the specific dates and scores.
8. Explore the charts to gain insights into the overall tone of your diary entries and how it changes over time.

## Contact
If you have any questions or suggestions regarding this project, please feel free to contact Barış Umut Baykal at barisumutbaykal@gmail.com.

Enjoy analyzing your diary entries and gaining insights into your emotional journey!
