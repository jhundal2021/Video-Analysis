# Video-Analysis
Using Google Vision API this project will output the most frequent objects that show up inside a given video along with the adult likelihood ratings of the content. This was part of the development of the clickbait detection chrome extension tool that was undertaken at SLO Hacks.

To run the program, you'll need the Google Cloud API. Open your console to install the API using the following commands:

```
# Navigate to an empty directory
git clone https://github.com/insiyab/clickbait-detection-extension.git

# Download and copy your Google Cloud API JSON file into the directory
cp <api-file>.json clickbait-detect-extension/cloud-api.json

```
After this to run the program:

```
python3 analyze_video.py <path to the video>

```
