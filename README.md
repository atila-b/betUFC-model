# Bet UFC model
This project aims to implement a deep learning model to identify, through fighter statistics and fight history, which are the attributes that most lead a fighter to win.

To achieve this goal, statistics were collected from all active fighters on the UFC website using the web scraping technique. Another dataset of all UFC fights from 1993 to 2021 was also used.

Through the two mentioned datasets, the training dataset of the model was created, containing, for each fight, its result and the statistics of the two fighters.

The created model receives the statistics of the two fighters that will fight and returns a prediction of who will win.

For web scraping, the BeautifulSoup library was used.

To manipulate the neural network, the TensorFlow library was used.

## Results
The highest accuracy achieved until now by the model was approximately 71%.
