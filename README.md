# BigQuery

#### By Chloe (Yen Chi) Le

#### Exploring BigQuery and Looker Studio

## Technologies Used

* Python
* Jupyter NoteBook
* SQL
* Github
* VS Code
* LookerStudio
* BigQuery 

## Description

Practice using client, creating datasets and tables with SQL and BigQuery.
Create data visualization on Looker Studio

For data visualization, I chose "Music and Mental Health Survey Result". The purpose of this survey is to identify, if any, correlations exist between an individual's music taste adn their self-reported mental health. The dataset can be found here: https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results

After working with the dataset, I found out that:

[<img src="./img/pie_chart.jpg" width='700'/>](./img/pie_chart.jpg)

  * Group 1: 75.5% of individual said that music improve their mental health
  * Group 2: 22.1% said there is no no effects
  * Group 3: 2.4% said music worsen their moods
  
I thought maybe the amount of hours they spend to listen to music or the BPM might be the cause, but none of them was right.
You can see the three images below. All of them spend about the same amount of hours to listen to music and the average BPM also the same.
  * Group 1
[<img src="./img/improve.jpg" width='700'/>](./img/improve.jpg)

  * Group 2
[<img src="./img/no_effect.jpg" width='700'/>](./img/no_effect.jpg)

  * Group 3
[<img src="./img/worsen.jpg" width='700'/>](./img/worsen.jpg)

## Setup/Installation Requirements

* Open the terminal and navigate to where you want to save the project
* git clone https://github.com/ChloeL6/Big-query.git, to save a copy of the project
* Do all the steps below to make and activate virtual environment, install all of the requirements and open the repo in VS code
    * python3.7 -m pip install --upgrade pip setuptools 
    * source venv/bin/activate
    * pip install -r requirements.txt
    * code .
* After VS Code open, go to main.ipynb to see codes for creating datasets and table

## Known Bugs

None

## License

Copyright (c) [2022] [ Chloe (Yen Chi) Le]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.