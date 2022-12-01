# DaVinciResolve-DateToTimecode

Can change the Timecode metadata of DaVinci Resolve files from Date Changed/Date Modified.

Useful when you have a camera battery dying and then all your other cameras are off sync.

Features: 


-Conversion to Timecode


-Preview examples of your changes


-Offset the time to move the time forward or backwards  

ex. time zone is est but camera is stuck at pst; then you can offset forward 3 hours to match time.


-Subtract Duration of clip from time modified or created..  

cameras often stamp the time after the media has ended, this will subtract the duration from the time modifed or created.  
this would make camera times more accurate.    

ex. recording started at 12:00 PM and has recorded for 25 minutes.. now the timestamp for the Date Created is now 12:25 PM.   

when subDuration is True then Date Created = 12:00 PM


-Debug/Error


Code should work, but make a backup project just in case.
