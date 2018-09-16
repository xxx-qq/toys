# Tetris

![](/screenshots/tetris.png)

### build & run
```bash
sudo apt-get install libsdl2-dev
g++ -std=c++1y tetris.cpp -lSDL2 -o tetris
./tetris
```

### keyboard

* &lt;Esc&gt; :  pause
* &lt;Enter&gt; : resume
* &lt;c&gt; : hold
* &lt;&#8592;&gt; : move left
* &lt;&#8594;&gt; : move right
* &lt;&#8595;&gt; : soft drop
* &lt;Space&gt; : hard drop