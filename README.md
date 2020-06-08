# WhigValues
A political quiz to determine which 19th century American party you align most with, Whigs or Democrats

<head>
<link href="https://fonts.googleapis.com/css?family=Montserrat:300,400,700|Roboto:400,700" rel="stylesheet">
<link href='style.css' rel='stylesheet' type='text/css'>
<title>8values</title>
<link rel="icon" type="x-icon" href="icon.png">
<link rel="shortcut icon" type="x-icon" href="icon.png">
<meta charset="utf-8">
<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<script>
  (adsbygoogle = window.adsbygoogle || []).push({
    google_ad_client: "ca-pub-6511426299019766",
    enable_page_level_ads: true
  });
</script>
</head>
<body>
<a href="https://github.com/8values/8values.github.io" class="github-corner" aria-label="View source on Github"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a><style>.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}</style>
<h1>8values</h1>
<hr>
<button class="button" onclick="location.href='instructions.html';" style="font-size:36pt;">Click here to start!</button>
<img src="values.svg" class="center"></img>

<h2>What is this test?</h2>
    <p>Inspired by 8values and other similar tests, WhigValues is a political quiz that attempts to match you with one of the two major parties of mid-19th century America, the Whig Party and the Democratic Party. This is done by asking a series of questions about your views on the major issues of the day. At the end of the quiz, you will be given a percentage that tells you which party your views better align with.<br /><br />
    There are <b><u><span id="numOfQuestions"></span></u></b> questions in the test.</p>

<h2>The parties</h2>
    <p>    <p>In addition to matching you to the eight values, the quiz also attempts to match you to a political ideology. This is a work in progress and is much less accurate than the values and axes, so don't take it too seriously. If you disagree with your assigned ideology, send us an email at eightvalues@gmail.com with your scores, matched ideology, and preferred ideology, and we'll look into adjusting the system. Thanks!</p>
<h2>I don't like my scores!</h2>
    <p>¯\_(ツ)_/¯<br/>
    If you have any suggestions or constructive criticism, feel free to send it to <a href="mailto:eightvalues@gmail.com">eightvalues@gmail.com</a> or open an issue on the GitHub page here: <a href="https://github.com/8values/8values.github.io">GitHub Page</a></p>

<!-- Website visit statistics - no personal information is collected! -->
<script type="text/javascript">
var sc_project=11325211;
var sc_invisible=1;
var sc_security="fd9f0659";
var scJsHost = (("https:" == document.location.protocol) ?
"https://secure." : "http://www.");
document.write("<sc"+"ript type='text/javascript' src='" +
scJsHost+
"statcounter.com/counter/counter.js'></"+"script>");
</script>
<noscript><div class="statcounter"><a title="web stats"
href="http://statcounter.com/" target="_blank"><img
class="statcounter"
src="//c.statcounter.com/11325211/0/fd9f0659/1/" alt="web
stats"></a></div></noscript>

<!-- This is the script for the page itself -->
<script type="application/javascript"src="questions.js"></script>
<script type="text/javascript">
    document.getElementById("numOfQuestions").innerHTML = questions.length;
</script>
</body>
