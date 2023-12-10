# NoAhsan
Final Project
Introduction:
The presented Python application represents a multifaceted sentiment analysis and data management tool, designed to perform a range of tasks seamlessly. It amalgamates web scraping, database operations, and machine learning model training into a cohesive framework, all accessible through an intuitive graphical user interface (GUI) menu. Initiating with web scraping functionalities, the application extracts headlines from specified tags on web pages while ensuring data uniqueness through persistent storage. The scraped data is then translated to English, and sentiments are analyzed, followed by classification and insertion into a MySQL database. The machine learning module incorporates model training using Keras and TensorFlow, leveraging a Long Short-Term Memory (LSTM) network for sentiment prediction. Users can subsequently test the trained model with custom inputs. The GUI menu, implemented with the easygui library, offers an interactive interface for users to choose from various options, including data scraping, database insertion, model training, model testing, and visualization of sentiment distribution. Seaborn is employed for visualizing sentiment distribution, providing valuable insights into the dataset. This versatile Python application serves as a comprehensive solution for sentiment analysis tasks, seamlessly integrating data collection, preprocessing, machine learning, and user interaction into a unified environment.
Objective:
The objective of this project is to develop a versatile sentiment analysis and data management application in Python. The application will feature robust data scraping capabilities, with a focus on multilingual content, ensuring diverse and unique datasets. Integrated with a MySQL database, the system will support efficient data storage and retrieval. The core sentiment analysis model will employ Long Short-Term Memory (LSTM) techniques using TensorFlow/Keras, enabling accurate sentiment classification across various textual content. A user-friendly Graphical User Interface (GUI) using the easygui library will enhance accessibility, while visualization tools like matplotlib and seaborn will provide insightful analyses of sentiment distributions within the dataset. This multifaceted tool aims to offer a comprehensive solution for sentiment analysis and data organization, catering to users with diverse needs and linguistic preferences.
Problem statement:
This project aims to tackle challenges in sentiment analysis and data management through a versatile Python application. The core issues involve the effective collection and uniqueness of diverse data, multilingual content handling with translation for consistency, seamless integration with a MySQL database, LSTM-based sentiment analysis model training, user-friendly graphical interaction, and insightful sentiment distribution visualization. By addressing these challenges, the application strives to provide a holistic solution for sentiment analysis, catering to users with varying levels of technical expertise.
Proposed method:
The proposed methodology for this project encompasses several key steps. The initial phase involves data scraping from diverse online sources using BeautifulSoup, focusing on extracting headlines or titles with varying linguistic characteristics. The collected data is then stored in a MySQL database, where non-English titles undergo language translation for uniformity. Sentiment analysis is conducted using TextBlob, and sentiment classes are assigned based on polarity scores. The titles are encoded and stored in a labeled dataset.
The core of the project involves training a sentiment analysis model using TensorFlow and Keras. A deep learning architecture, specifically LSTM (Long Short-Term Memory), is employed for its ability to capture contextual information in sequential data. The model is trained on the labeled dataset, and the trained model is saved for future use.
The application's user interface is developed using easygui, providing an interactive platform for users to scrape new data, insert it into the database, train the sentiment analysis model, test its predictions, and visualize sentiment distributions. Visualization is achieved using matplotlib and seaborn, offering graphical insights into the sentiment distribution of the dataset. The combination of effective data processing, sentiment analysis, and user-friendly interaction forms a comprehensive methodology for this sentiment analysis and data management application.
The project involves the following process steps:
1. **Data Scraping:**
   - Utilize BeautifulSoup to scrape headlines or titles from diverse online sources.
   - Focus on various linguistic characteristics and store the collected data.
2. **Database Integration:**
   - Create a MySQL database to store the scraped data for efficient data management.
   - Implement translation for non-English titles to ensure uniformity in language.
3. **Sentiment Analysis:**
   - Apply sentiment analysis using TextBlob to evaluate the polarity of each title.
   - Assign sentiment classes based on polarity scores, distinguishing between positive and negative sentiments.
4. **Labeling and Encoding:**
   - Encode sentiment classes and store the labeled dataset, facilitating model training.
5. **Model Training:**
   - Employ TensorFlow and Keras to design and train a sentiment analysis model.
   - Utilize the LSTM (Long Short-Term Memory) architecture to capture contextual information in sequential data.
6. **User Interface Development:**
   - Implement a user-friendly interface using easygui, allowing users to interact with the application seamlessly.
   - Provide functionalities for scraping new data, inserting it into the database, training the sentiment analysis model, testing predictions, and visualizing sentiment distributions.
7. **Visualization:**
   - Use matplotlib and seaborn to create visualizations that offer insights into the sentiment distribution of the dataset.
   - Enhance user understanding through graphical representations.
8. **Iterative User Interaction:**
   - Develop an interactive platform allowing users to perform various tasks iteratively.
   - Ensure ease of use and accessibility for users with different levels of technical expertise.
These steps collectively form a robust and comprehensive process for sentiment analysis and data management within the application.
Sample Dataset:
 
 
Sample Output:
 
User Interface:
 
Visualization:
 
