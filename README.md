# Fact-Ori
<p align="right">
 <img src="https://img.shields.io/github/last-commit/Shavvimal/Fact-Ori" />
 <img src="https://img.shields.io/github/issues/Shavvimal/Fact-Ori" />
 <img src="https://img.shields.io/github/languages/count/Shavvimal/Fact-Ori" />
 <img src="https://img.shields.io/github/languages/code-size/Shavvimal/Fact-Ori" />
 <img src="https://img.shields.io/tokei/lines/github/shavvimal/fact-ori" />
</p> 
 
This is the parent repo for a LAP-1 Group project: Fact-ori. This is a community fact sharing site that has the following functionality for users: 
- Users are able to visit the website and anonymously post fact entries.
- Users are able to add gifs from [giphy](https://developers.giphy.com/docs/api#quick-start-guide) in an entry using the giphy API.
- Users are able to view other peoples' entries.
- Users are able to be able to react to other peoples’ entries with an emoji.
- Users are able to have three emojis to choose from.
- Users are able to be able to comment on other people’s entries.

** Please note that a Mobile first design strategy has been undertaken, and due to the time contraint on the project, the mobile version is a lot more polished (although the desktop app is still made to be responsive). Please inspect and view from a mobile device for a better user experience.

The website is deployed using Netlify for client & Heroku for server. The data sent and stored in the backend is saved within .json files. Some funcitionality on the client side has been left as future features, such as the sort by, tags and shuffle facts. 

To docker compose: 

**Setup & Run**
- Clone repo & `cd` into folder
- `git submodule update --init`
- `docker-compose up` or `bash _scripts/start-containers.sh`

**Teardown**
- `docker-compose down --remove-orphans --volumes` or `bash _scripts/stop-containers.sh`