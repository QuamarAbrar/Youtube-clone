# Youtube-clone
# home page:
 # css:
 body{
    background-color: black;
    color: white;
}
.sidebar{
    display: inline-flex;
    flex-wrap: wrap;
    overflow-y: auto;
    width: 14%;
    height: 100%;
    left: 0;
    position: fixed;
    overflow-y: auto;
}
.ytlogo-text:hover{
    cursor: pointer;
}
.sidebar-icon{
    margin-top: 33px;
    margin-left: 20px;
}
.sidebar-icon:hover{
    cursor: pointer;
}
.sidebar-icony{
    margin-top: 28px;
    margin-left: 30px;
}
.sidebar-icony:hover{
    cursor: pointer;
}
.ytIn{
    font-size: x-small;
    text-align: right;
}
.ytIn:hover{
    cursor: pointer;
}
.home{
    width: 155px;
    height: 35px;
    margin-top: 10px;
    margin-left: 20px;
    margin-right: 30px;
    gap: 30px;
    display: inline-flex;
    border-radius: 5px;
    align-items: center;
}
.home img{
    margin-left: 10px;
}
.home:hover{
    transition: 0.2s;
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.sidebar-buttons{
    width: 155px;
    height: 35px;
    margin-top: 10px;
    margin-left: 20px;
    margin-right: 30px;
    gap: 30px;
    display: inline-flex;
    border-radius: 5px;
    align-items: center;
}
.sidebar-buttons a:link, a:visited, a:hover, a:active{
    color: white;
    text-decoration: none; 
    cursor: pointer;
}
.sidebar-buttons img{
    margin-top: 3px;
    margin-left: 10px;
    height: 21px;
    width: 21px;
}
.sidebar-buttons:hover{
    transition: 0.2s;
    background-color: rgb(99, 99, 99);
    cursor: pointer;
    color: white;
}
.linebreak{
    margin: 10px;
    height: 0.6px;
    width: 100%;
    background-color: rgb(99, 99, 99);
}
.sidebar-footer{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    font-size: 13.5px;
    margin-left: 7px;
    gap: 4px;
    margin-bottom: 10px;
}
.sidebar-footer a:visited, a:active, a:hover, a:link{
    color: rgb(173, 171, 171);
    text-decoration: none;
    cursor: pointer;
}
.page{
    display: flex;
    flex-direction: row;
    overflow-y: auto;
    flex-wrap: wrap;
    right: 0;
    margin-top: 25px;
    margin-right: 8px;
    position: fixed;
    width: 83%;
    height: 100%;
}
.search-bar {
  margin-left: 250px;
  border: 1px solid rgb(93, 93, 93);
  border-top-left-radius: 32px;
  border-bottom-left-radius: 32px;
  border-bottom-right-radius: 32px;
  border-top-right-radius: 32px;
  width: 125%;
  height: 45px;
  display: flex;
  align-items: center;
  overflow: hidden;
}

.search-bar input {
  color: #fff;
  flex: 1;
  border: none;
  height: 45px;
  width: 440px;
  padding: 10px 15px;
  background: linear-gradient(rgba(68, 68, 68, 0.6), rgba(68, 68, 68, 0.6));
}
.search-icon{
    width: 50px;
    height: 45px;
    background-color: rgb(68, 68, 68);
}
.search-icon:hover{
    cursor: pointer;
}
.search-icon img{
    margin-top: 10px;
    margin-left: 15px;
}
.navigation-bar{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    position: fixed;
    background-color: black;
    padding-bottom: 10px;
}
.mic{
    display: flex;
    margin-left: 25px;
    justify-content: center;
    background-color: rgb(68, 68, 68);
    border-top-left-radius: 32px;
    border-bottom-left-radius: 32px;
    border-bottom-right-radius: 32px;
    border-top-right-radius: 32px;
}
.mic:hover{
    cursor: pointer;
}
.mic img{
    margin: 10px;
}
.create{
    display: inline-flex;
    width: 220px;
    margin-left: 25px;
    justify-content: center;
    align-items: center;
    background-color: rgb(68, 68, 68);
    border-top-left-radius: 32px;
    border-bottom-left-radius: 32px;
    border-bottom-right-radius: 32px;
    border-top-right-radius: 32px;
    gap: 5px;
}
.create:hover{
    cursor: pointer;
}
.bell{
    display: flex;
    margin-left: 25px;
    justify-content: center;
    border-top-left-radius: 32px;
    border-bottom-left-radius: 32px;
    border-bottom-right-radius: 32px;
    border-top-right-radius: 32px;
}
.bell img{
    margin: 10px;
}
.bell:hover{
    background-color: rgb(68, 68, 68);
    cursor: pointer;
}
.account{
    display: flex;
    margin-top: 8px;
    margin-left: 25px;
}
.account:hover{
    cursor: pointer;
}
.account img{
    height: 33px;
    width: 33px;
    border-radius: 32px;
}
.categories{
    margin-top: 80px;
    display: flex;
    flex-direction: row;
    position: sticky;
    height: 35px;
    overflow-x: auto;
    overflow-y: hidden;
    gap: 5px;
    justify-content: center;
    align-items: center;
    margin-left: 10px;
    background-color: black;
}
.select-category1{
    display: inline-flex;
    height: 15px;
    width: 85px;
    background-color: white;
    color: black;
    border-radius: 9px;
    margin-left: 920px;
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 10px;
    justify-content: center;
}
.select-category1:hover{
    cursor: pointer;
}
.select-category2{
    display: inline-flex;
    height: 15px;
    width: 85px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category2:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category3{
    display: inline-flex;
    height: 15px;
    width: 100px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category3:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category4{
    display: inline-flex;
    height: 15px;
    width: 190px;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category4:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category5{
    display: inline-flex;
    height: 15px;
    width: 85px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category5:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category6{
    display: inline-flex;
    height: 15px;
    width: 85px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category6:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category7{
    display: inline-flex;
    height: 15px;
    width: 85px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category7:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category8{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category8:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category9{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category9:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category10{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category10:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category11{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category11:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category12{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category12:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category13{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category13:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category14{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category14:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category15{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category15:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category16{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category16:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category17{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category17:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category18{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category18:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.select-category19{
    display: inline-flex;
    height: 15px;
    width: auto;
    gap: 3px;
    background-color: rgb(68, 68, 68);
    border-radius: 9px;
    padding: 10px;
}
.select-category19:hover{
    background-color: rgb(99, 99, 99);
    cursor: pointer;
}
.video-section{
    display: inline-flex;
    flex-wrap: wrap;
    gap: 10px;
    overflow-y: auto;
    margin: 10px 10px 40px 10px;
    width: 370px;
    cursor: pointer;
    height: auto;
}
.video-card{
    display: flex;
    flex-direction: column;
    margin: 10px;
    width: 300px;
    cursor: pointer;
    height: auto;
}
.video-card h3{
    font-size: 20px;
    margin: 14px 0 0 0;
}
.video-card p{
    font-size: 15px;
    margin: 0 0 0 40px;
    color: rgb(173, 171, 171);
}
.video-card img{
    height: 24px;
    width: 24px;
    margin: 20px 5px 5px 5px;
    border-radius: 12px;
}
.video-info{
    display: flex;
    gap: 10px;
}

# html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youtube Clone by Quamar</title>
    <link rel="stylesheet" href="youtube.css">
    <link rel="shortcut icon" href="yotube icons and images/youtube-2.png">
</head>
<body>
    <div class="sidebar">
        <span class="sidebar-icon"><img src="yotube icons and images/hamburger.png" alt="hamburger icon" height="20px" width="20px"></span>
        <span class="sidebar-icony"><img src="yotube icons and images/youtube-2.png" alt="youtube logo" height="30px" width="34px"></span>
        <span class="ytlogo-text">
                <legend class="ytIn">IN</legend>
                <h2>YouTube</h2> 
        </span>
        <div class="home">
            <span><img src="yotube icons and images/home.png" alt="home icon" height="21px" width="21px"></span>
            <a href="youtube.html">Home</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/ytshorts.png" alt="shorts"></span>
            <p>Shorts</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/subscriptions.png" alt="subscriptions"></span>
            <a href="subscriptions.html">Subcriptions</a>
        </div>
        <div class="linebreak"></div>
        <div class="sidebar-buttons">
            <h3>You</h3><img src="yotube icons and images/side-arrow.png" alt="side arrow icon" height="21px" width="21px">
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/history-icon.png" alt="history icon" height="21px" width="21px"></span>
            <a href="history.html">History</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/playlist-icon.png" alt="playlist icon" height="21px" width="21px"></span>
            <a href="playlists.html">Playlists</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/video-icon.png" alt="video icon" height="21px" width="21px"></span>
            <a href="your_videos.html">Your videos</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/courses-icon.png" alt="courses icon" height="21px" width="21px"></span>
            <a href="your_courses.html">Your courses</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/watch-later.png" alt="watch later" height="21px" width="21px"></span>
            <a href="watch_later.html">Watch Later</a>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/like-icons.png" alt="like icons" height="21px" width="21px"></span>
            <a href="liked_videos.html">Liked videos</a>
        </div>
        <div class="linebreak"></div>
        <div class="sidebar-buttons">
            <h3>Subscriptions</h3><img src="yotube icons and images/side-arrow.png" alt="side arrow icon" height="21px" width="21px">
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub1.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Alan Becker</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub2.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Aspirant</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub3.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Yakeen</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub4.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Aakash JEE</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub5.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Aashish Solanki</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub6.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Abhi and Niyu</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sub7.jpg" alt="channels" height="21px" width="21px"></span>
            <p>Andre Antunes</p>
        </div>
        <div class="sidebar-buttons">
            <h3>Show more</h3><img src="images/down.png" alt="down" height="21px" width="21px">
        </div>
        <h3>Explore</h3>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/shopping-icon.png" alt="shopping bag icon"></span>
            <p>Shopping</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/music.png" alt="music icon"></span>
            <p>Music</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/clapperboard.png" alt="clapperboard icon"></span>
            <p>Films</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/live-icons.png" alt="live icons"></span>
            <p>Live</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/gaming-icon.png" alt="gaming icon"></span>
            <p>Gaming</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/news-icon.png" alt="news icon"></span>
            <p>News</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/sports-icon.png" alt="sports icon"></span>
            <p>Sport</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/courses-icon.png" alt="courses icon"></span>
            <p>Courses</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/fashion-icon.png" alt="fashion icon"></span>
            <p>Fashion & beauty</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/podcasts-icon.png" alt="podcats"></span>
            <p>Podcasts</p>
        </div>
        <div class="linebreak"></div>
        <h3>More from YouTube</h3>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/youtube-2.png" alt="youtube icon"></span>
            <p>YouTube Premium</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/youtube-studio.png" alt="youtube studio icon"></span>
            <p>YouTube Studio</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/youtube-music.png" alt="youtube music icon"></span>
            <p>YouTube Music</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/youtube-kids.png" alt="youtube kids icon"></span>
            <p>YouTube Kids</p>
        </div>
        <div class="linebreak"></div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/settings-icon.png" alt="settings icon"></span>
            <p>Settings</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/flag-icon.png" alt="flag icon"></span>
            <p>Report history</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/help-icon.png" alt="help icon"></span>
            <p>Help</p>
        </div>
        <div class="sidebar-buttons">
            <span><img src="yotube icons and images/feedbakc-icon.png" alt="feedback icon"></span>
            <p>Send feedback</p>
        </div>
        <div class="linebreak"></div>
        <div class="sidebar-footer">
        <div>
            <span><p><a href="#About">About</a></p></span>
            <span><p><a href="#Press">Press</a></p></span>
            <span><p><a href="#Copyright">Copyright</a></p></span>
        </div>
        <div>
            <span><p><a href="#ContactUs">Contact us</a></p></span>
            <span><p><a href="#Creator">Creator</a></p></span>
            <span><p><a href="#Advertise">Advertise</a></p></span>
        </div>
        <div>
            <span><p><a href="#developers"></a></p></span>
        </div>
        <div>
            <span><p><a href="#terms">Terms</a></p></span>
            <span><p><a href="#privacy">Privacy</a></p></span>
            <span><p><a href="#policy&saftey">Policy & Safety</a></p></span>
        </div>
        <div>
            <span><p><a href="#howytworks">How YouTube works</a></p></span>
        </div>
        <div>
            <span><p><a href="#newfeatures">Test new features</a></p></span>
        </div>
        <footer>© 2025 Google LLC</footer>
        </div>
    </div>
    <div class="page">
        <nav class="navigation-bar">
            <form class="search-bar">
            <input type="search" placeholder="Search" />
            <div class="search-icon"><img src="yotube icons and images/search-icon.png" height="22px" width="22px" alt=""></div>
            </form>
            <div class="mic">
                <img src="yotube icons and images/mic-icon.png" alt="mic icon" height="27px" width="27px">
            </div>
            <div class="create">
                <img src="yotube icons and images/icons8-plus-24 copy.png" alt="plus icon" height="21px" width="21px"><div>Create</div>
            </div>
            <div class="bell">
                <img src="yotube icons and images/bell-icon.png" alt="bell icon" height="25px" width="25px">
            </div>
            <div class="account">
                <img src="yotube icons and images/account-img.jpg" alt="account image">
            </div>
        </nav>
        <div class="categories">
            <div class="select-category1">All</div>
            <div class="select-category2">Music</div>
            <div class="select-category3">Gaming</div>
            <div class="select-category4"><span>Nusrat</span> <span>Fateh</span> <span>Ali</span> Khan</div>
            <div class="select-category5"><span>Ghazal</span></div>
            <div class="select-category6"><span>Checkmates</span></div>
            <div class="select-category7"><span>Mixes</span></div>
            <div class="select-category8"><span>Web</span> <span>Development</span></div>
            <div class="select-category9"><span>Object</span>-<span>oriented</span> <span>programming</span></div>
            <div class="select-category10"><span>Shankar</span>-<span>Jaikishan</span></div>
            <div class="select-category11"><span>Indian</span> <span>Institutes</span> <span>of</span> <span>Technology</span></div>
            <div class="select-category12"><span>AI</span></div>
            <div class="select-category13"><span>Guitar</span> <span>chords</span></div>
            <div class="select-category14"><span>Colleges</span></div>
            <div class="select-category15"><span>Keyboards</span></div>
            <div class="select-category16"><span>Abstract</span> <span>algebra</span></div>
            <div class="select-category17"><span>Kishore</span> <span>Kumar</span></div>
            <div class="select-category18"><span>Physical</span> <span>Chemistry</span></div>
            <div class="select-category19"><span>Test</span></div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/TJjKOouOHn8?si=37bCKAYakP0ATG-U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/gothamchess.jpg" alt="channel pfp"><h3>This 12-Year-Old chess prodigy left Hikaru speechless</h3></div>
                <p>GothamChess&#10004</p>
                <p>1M views • 1 month ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/CnQnJEj-Yxo?si=NUOzf46PvldBdR99" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/chess.com" alt="channel pfp"><h3>The best chess players over time</h3></div>
                <p>Chess.com&#10004</p>
                <p>5.6M views • 6 months ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/-wt9cQa7xW0?si=QXeiU5ipy1f45OdK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/bubblie.jpg" alt="channel pfp"><h3>Why GenZ is SECRETLY OBSESSED with this author?</h3></div>
                <p>The Bubblie</p>
                <p>990k views • 3 months ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/6Oy41wO0gE0?si=-Ae1gNenjPcYRpze" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/destination-faang.jpg" alt="channel pfp"><h3>Launching the ultimate system designing course</h3></div>
                <p>Destination FAANG</p>
                <p>6.7k views • 5 days ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/o_Ahgu1-zj4?si=DKdTmUos0HKdyeov" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/leetcode-profiles.jpg" alt="channel pfp"><h3>Gennady Korotkevich Biography: The Unstoppable King of Coding</h3></div>
                <p>Leetcode Profiles</p>
                <p>575k views • 1 year ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/Mn6GHMA8GIs?si=FFX0_8cvw0Az4KXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/gothamchess.jpg" alt="channel pfp"><h3>His Chess Literally BROKE Computers</h3></div>
                <p>GothamChess&#10004</p>
                <p>704k views • 1 month ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/BqSxjmvXzzY?si=BN1KuhEh6aCNA8_5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/facts.jpg" alt="channel pfp"><h3>57 Years Apart - A Boy And a Man Talk About Life</h3></div>
                <p>Facts.&#10004</p>
                <p>37M views • 9 years ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/Ti5vfu9arXQ?si=3C0ME-elkoPIq5MC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/lifeatgoogle.jpg" alt="channel pfp"><h3>How to solve a Google interview question</h3></div>
                <p>Life at Google&#10004</p>
                <p>1.1M views • 8 months ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/NtZaP8VMv0c?si=aulrDSNcRfI5YfPg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/steve-mould.jpg" alt="channel pfp"><h3>NASA tested my chain theory in space</h3></div>
                <p>Steve Mould&#10004</p>
                <p>6.7M views • 2 weeks ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/YEZHU4LSUfU?si=pKjMK-teVTPR6uAA" title="YouTube video player" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/sam-witteveen.jpg" alt="channel pfp"><h3>Deepseek OCR - More than OCR</h3></div>
                <p>Sam Witteveen</p>
                <p>188k views • 5 days ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/SmZmBKc7Lrs?si=SKGyIb-UAXuRtHvD" title="YouTube video player" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/artem-kirsanov.jpg" alt="channel pfp"><h3>The Most Important Algorithm in Machine Learning</h3></div>
                <p>Artem Kirsanov&#10004</p>
                <p>866k views • 1 year ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/Cc33wOBAKDM?si=ynR13eoF-rBCGP4X" title="YouTube video player" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/core-dumped.jpg" alt="channel pfp"><h3>Bit Shifting: The Hidden Trick Inside Your CPU</h3></div>
                <p>Core Dumped</p>
                <p>36k views • 1 day ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/pBASqUbZgkY?si=k-qyIXyMTuKE2W8_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/codist.jpg" alt="channel pfp"><h3>Every Type Of Api You Must Know Explained!</h3></div>
                <p>Codist</p>
                <p>290k views • 4 weeks ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/W145DXs8fFg?si=lfsLdzu_WoY_dLrk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/kunal-kushwaha.jpg" alt="channel pfp"><h3>OOP 4 | Access Control, In-built Packages, Object class</h3></div>
                <p>Kunal Kushwaha&#10004</p>
                <p>282k views • 3 years ago</p>
            </div>
        </div>
        <div class="video-section">
            <div class="video-card">
                <iframe width="360" height="215" src="https://www.youtube.com/embed/meEXag1XCFw?si=o-PQl6Y_vh39VAHP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                <div class="video-info"><img src="yotube icons and images/forest-knight.jpg" alt="channel pfp"><h3>Why Everyone's Switching to Rust (And Why You Shouldn't)</h3></div>
                <p>Forrest Knight&#10004</p>
                <p>250k views • 2 months ago</p>
            </div>
        </div>
    </div>
</body>
</html>
