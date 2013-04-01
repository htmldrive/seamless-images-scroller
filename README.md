Seamless images scroller with jquery plugin
=======================


[![Seamless images scroller with jquery plugin](http://www.htmldrive.net/media/2010/8/3/1280821066.png "Seamless images scroller with jquery plugin")](http://www.htmldrive.net/items/demo/284/Seamless-images-scroller-with-jquery-plugin "Seamless images scroller with jquery plugin")

[**Demo**](http://www.htmldrive.net/items/demo/284/Seamless-images-scroller-with-jquery-plugin "Seamless images scroller with jquery plugin")

##Usage
**Include js and css files.**

    <link href="css/scroller_roll.css" rel="stylesheet" type="text/css"></link>
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
    <script type="text/javascript" src="js/scroller_roll.js"></script>
  
**Add html.**

    <div id="scroller_roll1" class="scroller_roll">
        <ul>
            <li><a href="link1" title="title1"><img src="images/slideshow_large_1.jpg" width="60" height="60" alt="title"/></a></li>
            <li><a href="link2" title="title2"><img src="images/slideshow_large_2.jpg" width="60" height="60" alt="title"/></a></li>
            <li><a href="link3" title="title3"><img src="images/slideshow_large_3.jpg" width="60" height="60" alt="title"/></a></li>
            <li><a href="link4" title="title4"><img src="images/slideshow_large_4.jpg" width="60" height="60" alt="title"/></a></li>
        </ul>
        <div style="clear: both"></div>
    </div>
        
**Add startup script.**

    <script language="javascript" type="text/javascript">
        $(function() {
            $("#scroller_roll1").scroller_roll({
                title_show: 'enable',//enable  disable
                time_interval: '15',
                window_background_color: "#C1F0FF",
                window_padding: '1',
                border_size: '1',
                border_color: '#0099CC',
                images_width: '75',
                images_height: '70',
                images_margin: '5',
                title_size: '12',
                title_color: 'black',
                show_count: '3'
            });
        });
    </script>