<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Top 100 Mondial</title>

<style>
body {
  font-family: Arial;
  background: linear-gradient(135deg, #00bcd4, #00ff99);
  color: white;
  text-align: center;
}

h1 {
  text-shadow: 0 0 10px black;
}

.container {
  width: 95%;
  margin: auto;
  background: rgba(0,0,0,0.35);
  padding: 15px;
  border-radius: 15px;
}

li {
  list-style: none;
  background: rgba(0,0,0,0.4);
  margin: 5px;
  padding: 8px;
  border-radius: 10px;
  text-align: left;
}
</style>
</head>

<body>

<h1>🌍🔥 TOP 100 MONDIAL 🔥🌍</h1>

<div class="container">
<ul id="list"></ul>
</div>

<script>

const classement = [
{r:1,n:"Sammy"},
{r:2,n:"Livier"},
{r:3,n:"Olivier"},
{r:4,n:"The Presence"},
{r:5,n:"One-Above-All"},
{r:6,n:"Zeno"},
{r:7,n:"Living Tribunal"},
{r:8,n:"Lucifer Morningstar"},
{r:9,n:"Grand Priest"},
{r:10,n:"Whis"},
{r:11,n:"Beerus"},
{r:12,n:"Darkseid"},
{r:13,n:"Doctor Manhattan"},
{r:14,n:"Galactus"},
{r:15,n:"Franklin Richards"},
{r:16,n:"Scarlet Witch"},
{r:17,n:"Goku"},
{r:18,n:"Vegeta"},
{r:19,n:"Gohan Beast"},
{r:20,n:"Broly"},
{r:21,n:"Jiren"},
{r:22,n:"Black Frieza"},
{r:23,n:"Naruto"},
{r:24,n:"Sasuke"},
{r:25,n:"Kaguya"},
{r:26,n:"Hagoromo"},
{r:27,n:"Madara"},
{r:28,n:"Obito"},
{r:29,n:"Hashirama"},
{r:30,n:"Minato"},
{r:31,n:"Itachi"},
{r:32,n:"Pain"},
{r:33,n:"Imu"},
{r:34,n:"Shanks"},
{r:35,n:"Teach"},
{r:36,n:"Luffy"},
{r:37,n:"Kaido"},
{r:38,n:"Big Mom"},
{r:39,n:"Mihawk"},
{r:40,n:"Akainu"},
{r:41,n:"Aokiji"},
{r:42,n:"Kizaru"},
{r:43,n:"Whitebeard"},
{r:44,n:"Zoro"},
{r:45,n:"Sanji"},
{r:46,n:"Law"},
{r:47,n:"Sabo"},
{r:48,n:"Ace"},
{r:49,n:"Hancock"},
{r:50,n:"Kid"},
{r:51,n:"Crocodile"},
{r:52,n:"Enel"},
{r:53,n:"Fujitora"},
{r:54,n:"Marco"},
{r:55,n:"Buggy"},
{r:56,n:"Thor"},
{r:57,n:"Doctor Strange"},
{r:58,n:"Hulk"},
{r:59,n:"Jean Grey"},
{r:60,n:"Loki"},
{r:61,n:"Magneto"},
{r:62,n:"Deadpool"},
{r:63,n:"Wolverine"},
{r:64,n:"Spider-Man"},
{r:65,n:"Superman"},
{r:66,n:"Flash"},
{r:67,n:"Wonder Woman"},
{r:68,n:"Batman"},
{r:69,n:"Saitama"},
{r:70,n:"Gojo"},
{r:71,n:"Ichigo"},
{r:72,n:"Aizen"},
{r:73,n:"Baptiste"},
{r:74,n:"Rimuru"},
{r:75,n:"Léo"},
{r:76,n:"Meliodas"},
{r:77,n:"Escanor"},
{r:78,n:"Kratos"},
{r:79,n:"Levi"},
{r:80,n:"Eren"},
{r:81,n:"Tanjiro"},
{r:82,n:"Ban"},
{r:83,n:"Natsu"},
{r:84,n:"Erza"},
{r:85,n:"Gintoki"},
{r:86,n:"Alucard"},
{r:87,n:"Kaneki"},
{r:88,n:"Edward Elric"},
{r:89,n:"Light Yagami"},
{r:90,n:"Ryuk"},
{r:91,n:"Sinbad"},
{r:92,n:"Neo"},
{r:93,n:"Morpheus"},
{r:94,n:"John Wick"},
{r:95,n:"Harry Potter"},
{r:96,n:"Voldemort"},
{r:97,n:"Gandalf"},
{r:98,n:"Frodo"},
{r:99,n:"Darth Vader"},
{r:100,n:"Luke Skywalker"}
];

const list = document.getElementById("list");

classement.forEach(c => {
  const li = document.createElement("li");
  li.textContent = "#" + c.r + " | " + c.n;
  list.appendChild(li);
});

</script>

</body>
</html>
