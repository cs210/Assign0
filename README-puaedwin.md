## Introduction
Hello! My name is Edwin Pua. I'm currently coterming in CS under the AI track, but I also love making software, data engineering/analytics, and biotech. Hobbywise, I love indie games, iyashikei media, and walking around Stanford. Thanks for stopping by! ( ﾟヮﾟ)/

P.S. Feel free to add me on LinkedIn ([https://www.linkedin.com/in/edwin-pua/](https://www.linkedin.com/in/edwin-pua/)). I accept all connections (⊙_⊙ )

## Projects

1. **Designed an AI to play the video game "Downwell" by itself and beat the first level**

![Downwell Selfplay](https://i.ibb.co/5Rcd3F0/image19.gif)

- Demo: https://youtu.be/VjBtvJXVRnM
- Report: [http://cs230.stanford.edu/projects_fall_2022/reports/111.pdf](http://cs230.stanford.edu/projects_fall_2022/reports/111.pdf)

Here, I trained a recurrent neural network that accepts gameplay frames as input, tries to recognize objects and enemies in the gameplay frames, and outputs corresponding keyboard presses! I did this using a combination of YOLOv5 object detection, Keras, and lots of Python scripts. Notice that the AI adopts some human behaviors, like shooting and bouncing on enemies.

2. **Scraped, extracted, and analyzed web data from online sources and PC Gaming Client Steam to build machine learning model**

![Genre Buckets](https://i.ibb.co/QKxqchw/7.png)

- Report: [https://colab.research.google.com/drive/1I_guplf3j_yzks9F2GJ3MvYrdb15dcva](https://colab.research.google.com/drive/1I_guplf3j_yzks9F2GJ3MvYrdb15dcva)

For those that don't play games, Steam is a popular PC gaming client, where users can play games and leave reviews. Here, I analyzed which features potentially related to high user review scores (genre, price, release date) and built a machine learning model that tries to predict review score based on these input features. 

The above image showcases how games that are cute are higher rated than games that are gorey, and games that have cats are higher rated than games with dragons!

3. **Examined the nuclei of rabbit corneas and applied computer vision techniques to find cancerous cells**

![Cornea](https://i.ibb.co/s9dgdd2/corena.png)

Here, I applied computer vision techniques to remove background noise, sharpen nuclei edges, convert the image to a binary mask, and use image segmentation like Otsu's thresholding and watershed to separate cells. 

After finding the boundaries of each cell, I found which nuclei belonged to cancerous cells by comparing the intensity/brightness of the nucleus to the intensity/brightness of the cytoplasm and checking if the ratio exceeds 1.

## Experience

![Quotient](https://i.ibb.co/8067csL/quotient.png)

I've worked at Quotient Technology as a data engineer. These are the guys that own coupons.com! Here are some of the cool stuff I did:

- Identified frequently unused tables by querying table metadata via SQL scripts in Python, saving the company
500+ TB in storage and reducing costs by $10,000+/month.
- Utilized SQL on Google BigQuery to analyze transactional data, detecting anomalies (e.g. missing data or unusual
sales patterns) using z-scores and BigQuery’s built-in ML packages.
- Implemented a user-friendly in-house website using HTML and JavaScript to report anomalies identified during
data analysis.
- Collaborated with the data science team to create Python scripts that efficiently splits BigQuery dimension tables
into smaller parquet files.
- Became proficient in Apache Airflow, designed and implemented Directed Acyclic Graphs (DAGs) to automate the
above anomaly detection and parquet-splitting processes.

## Technical Skills

- Languages: Python, C++, Java, C, SQL (BigQuery), JavaScript, HTML, CSS
- Developer Tools: GitHub, VSCode, PyCharm, Eclipse, Android Studio, Airflow, MATLAB, AWS
- Coursework: Data Structures, Algorithms, Deep Learning, Computer Vision, Computer Graphics, Data Systems,
Object Oriented Programming, Web Programming, Natural Language Processing, Biocomputation

____

Again, thanks for stopping by! I'm looking forward to meeting and working with you all.