
# Untangle Internship (Review Engine)
# Team - Ninja
# Visvesh, Lahar, Surendar (Lead)

This is a review application which describes how the game is performing in the market based on user experience by considering various constraints such as appid, votes_up, reviews, weighted_votre_score, play_time, num_reviews, etc.




## Authors

- [@visvesh123](https://www.github.com/visvesh123)
- [@venkatsurendar](https://www.github.com/venkatsurendar)



## Demo
The entire architecture is well designed and deployed successfully in AWS cloud platform. 
- Frontend: https://main.d2ahhc6j3xld17.amplifyapp.com/
 
- (Backend) Yeak model: http://3.110.113.63:5000/trending_keywords/597970
- (Backend)	Main Flask app: http://52.66.244.63:8000/avg_rating/597970 
- StreamLit : http://3.110.165.21:8501/



## Tech Stack

**Client:** React.js & Streamlit

**Server:** Flask

**ML Models Involved:** Sentimental analysis, keyword Extraction (NLP) along with statistics.

## Various sources links

 - [Client Github Repo](https://github.com/visvesh123/untangle_client.git)
 - [Flask Github Repo](https://github.com/visvesh123/UntangleIntern.git)
 - [Yake API Repo](https://github.com/visvesh123/keybert.git)
 - [SteamLit Repo]()
 - [Presentation Slides]( https://app.pitch.com/app/public/player/9e500ac4-c37c-4bc1-815c-74ee72e926ec)


## Installation


- For YAKE & Main Flask repo:
1. Please clone all the listed applications from provided GitHub links.
2. Make sure you are updated with python and pip
3. Create pipenv and install all the dependencies.
4. Run the app.py file for output.
5. Please test API’s in web-bowser with providing an appid if required. (ex: http://127.0.0.1:8000/avg_rating/597970)


- For React app:
1. Clone and direct to the folder until /src
2. Now run “rpm install”
3. The run “rpm start”
4. Note: Both Flask and YEAK servers must be running in-order to view frontend.

- For Streamlit:
1. Clone and direct to the folder
2. Run “streamlit run app.py”
3. Make sure the excel/csv files required are there within the folder.
## Feedback

If you have any feedback, please reach out to us.
Hope this helps, else please connect us anytime.
- Surendar - venkat18563@mechyd.ac.in
- Visvesh - visvesh18568@mechyd.ac.in
- Lahar - sailahar18569@mechyd.ac.in

