# TiffViewer
TiffViewer For ie, chrome and firefox browser

ie by default show the tiff files, so this code for recognize ie browser(true means ie and false means others):  

<code>
function msieversion()// this function for recognize ie from other browser  

{  
    var ua = window.navigator.userAgent;//inner commands  
    
    var msie = ua.indexOf("MSIE ");  
    
    if (msie > 0) // If Internet Explorer, return version number  
    
    {
    
		return true;
		
        //alert(parseInt(ua.substring(msie + 5, ua.indexOf(".", msie))));
	
    }  
    
    else  // If another browser, return 0  
    
    {  
    
		return false;  
		
        //alert('otherbrowser');  
	
    }  
    
    return false;
    
} 

</code>  


for load tiff in firefox and chrome used codes from bottom links:
https://github.com/seikichi/tiff.js/tree/master

this project is  html demo. download this project then extract and run "tiff All Browser.html" file and test it. it is work...
<a href="https://rasouliali.github.io/TiffViewer/" >online Demo</a>
