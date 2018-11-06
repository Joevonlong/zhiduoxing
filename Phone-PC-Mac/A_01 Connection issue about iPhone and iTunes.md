# A_01 Connection issue about iPhone and iTunes

## Issue

iTunes cannot read content of iPhone. connection faild. 
> iTunes cannot read the contents of the iPhone "*** iPhone". Go to the Summary tab in iPhone preferences and click Restore to restore this iPhone to factory settings.

## Solution
**find system file of iPhone, "iTunesCDB"**

path: *iTunes_Control/iTunes/iTunesCDB*

delet: file **iTunesCDB**

- Stpe 1

	find a file management tool that can read iPhone system file.
	(e.g. iFunBox)
	
- Step 2
	
	connect your iPhone to your Mac/PC,  
	close the iTunes,  
	open file management tool,  
	find the path : User system/iTunes_Control/iTunes/iTunesCDB
	
- Step 3

	delet file "iTunesCDB"

- Step 4

	reconnect to iTunes,   
	your iTunes should read your iPhone content again.  



### References
> https://www.fonecope.com/itunes-cannot-read-the-contents-of-the-iphone.html
>
> https://www.guidingtech.com/fix-itunes-cannot-read-iphone/
> 
> https://discussions.apple.com/thread/4023862
> 
> >Video: https://www.youtube.com/watch?v=RyeGhFW8fgI

