# Hash Functions

- [Cryptogrphic hash function sandbox](https://emn178.github.io/online-tools/sha256.html)
- [How hashing algorithm work](https://metamorphosite.com/one-way-hash-encryption-sha1-data-software)

One critical characteristic of a secure cryptographic hash function is that it is one-way. 

Computing a hash should be fast and secure while finding the input for a hash should be very difficult and take a very long time.

Cryptographic hash function are essential to trust protocol by providing three main things: Uniqueness, avalanche effect, and speed. 

## Uniqueness

We can be assured the `string` we put in will always produce the same hash result. Hash collision happens when two input returns the same hash result. This is highly unlikely as our hash function produces a sufficiently large number of possibility.

## Avalanche Effect

Small changes on the target string for a hash function leads to outsized effects. A single change in the string will cause a successive series of changes that compound each other.

## Speed

Hash functions can neither be too fast nor too slow. A slow hash function causes delay, and it's easier to find collision with a fast hash function. A good hash function needs to balance speed and difficulty to be the perfect [Trapdoor Function](https://en.wikipedia.org/wiki/Trapdoor_function).

