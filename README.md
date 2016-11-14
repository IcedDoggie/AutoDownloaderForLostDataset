# AutoDownloaderForLostDataset
Currently supports video downloading and tracks'file downloading only. The downloader is built with python.

# User Manual
To use it, you can copy the python files to designated folder. Target your cmd at the folder and run "python <filename.py>" (example: python AutoDownloadVideo.py).  
  
Format : python AutoDownloadTracks.py (year) (month) (day) (number of videos to download) (camera's id/camera's number) 
Example: python AutoDownloadTracks.py 2013 1 1 100 001 
  
NOTE: spacing is important!  
# Tunables
Tunable variables in this script includes:  
(1) currentDay : specifying the day that you wish to start with  
(2) currentMonth : specifying the month that you wish to start with  
(3) currentYear : specifying the year that you wish to start with  
(4) pointerDay : the starting position in the array(eg :if you choose the 8th day in the month, this pointer should be 7.)  
(5) pointerMonth : the starting position in the array(eg :if you choose the 4th month in the year, this pointer should be 3.)  
(6) cameraNo : the id of the camera  
(7) counter : setting how many files to download  


