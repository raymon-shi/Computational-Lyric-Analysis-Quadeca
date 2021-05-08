## Data

These are all the notebooks that are related to the data collection and building the corpus for my computational text analysis.


The `loading_data.ipynb` notebook creates the `data` folder and its subfolder structure, searches for Quadeca's albums on Genius.com using the LyricsGenius API, scrapes the Billboard Top 50 Rap, and creates an appropriate JSON file for each respective album/chart.

The `describing_the_data.ipynb` notebook converts the JSON files a list of dictionaries format, where each list represents an album or a music chart and each dictionary represents the song details.

The `data` folder itself stores all the JSON files. All JSON files pertaining to Quadeca's earlier albums will be stored in the `before_insecre_albs` folder. All JSON files pertaining to Quadeca's larger albums will be stored in the `after_insecure_albs`. All JSOn files related tot he Billboard Top 50 Rap will be stored in the `mainstream_rap_bbt50` folder.