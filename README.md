# Personality types in business

The idea behind this project was inspired by the documentary, "Persona:  The Dark Truth Behind Personality Tests."
This documentary explores the origins of the popular personality test, Myers-Briggs, developed by a mother and daughter who were inspired by Carl Jung's book, "Psychological Types."
I won't go into detail about the documentary here - you'll need to watch it for yourself.  However, the documentary made me wonder, "which personalities, if any, are more often successful in business?  Do certain personalities gravitate toward a particular field or industry?  Do some personalities make more money than others?
For this project, I decided to use a sample size of 50 people, and what better sample to use other than CEOs from the Fortune 50, the top 50 companies within the United States?
Unfortunately, finding people's Myers-Briggs' test results proved to be quite difficult.  So, for the sake of this project, I decided to substitute the Myers-Briggs test results with Zodiac signs instead, as these are much more accessible.
If you are unfamiliar with the Myers-Briggs personality types, you can read about them here:  https://www.myersbriggs.org/
Likewise, if you want to read up on the different Zodiac signs and their respective elements, go here:  https://cafeastrology.com/

Zodiac personality traits:
  - Aries - trailblazer; independent; competitive; blunt; short temper
  - Aquarius - individual/unique; believe in change and evolution; making the world a better place; idealist
  - Cancer - emotional; intuitive; can be prickly and standoffish; hates small talk; psychic
  - Capricorn - smart; hardworking; in control; stubborn; adept at making and investing money
  - Gemini - energetic and quick witted; smart; passionate; great communicator
  - Leo - bold; intelligent; courageous; natural leader; high self-esteem; proud
  - Libra - intelligent; kind; values harmony; appreciates aesthetics; diplomatic; daydreamer
  - Pisces - smart; creative; deeply intuitive; sensitive
  - Sagittarius - independent; strong-willed; leader; adventurous; generous
  - Scorpio - passionate; independent; authentic; intimidating; prickly exterior
  - Taurus - ambitious; trustworthy; stubborn; hard worker
  - Virgo - sophisticated; kind; practical; big-picture thinker; planner; smart

About the four elements:
  - Water signs: (cancer, scorpio, pisces) highly imaginative; creative; insightful
  - Air signs: (aquarius, libra, gemini) great communicators, good with data and information
  - Fire signs: (aries, leo, sagittarius) enthusiastic, bold, aggressive
  - Earth signs: (taurus, virgo, capricorn) hard workers, grounded, practical

This project was made using the following:
  -  Python 3.10.6
  -  Visual Studio Code
    - I used a Jupyter notebook within VScode (.ipynb file)
  -  You will need the following modules:
      -  pandas; matplotlib; seaborn
        - In your terminal:
          - pip install pandas
          - pip install matplotlib
          - pip install seaborn
        
  *To make it easier to read the CSV file to run the code, I recommend having the CSV file in the same directory as the .ipynb file.  Otherwise, you'll need to specify the path to the .csv for the Pandas csv_reader.  The .ipynb file and .csv are already packaged together for you in the folder "Project". Once you have cloned the repo and installed the modules (pandas,matplotlib/seaborn), all you should need to do is click "Run All".*
  
About the data used in this project:  
The Forbes Fortune 50 list can be found here:  https://fortune.com/fortune500/2022/search/  
As for the CEO's zodiac signs, I had to look each one up using Google.  The more well-known CEOs were easy to find but for the others, I had to look up their birthdays to determine their zodiac sign.  I also used Google to find their networth.  Then I compiled all the data into a CSV file.  The type of data found within the .csv file is mostly string values (Company name, Industry = type of company, CEO's name, CEO's zodiac sign and respective element type); the rest of the data is integer values - each CEO's networth.

This project implements the following features:  
  -  Read in data from a local csv
  -  Create custom function to clean/manipulate data (fix a typo and shorten industry names to fit on a graph; add dollar sign and commas to easier read monetary values)
  -  Perform more than 5 calculations (.sum(), .mean(), .median(), .mode(), calculate range, averages and percents)
  -  Create custom functions to operate on data (created sub-dataframes to determine most occuring sign within a particular element type)
  -  Visualize data using: made more than 2 different types of graphs using matplotlib and seaborn
  -  Incorporate markdown within the Jupyter ntoebook:  used markdown cells to describe the data being presented along with a brief conclusion at the end.
