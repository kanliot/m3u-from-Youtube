# m3u-from-Youtube
Bash script to create m3u playlists from Youtube playlists or Youtube channels    
Requires `youtube-dl`

    Usage: m3ufromyt ./out.m3u

    Create a nice m3u file from an youtube url.
    a SINGLE youtube url will be prompted for..
    please don't redirect output.
    you should enter a youtube url at the prompt.
    Youtube urls to a playlist, or to channel/videos have been tested
    this script is slow on big channels.  about 1000 videos per hour
    option -r allows you to reverse the .m3u playlist
    option -q allows you to make this program quiet
    
## All .m3u files output will have these features: 
    For each video, an INFO line containing duration, date (U.S. order), and title of the youtube video.
    For each video, location of the content (as a url like http://www.youtube.com/watch?v=KViumtPd5RE ) 
    
#### What this script doesn't do is download videos, or give an .mp4 link to content like `youtube-dl --get-url`

requires Bash, etc. should run on any Linux. 
