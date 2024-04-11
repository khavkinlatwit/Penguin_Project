# Penguin Report
##### By: Leo Khavkin


## Introduction
  

The project was undertaken to investigate several key questions regarding the physical attributes of penguins in the Palmer Archipelago, Antarctica. Firstly, the researchers sought to determine if there exists a correlation between the body mass and flipper length of the penguins within the dataset. Secondly, they aimed to ascertain whether a significant difference in body mass exists between the Adélie species and the chinstrap species of penguins. Lastly, the researchers endeavored to explore the correlation between flipper length and flipper depth among the penguins. Utilizing the comprehensive dataset available, the study aimed to provide insights into these specific relationships, contributing to a deeper understanding of penguin biology and ecology in the Antarctic region.


## Selection of Data

 The Palmer Archipelago, nestled within the frigid embrace of Antarctica, serves as a critical habitat for various species, including penguins. Studying these resilient inhabitants provides invaluable insights into the delicate ecosystems of the region and the broader impacts of climate change. The Palmer Archipelago Antarctica Penguin Dataset, available on Kaggle, encapsulates comprehensive data on penguin populations within this pristine environment. This dataset offers researchers, environmentalists, and enthusiasts a unique opportunity to delve into the lives, behaviors, and ecological dynamics of three penguin species: Adélie, Chinstrap, and Gentoo. With detailed measurements, observations, and metadata, this dataset serves as a cornerstone for diverse analyses, ranging from population trends and habitat preferences to the effects of environmental factors on these iconic Antarctic residents. Whether exploring patterns of migration, reproductive success rates, or anthropogenic impacts, the Palmer Archipelago Antarctica Penguin Dataset presents a rich tapestry of information, fostering deeper understanding and informed conservation efforts for these charismatic creatures and their fragile home.

## Methods

In addressing the research questions, the project utilized various materials and tools within Jupyter environment. These included essential libraries such as pandas for data manipulation, seaborn for data visualization, matplotlib.pyplot for creating plots, numpy for numerical computations, and scipy.stats for statistical analysis. However, before delving into analysis, it was imperative to preprocess the data due to the presence of null entries. Cleaning the data involved identifying and handling missing values appropriately to ensure the integrity and accuracy of subsequent analyses and findings.


## Results

#### Results for question 1:

  The analysis of variance (ANOVA) results indicate a highly significant relationship between body mass and flipper length of the penguins in the dataset. The F-statistic value of 175842808.7694842 is extremely large, suggesting a strong association between the two variables. Additionally, the p-value is practically zero (1.1102230246251565e-16), indicating that the probability of observing such extreme results by chance alone is exceedingly low. The study found a very strong correlation between body mass and flipper length among the penguins examined. This means that as the body mass of the penguins increases, there tends to be a corresponding increase in flipper length, and vice versa.

#### Results for question 2:


  The Two-sample t-test results suggest a highly significant difference between the body mass of the Adelie species of penguins and the Chinstrap species of penguins. The p-value of 2.220446049250313e-16 is extremely small, indicating that the probability of observing such a difference by chance alone is essentially zero. The study found a significant disparity in body mass between the Adelie and Chinstrap species of penguins. This implies that, on average, one species tends to have a noticeably different body mass compared to the other.

#### Results for question 3:

  The analysis using scipy.stats indicates a weak negative correlation between flipper length and flipper depth. The correlation coefficient of approximately -0.223 suggests that as flipper length increases, flipper depth tends to decrease slightly. However, the magnitude of this correlation is relatively low, with only 5% of the variance in flipper depth being explained by changes in flipper length. The study found a modest, negative correlation between flipper length and flipper depth among the observed penguins. This means that while there is a tendency for longer flippers to be associated with shallower depths, the relationship is not very strong.


## Discussion 

  The analysis of the Palmer Archipelago Antarctica Penguin Dataset yielded significant findings regarding penguin biology in the Antarctic region. Firstly, a strong correlation was found between body mass and flipper length, indicating a mutual relationship between these traits. Secondly, a notable difference in body mass between Adélie and Chinstrap penguin species suggests distinct physiological characteristics. Lastly, a weak negative correlation between flipper length and depth hints at subtle relationships in penguin morphology. These findings enrich our understanding of penguin ecology and underscore the importance of comprehensive datasets for conservation efforts. Future research could explore temporal changes, genetic factors, and ecological implications further.

##### Code

[Penguin Data ipynb](https://jupyter.cs.wit.edu/user/khavkinl/notebooks/Penguin.ipynb)

