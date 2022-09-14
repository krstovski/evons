# Evons
This repository that contains information on the Evons dataset described in the following paper:  
"Evons: A Dataset for Fake and Real News Virality Analysis and Prediction", Kriste Krstovski, Angela Soomin Ryu, and Bruce Kogut, COLING 2022.  

The dataset is organized into a single csv file (evons.csv) and two folders (articles and images).  

## evons.csv ##
The evons.csv file is accesible through the following link:  
https://www.dropbox.com/s/wlg1ugxz6vp8psv/evons.csv?dl=0

The file contains the following columns:
- **article_fn** -  Name of the file which contains the full article text. While the dataset contains articles from fake and real news sources, only filenames of fake news articles are present in this table as articles from real news sources where obtained from the "All the news 2.0" dataset (
https://components.one/datasets/).
Article files are provided in the **articles** folder where articles are organized into subfolders depending on the fake news media source. The folder is available for download as a articles.tar.gz file (please see the link below under the "Article Body Text" heading for a download link). 

- **fb_comments** - Number of Facebook comments.
- **fb_likes** - Number of Facebook likes.
- **fb_shares** - Number of Facebook shares.
- **fb_engagements** - Number of Facebook engagements. This is the sum of the previous 3 columns (number of shares, likes, and comments). It is used as a proxy of how much attention the post generated.
- **media_source** - news media source. We use the following abbreviations:
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
- **is_fake** - Does the media source contain fake or real news stories. "1" for fake and "0" for real. 
- **date** - News article date. 
- **title** - Article title.
- **description** - Article description with which the article was shared on Facebook.
- **is_valid_image** - Does the article contain a valid thumbnail image "1" for valid and "0" for invalid.
- **image_fn** - Thumbnail image filename. Thumbnail image files are provided in the **images** folder. Images are organized into sufolders depending on the news media source. This folder is available for download as an images.tar.gz file (please see the link below under the "Thumbnail Images" heading for a download link). 
- **dominantColorForeground** - Dominant foreground color attribute of the thumbnail image. 
- **dominantColorBackground** - Dominant background color attribute of the thumbnail image. 
- **dominantColors** - Set of dominant colors across the thumbnail image. 
- **accentColor** - Accent color, which is the most vibrant color in the thumbnail image.
- **isBwImg** - Is the thumbnail in black and white (bw) format. 
- **image_tags** - Set of extracted image attributes. 
- **num_face** - Number of detected faces in the thumbnail image. 
- **face_tags** - Set of extracted facial attributes. 

## Article Body Text ##
Article body text originating from the real news sources was obtained from the "all the news 2.0" dataset which is available through the following link:
https://components.one/datasets/all-the-news-articles-dataset. 
Article body text originating from the fake news sources is available for download through the following link:  
https://www.dropbox.com/s/wlg1ugxz6vp8psv/evons.csv?dl=0. 

## Thumbnail Images ##
Thumbnail images are organized into subfolders depending on the news media source. They are available for download through the following link:
https://www.dropbox.com/s/y4tc7gpuztdakgw/images.tar.gz?dl=0
