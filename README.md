# Google-Drive-API-Example
This is a quick example to get you set up with Google Drive API.

# Here are the steps needed:
- Go to this page: https://developers.google.com/drive/api/quickstart/python
- Create a Google Cloud project, as described by this video: https://youtu.be/I5ili_1G0Vk
- Create Oauth 2.0 consent screen as described by the same video
- Enable the API as described by the same video
- Download "credentials.json" as described by the same video
- Install the Google client library using the following command:
``` 
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib 
```

- Place your "credentials.json" file at the same directory as your code "quickstart.py"
- Run the quickstart Python program
- First time you will be redirected to a webpage to enter your username and password through the OAuth 2.0 window
- Make sure you add "credentials.json" and "token.json" to your .gitignore file

# Resources and References:
- https://developers.google.com/drive/api/quickstart/python
- https://console.cloud.google.com/
- https://youtu.be/I5ili_1G0Vk
- Drive API playlist: https://www.youtube.com/watch?v=9K2P2bWEd90&list=PL3JVwFmb_BnTamTxXbmlwpspYdpmaHdbz&index=1&ab_channel=JieJenn
- Google Drive API in Python: https://learndataanalysis.org/google-drive-api-in-python-getting-started-lesson-1/
- Oauth 2.0 Overview: https://youtu.be/CPbvxxslDTU
