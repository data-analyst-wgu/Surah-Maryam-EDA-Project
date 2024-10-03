Final Report: EDA of Surah Maryam in the Quran: By Ahsan Khan 

Project Overview
A.1. Research Question or Organizational Need
The primary research question this project addressed was: What are the key thematic elements in Surah Maryam (Chapter 19) of the Quran as reflected in word frequency and context? The project sought to explore the structure and thematic significance of the chapter, focusing on key figures such as Maryam and Allah. The insights generated were intended to provide scholars and students of Islamic studies with a quantitative analysis of this important chapter.
A.2. Scope of the Project
The scope of the project was restricted to analyzing the English Yusuf Ali translation of Surah Maryam. The analysis focused on extracting insights through word frequency analysis and text mining techniques. The project excluded comparative analysis with other translations, chapters, or religious texts.

A.3. Overview of the Solution
The project utilized a descriptive analytics approach. Key tools and methodologies included:
Python libraries: Pandas for data manipulation, NLTK for text preprocessing, Matplotlib and WordCloud for visualization.
Methodologies: Word frequency analysis was the primary method used to identify recurring terms, with a focus on visualizing these patterns through word clouds and bar charts.




Project Execution
B.1. Project Plan
The original project plan involved:
Data collection: Obtaining the Quran dataset (Yusuf Ali translation).
Data preparation: Cleaning and preprocessing the text.
Analysis: Performing word frequency analysis and generating visualizations.


B.2. Project Planning Methodology
The CRISP-DM methodology was used to guide the project. The project adhered to its phases (Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment), although some adjustments were made during the data preparation phase when additional cleaning was required.


B.3. Timeline and Milestones
The initial timeline was extended due to unexpected issues with encoding and data formatting. However, the following major milestones were achieved:
Data Collection and Preparation: Week 1–2.
Analysis and Visualization: Week 3.
Final Reporting: Week 4.






Methodology
C.1. Data Selection and Collection Process
The data for this project was sourced from Kaggle, containing the complete English Yusuf Ali translation of the Quran. The dataset was pre-processed to focus only on Surah Maryam. The actual data selection process was as planned, but the collection encountered some challenges due to text formatting issues that required additional cleaning.
Obstacles: Data cleaning took longer than anticipated due to the removal of non-alphanumeric characters and punctuation.
Data Governance: No significant governance issues were encountered since the dataset was publicly available and did not include personal or sensitive information.
C.2. Advantages and Limitations of the Dataset
Advantages: The dataset was publicly accessible and provided a reliable translation of the Quran. Its structure (Surah and Ayah columns) made it easy to filter and analyze specific sections.
Limitations: The dataset's text-based nature meant that additional preprocessing was required to handle stop words and special characters. It was also limited to one translation of the Quran, excluding other versions.


D. Data Extraction and Preparation
The data preparation process included the following steps:
Data extraction: Focused on extracting only the Surah Maryam section from the larger dataset.
Preprocessing: Included converting the text to lowercase, removing punctuation, and eliminating stop words using the NLTK library.
Tokenization: The text was tokenized into individual words for frequency analysis.
The use of Pandas for extraction and NLTK for text preprocessing was appropriate because these libraries efficiently handle large textual data, enabling seamless data cleaning and transformation.


Data Analysis Process
E.1. Methods Used
Word Frequency Analysis: Calculated the frequency of specific terms, focusing on the words "Allah" and "Maryam" to assess their thematic importance.
Visualization: Tools like WordCloud and Matplotlib were used to visualize the frequency of words, helping to reveal patterns in the text.

E.2. Advantages and Limitations of Tools
Advantages:
WordCloud: Effectively visualized key terms and their relative importance within the chapter.
Matplotlib: Provided straightforward bar charts for frequency comparisons.
Limitations:
WordCloud: While visually appealing, it can be less effective at conveying precise quantitative information.
Bar charts: Limited in showing the relationships between themes and context.

E.3. Step-by-Step Application of Analytical Methods
Data Cleaning: Text was cleaned by removing punctuation and stop words using NLTK.
Tokenization: The cleaned text was tokenized into individual words.
Word Frequency Calculation: The word frequency of all terms in Surah Maryam was calculated using Python’s Counter.
Visualization: Generated word clouds and bar charts to visualize the most frequently mentioned terms.
Verification: The results were verified by comparing the most frequent terms with known themes in the chapter.





Results
F.1. Output Evaluation
The analysis revealed that "Allah" and "Maryam" were among the most frequently mentioned terms in the chapter, confirming the significance of divine themes and Maryam's role. These outputs met the expectations, as the key terms aligned with the thematic focus of Surah Maryam.


F.2. Practical Significance
The practical significance of this analysis is valuable for:
Islamic scholars seeking to understand the thematic focus of Surah Maryam in the context of divine relationships.
Religious educators who can use the results to illustrate the significance of certain figures and themes in the Quran.

F.3. Overall Success
The project successfully met its objectives by uncovering thematic patterns and providing insights through visualizations. The methodology applied effectively addressed the research question, and the deliverables provided useful tools for stakeholders.








Key Takeaways
G.1. Conclusions
The analysis of Surah Maryam confirmed the prominence of divine themes, with "Allah" being the most frequent term. The focus on Maryam highlighted her importance in the chapter, supporting the chapter's central narrative.
G.2. Tools for Effective Storytelling
The use of WordCloud and bar charts provided clear and effective ways to visualize and communicate the findings. The word cloud, in particular, offered a visual summary of the key terms and their relative prominence, while bar charts provided precise data points for analysis.


G.3. Recommended Actions
Further Analysis: Extend the analysis to other chapters in the Quran to explore how Maryam is referenced in other contexts.
Educational Use: Utilize the findings to develop educational materials that explain the significance of Surah Maryam in Islamic teachings.

Appendices
I.1. Code Used
The code used for this analysis includes Python scripts for data cleaning, tokenization, word frequency analysis, and visualizations using Pandas, NLTK, Matplotlib, and WordCloud.
I.2. Data Sources
The dataset was sourced from Kaggle and contains the English Yusuf Ali translation of the Quran.

