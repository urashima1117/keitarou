<!doctype html>
<html lang="ja">

<style>
  nav {
    background-color: #333;
    /* background-color: #f6e778; */

    overflow: hidden;
  }

  nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }

  nav li {
    float: right;
  }

  nav li a {
    display: block;
    color: white;
    /* text-align: center; */
    padding: 14px 16px;
    text-decoration: none;
  }

  nav li a:hover {
    background-color: #ddd;
    color: black;
  }

  .video-wrapper {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
  }

  .video-wrapper video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  body {
    margin: 0px;
  }
</style>

<body ID="pageIndex">


  <nav>
    <ul>

      <li><a href="https://aquajacket.tokyo/form/">Contact</a></li>
      <li><a href="#">Home</a></li>
    </ul>
  </nav>




  <div class="video-wrapper">
    <video id="my-video" muted autoplay loop playsinline>
      <source src="comingsoon_njb_20230404.mp4" type="video/mp4">
    </video>
  </div>



</body>

</html>
