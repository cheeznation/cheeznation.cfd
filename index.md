<audio controls autoplay>
  <source src="The Cooking Channel.ogg" type="audio/ogg">
  <source src="The Cooking Channel.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Cheez Nation
# Your source for Cheez News, Cheez Videos, Cheez Streams and more


Hello there, you have reached the official Cheez Nation website ran by Cheez Headquarters. This website here will update you on the many Cheez Nation situations, news and more.
As of right now, the website is still being heavily worked on, but fret not, Cheez Interns and Kit are working on it.



# CHEEZ YOUTUBE 

Want to see the latest video from Cheez Headquarters? Look no further, enjoy the content.

Coming soon is more!


# CHEEZ TWITCH

See if Cheez Headquarters is live to the Cheez Nation, with Cheez Entertainment block!

<script src= "https://player.twitch.tv/js/embed/v1.js"></script>
<div id="gongle"></div>
<script type="text/javascript">
  var options = {
    width: 560,
    height: 315,
    channel: "cheeznationblehh",
    // only needed if your site is also embedded on embed.example.com and othersite.example.com
    parent: ["cheeznation.cfd", "cheeznation.github.io"]
  };
  var player = new Twitch.Player("gongle", options);
  player.setVolume(0.5);
</script>
# CHAT WITH OTHER CHEEZ NATION FANS
[Click here](https://cheeznation.cfd/IRC/)

# READ THE CHEEZ BLOG

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


