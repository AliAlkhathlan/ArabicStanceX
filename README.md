# ArabicStanceX
ArabicStanceX: A large-scale social media dataset for Arabic stance detection (14.5K tweets, 17 topics)
ArabicStanceX is a large-scale, richly annotated dataset for stance detection in Arabic social media text. It consists of 14,477 tweets covering 17 diverse topics across six domains: Sport, Education, Health, Religion, Economy, and Other.

Dataset Structure
The dataset is organized into two main folders:

train/

test/

Each of these folders contains six subfolders, one for each domain:

education/

sport/

health/

religion/

economy/

other/

Within each domain folder, there are topic-specific .json files.
Each .json file corresponds to a specific topic and contains a list of entries. Each entry includes:

ID: Unique identifier of the tweet

text: The Arabic tweet content

stance: The annotated stance label (favor, against, or none)

Citation
If you use this dataset in your research, please cite our paper:
