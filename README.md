# disableBackButton
hello guys , code for disabling back button is attached, Go through it

I have used simple javascript, which basically null the history for that particular file

js code is as below, 
```
history.pushState(null, null, location.href);
	    window.onpopstate = function () {
	        history.go(1);
	    };
```
Screenshot : 
      http://prntscr.com/k7fhz6
      
