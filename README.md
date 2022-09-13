# Evons
This repository that contains information on the Evons dataset described in the following paper:  
"Evons: A Dataset for Fake and Real News Virality Analysis and Prediction", Kriste Krstovski, Angela Soomin Ryu, and Bruce Kogut, COLING 2022.  

The dataset is organized into a single csv file (evons.csv) and two folders (images and articles). 

The evons.csv contains the following columns:
- **article_fn** -  Name of the file which contains the full article text. While the dataset contains articles from fake and real news sources, only filenames of fake news articles are present in this table as articles from real news sources where obtained from the "All the news 2.0" dataset (
https://components.one/datasets/).  
- **fb_comments** - number of Facebook comments
- **fb_likes** - number of Facebook likes
- **fb_shares** - number of Facebook shares
- **fb_engagements** - number of Facebook engagements. This is the sum of the previous 3 columns (number of shares, likes, and comments). It is used as a proxy of how much attention the post generated.
- **media_source** - news media source. 
  - mwn - MadWorldNews
  - psn - Puppet String News
  - usas - USA Supreme
  - ynw - YourNewsWire
  - bb4sp - Barracuda Brigade
  - aff - American Freedom Fighters
  - npr - National Public Radio
  - nyt - New York Times
  - reuters -  Reuters
  - Guardian - The Guardian
  - wp - Washington Post 
- **is_fake**
- **date**
- **title**
- **description**
- **is_valid_image**
- **image_fn**
- **dominantColorForeground**
- **dominantColorBackground**
- **dominantColors**
- **accentColor**
- **isBwImg**
- **image_tags**
- **num_face**
- **face_tags**
