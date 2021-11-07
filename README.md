# Live-Cricket-Score
Checkout here (http://livecricket.rf.gd/)
Basically Its a webpage that first fetches data with help of PHP arrays displays live cricket score .Fetches data using API, technologies used - CSS,HTML,JS,PHP.

## Technologies Used
1. [infinityfree.net] (https://app.infinityfree.net/)One of those websites which provides free domainname,hosting and probably SSL certificates too & i hosted the webpage here.

2. Programming Languages used: HTML,CSS,JS,PHP

3. [XAMPP]: It works like an localhost which is basically used to store and test our code.

## Output
![Output](livecricket.jpg)
 
## Make sure to make following changes in index.php file
```
  $data=file_get_contents('https://cricket-api.vercel.app/cri.php?url=https://www.cricbuzz.com/live-cricket-scores/38137/40th-match-super-12-group-2-icc-mens-t20-world-cup-2021');

//change the link provided after keyword 'url' that is visit cricbuzz website check live match going on cricbuzz and paste it after after keyword 'url'.



