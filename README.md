# Youtube_playlist_scraper
This script, uses Youtube API V3 to extract data for each video in playlist, and uses playlist data to automate an online converter that downloads videos in mp3/mp4 format./n
#HOW IT WORKS /n
By providing an api-key (Google Cloud Platform), and enabling Youtube Api V3 (https://developers.google.com/youtube/v3), it allows script to iterate each video in playlist and extract important information such is:/n
- Tittle
- Date of Publishment
- Link
- Duration
- Views_Count
- Like_Count
- Coment Count
- Thumbnail

-After Collecting this information, script uses https://ytmp3.cc/uu129cc/ online converter and downloads all videos in mp3 format, then saves it in a folder in the same dir, so videos are converted by below page, and script interacts with that page through web automation with Playwright, so script acts like a real user.
-What is special about this project is that it uses asynchronous programing, in order to automate multiple browsers at the same time, in order to get a faster download process, so multiple browser sessions are being run at the same time./n

REQUIREMENTS: 
Playwright --- https://playwright.dev/python/docs/intro
|| GoogleApiClient --- https://pypi.org/project/google-api-python-client/
|| OpenPyXl ---https://pypi.org/project/openpyxl/
|| Requests --- https://pypi.org/project/requests/



