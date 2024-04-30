# youtube_api
get DataFrame of videos you interested in and it's comments with replies in second DataFrame for further analysis
you need to have your own youtube API_KEY for this code to work
you can easily get it from https://console.cloud.google.com
If you are going to use youtube api once or twice i recommend you to not use Oauth 2.0 and just get api_key
Also, problems may arise depending on how many videos and comments you are going to get. You may run out of quotas, which you can also get from https://console.cloud.google.com
The purpose of my code was to analyze the opinion of commentators to import substitution (импортозамещение) for further analysis, this code was used for mining comments and replies to this comments (since it's a different thing for youtube API)
All the details you can easily get from https://developers.google.com/youtube/v3/docs
