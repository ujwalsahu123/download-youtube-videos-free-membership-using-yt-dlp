# download-youtube-videos-free-membership-using-yt-dlp

You can download a normal youtube video on your device esily using different platforms like apps (snaptube) and websites . 
<br>but<br>
Its almost impossible to watch or download a membership video for free . <br>
but there is a loop hole in the system - There are many youtube channels who provide paid membership videos and courses on youtube and instead of taking long time subsription you can take only 1 month subscription and download all the paid videos and then cancel the subscription . using this way you only need to pay for a single month of memebership . <br>
ex - a paid youtube course need 799 a month and the same content is for 5999 on the official that teachers course website . 
<br>
so instead of taking the entire course subscription for rs5999 , i took the 799 a month membership on youtube and then downloaded the entire paid content . so that i can watch it anytime later . 
<br>
<hr>
steps : <br>
download the yt-dlp which is a software to download youtube videos :  https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp.exe <br><br>
Install ffmpeg (Optional, but recommended)

Download https://github.com/yt-dlp/FFmpeg-Builds/releases/download/latest/ffmpeg-master-latest-win64-gpl.zip , checkout on google if link expires . 

Extract the files and find ffmpeg.exe and ffprobe.exe inside the bin folder

Copy those two files to the same folder as yt-dlp.exe
<br><br>
put all these 3 files on the same folder . open the file explorer and go to that folder . in the navigation bar of that folder write cmd and press enter . and a command line interface will open . 
<br> <br>
Then in the terminal window that opens, type <h4>yt-dlp "URL"</h4>replacing URL with the link u want to download.
<br> <br>
for downloading a membership video you need to have the membership of that channel /access the video . <br>
download the <h4>get cookies.txt locally</h4> chrome extention . now login in to chrome and youtube with membership email account . open youtube and go to that membership channel , now in click on the extention icon and click on the get cookies.txt locally - all cookies . now put the downloaded cookies.txt folder in the same folder as yt-dlp . <br>
open the cmd . and type > yt-dlp --cookies cookies.txt "URL" <br>
for 720 quality vedio at max you can do > yt-dlp --cookies cookies.txt -f "bestvideo[height<=720]+bestaudio/best[height<=720]" "URL". 
<br>
the cookies expires very quickly (15 min , i think) resulting into error . so for that you need to delete the cookie file and then again download it and put it in the folder . and the name of the cookie file should not be cookies(1) or etc . it should be cookies . 
