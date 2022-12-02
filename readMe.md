
# Instagram Data Analyzer

A personal project to analyze my Instagram activity from 2016-2022 using Pythonic libraries.

#### -- Project Status: [Active]

## Project Objective
The purpose of this project is investigate my Instagram activity - post/reel comments, followers/following history, media likes etc.
#### -- Explored till now: [Instagram Post Comments]
 

## Project Description
The data used in this project is from my Instagram activity extracted from their website. More details on that below.
The questions that I have tried to answer from this project till now are : 
1. In which **year** have I been most active in comments section?
2. In which **month** have I been most active in comments section?
3. On what date do I usually comment the most?
## Installation

```bash
  pip install -r requirements.txt
```
    

## Getting Started
  You'll need to download your data to review it.
  - Go over to instagram.com on your PC and login to your account.
  - Click More in the bottom left, then click Settings.
  - Click Privacy and security.
  - Scroll down to Data download and click Request download.
  - Enter the email address where you'd like to receive a link to your data.
  - Click next to HTML or JSON to select the format you'd like to receive your data in, then click Next.
  - Enter your Instagram account password and click Request download.
  - You'll soon receive an email titled Your Instagram Data with a link to your data. Click Download data and follow the instructions to finish downloading your information.

For more info : [Downloading Instagram Data](https://help.instagram.com/181231772500920/?helpref=uf_share)
#### Instagram Post Comments Structure - Example
```json
{
  "comments_media_comments": [
    {
      "string_map_data": {
        "Comment": {
          "value": "@user This is a comment! The structure looks somewhat like this. \u00f0\u009f\u0098\u0082"
        },
        "Time": {
          "value": "Apr 19, 2017, 3:35 AM"
        }
      }
    },
		
	]
}
```

## Featured Notebooks/Analysis/Deliverables
* Charts added in 'visualizations' folder
* Presentation [to be added]
## Roadmap

- Integration of Streamlit
- Explore media related data
- Summarize understanding (ppt)

## License

[MIT](https://choosealicense.com/licenses/mit/)
