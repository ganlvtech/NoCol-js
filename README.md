# NoCol-js

Inspired by https://github.com/johnBuffer/NoCol

Remove colliding balls to "No Collision". This algorithm is not like the original algorithm which moves two balls tangent to each other when colliding.

## The acceleration of a ball

```plain
ax = -x * FACTOR;
ay = -y * FACTOR;
```

Force is targeting center and is proportional to distance.

It's just a simple harmonic motion. All balls have a same period.
