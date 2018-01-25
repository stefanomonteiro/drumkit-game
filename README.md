
# drumkit-game
---




I Made a game out of [Javascript 30 first video tutorial](https://youtu.be/VuN8qwZoego?list=PLu8EoSxDXHP6CGK4YVJhL_VWetA865GOH) by Wes Bos.


![Drum Kit Game](JS30_DrumGame.gif "Drum Kit Game")



### How the song animation works:

The `music` array is looped with a setTimeout function.

### The `music` array:

It contains sub-arrays, each sub-array represents one music note. The animation above is represented by the following `music` array:

```javascript
const music = [
  ['g', 71 , 3000],
  ['a', 65 , 4000],
  ['g', 71 , 5000],
  ['g', 71 , 5500],
  ['a', 65 , 6000],
  ['g', 71 , 7000],
  ['a', 65 , 8000],
  ['g', 71 , 9000],
  ['g', 71 , 9500],
  ['a', 65 , 10000]
];
```

* Where:
    - `music[0]` is a string of the keyboard key;
    - `music[1]` is the keycode for music[0];
    - `music[2]`is the delay for each animation from page restart;

Feel free to create your own music and become a Rock Star!

Share them using #javascript30!!!
