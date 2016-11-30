# TiffViewer
TiffViewer For ie, chrome and firefox browser

ie by default show the tiff files, so this code for recognize ie browser(true means ie and false means others): 

<code>
function msieversion() 
{
    var ua = window.navigator.userAgent;
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

for load tiff in firefox and chrom used codes from bottom links:
https://github.com/seikichi/tiff.js/tree/master

demo upload in this "tiff All Browser.html" file download and test it. it is work...
