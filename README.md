# Romance-of-the-Three-Kingdom-Network-Analysis

### Background and Research Question
The literary classic Romance of the Three Kingdoms by author, Luo Guanzhong, is one of the four great pillars of Chinese literature. The book is set in the third century and draws upon China’s history and folklore to create a story showing the era’s politics and social affairs. The book follows the ascent of Sima Yi who is part of the Han Dynasty. They identified themselves as China’s next rulers but have brought the empire to the brink war. 

Through strategies, conversations and fights for power we can trace the relationship between the 70 characters present throughout the book. From the various relationships we are curious to explore questions like: which characters like or dislike each other throughout the story? Would sentimental analysis identify certain relationships between characters from different countries? Would the relationship network change over time?

### Data Understanding 
The original book is written in Chinese. And there are vast amounts of English translations of the book. For our analysis, we collected our data from one of the existing translation on Github.  And the Github page also provides a list of 70 major character names. To provide detailed analysis for characters from different countries, we labelled each character for which country they are in based on history fact. 	

The primary approach we are using to define a relationship exists is by applying textual analysis. We first divide the sentences into tuples of three words. Then we created a function to compare the distance between two character names. If that distance is above a certain threshold, we define that relationship exists. This approach is intuitive to discern undirected relationships. We tried to build directed networks to better understand interactions between characters. But considering that it’s challenging to identify directed relationships based on verbs for subjunctive verbs, we decided to proceed our analysis based on undirected networks.
