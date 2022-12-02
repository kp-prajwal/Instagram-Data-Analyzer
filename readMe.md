
# Instagram Data Analyzer

A personal project to analyze my Instagram activity from 2016-2022 using Pythonic libraries.

#### -- Project Status: [Active]

## Project Objective
The purpose of this project is investigate my Instagram activity - post/reel comments, followers/following history, media likes etc.
#### -- Explored till now: [Instagram Post Comments]
 

## Project Description
The data used in this project is for my
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)


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
