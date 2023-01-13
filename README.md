<div align="center">
  <img src="https://github.com/tiagodgy/ezBoard-Public/blob/main/images/ezboard_logo_background.png?raw=true" width="300">
</div>
<br><br/>

ezBoard is my first full-stack project that is in production. I was the sole developer on this project, and it took me 5 months to go from the initial MVP to its release on the Google Play Store and receiving permission to distribute it on the Android TV store.

The idea to develop this app came to me while I was talking to a relative about how expensive hardware like the Raspberry Pi has become in recent years. I had the idea to develop an app for Android TV OS that wouldn't require any additional hardware to run on most smart TVs, and even on "dumb" TVs, users can buy a TV box device like the Xiomi Stick 4k for less than $50, which can provide even better performance compared to most smart TVs.

For the front-end, I used React JS for the web app and React Native for the Android TV app. To build the institutional website, I used WordPress since it offers a lot of plugins for SEO and customer service. For CSS styles, I used TailwindCss.

For the backend, I used Pocketbase hosted on Fly.io using Docker. Initially, it was challenging to integrate it with the front-end since it is a new tool on the market and completely open-source, there is not a lot of information available on the internet. However, the GitHub discussion is very active. A shout-out to ganigeorgiev, one of the project's maintainers, who helped me make real-time requests work on React Native.

For me, the hardest part of this project was making it available for Android TV. Google's team is very concerned with the quality and compatibility of Android TV apps distributed on the Google Play Store. I had to compile more than 20 versions before it was approved for distribution.
<hr/>
<a href="https://ezboard.tech/" align="center">
    <p style="font-size: 100px;">ezBoard.tech</p>
  </a>
<hr/>
<div align="center">
  <a href="https://play.google.com/store/apps/details?id=com.test.ezBoard">
    <img src="https://github.com/tiagodgy/ezBoard-Public/blob/main/images/google_play_tag.png?raw=true" width="300">
  </a>
</div>


