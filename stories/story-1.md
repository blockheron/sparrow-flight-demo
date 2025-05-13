layout: page
title: "Story 1"
permalink: /sparrow-flight-demo/stories/story-1

<!DOCTYPE html>
<html>
    <!-- header -->
	<head>
        <!-- UPDATE TITLE -->
        <title>Story 1 | Sparrow Flight</title>

		<link rel="icon" type="image/png" href="../img/favicon.png">
        <link rel="stylesheet" type="text/css" href="../styles/global.css">
        <meta name="description" content="A story from the Flight.">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        
        <meta http-equiv='cache-control' content='no-cache, no-store, must-revalidate'>
        <meta http-equiv='expires' content='0'>
        <meta http-equiv='pragma' content='no-cache'>
        <iframe class="iframe-header" src="../html/header.html" width="100%" scrolling="no"></iframe>
    </head>
    
    <div class="container">

    <!-- UPDATE THIS FUNCTION PARAM!!! -->
    <body onload="storyButtons(1)">
    <table class="story-nav">
        <tbody>
        <tr>
        <td style="text-align: left; width: 40%"><p><a name="firstButton">First</a>&nbsp; &nbsp;<a name="prevButton">Prev</a></p></td>
        <td style="text-align: center"><p name="pageIndex"></p></td>
        <td style="text-align: right; width: 40%"><p><a name="nextButton">Next</a>&nbsp; &nbsp;<a name="lastButton">Last</a></p></td>
        </tr>
        </tbody>
    </table>

    <h2 class="story-title">Story 1: Demonstration for Webcomics with placeholder images</h2>
    <table style="width: 100%">
        <tbody>
        <tr>
        <td colspan="2">Published 14 Sep 2024</td>
        </tr>
        </tbody>
    </table>

    <p></p>
    <img src="https://gallery.eousercontent.com/45fed8ce-b513-11ef-8295-2d7ea4f395ef%2Fmedia-manager%2F1746332763062-Helvetia%20-%20Sleepy%20Sparrow.png">
    <p></p>
    <img src="https://gallery.eousercontent.com/45fed8ce-b513-11ef-8295-2d7ea4f395ef%2Fmedia-manager%2F1743362863040-SF%20-%20The%20Ugly%20Duckling%20title.jpg">
    <p></p>
    <img src="https://gallery.eocampaign1.com/45fed8ce-b513-11ef-8295-2d7ea4f395ef%2Fmedia-manager%2F1740070245637-tumblr_36fa5c6fb3dfd7aa6617248e59443305_89184237_2048.jpg">
    <p></p>
    <img src="../img/Helvetia - Rough Beginnings 4.png">
    <p></p>
    <img src="../img/Helvetia - Rough Beginnings 5.png">
    <p></p>
    <img src="../img/Helvetia - Rough Beginnings 6.png">
    <p></p>
    <img src="../img/Helvetia - Rough Beginnings 7.png">
    <p></p>

    <!-- story navbar -->
    <table class="story-nav">
        <tbody>
        <tr>
        <td style="text-align: left; width: 40%"><p><a name="firstButton">First</a>&nbsp; &nbsp;<a name="prevButton">Prev</a></p></td>
        <td style="text-align: center"><p name="pageIndex"></p></td>
        <td style="text-align: right; width: 40%"><p><a name="nextButton">Next</a>&nbsp; &nbsp;<a name="lastButton">Last</a></p></td>
        </tr>
        </tbody>
    </table>

    <!-- UPDATE PAGE_URL AND PAGE_IDENTIFIER!!! -->
    <div id="disqus_thread"></div>
    <script>
        /**
        *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
        *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
        
        var disqus_config = function () {
        this.page.url = "https://sparrowflightproject.web.app/stories/story-2.html";  // Replace PAGE_URL with the individual page's canonical URL variable
        this.page.identifier = "story-2"; // Replace PAGE_IDENTIFIER with your page's unique identifier variable (really just some ID)
        };
        
        (function() { // DON'T EDIT BELOW THIS LINE
        var d = document, s = d.createElement('script');
        s.src = 'https://sparrowflightproject.disqus.com/embed.js';
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

    <!-- <script id="dsq-count-scr" src="//sparrowflightproject.disqus.com/count.js" async></script> -->
    </div>

    <!-- footer -->
    <footer>
        <iframe class="iframe-footer" src="../html/footer.html" width="100%" height="325px" scrolling="no"></iframe>
    </footer>
    <script type="text/javascript" src="../scripts/global.js"></script>
</html>