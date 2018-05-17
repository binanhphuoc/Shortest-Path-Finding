# Shortest-Path-Finding
Given a map, a start location and a destination, this program finds the shortest path between the two given locations.

## Example

[
<img width="845" alt="screen shot 2018-05-16 at 6 49 58 pm" src="https://user-images.githubusercontent.com/25260442/40149656-81732d9c-593a-11e8-8064-3740066ddb3d.png">
](url)

### Input map given as a text file: input.txt

```
A B 4
A C 3
A E 7
A Ann 0
B C 6
B L 5
C D 11
D L 9
D F 6
D G 10
E Chan 0
E G 5
F L 5
F Jan 0
Jan H 0
END OF INPUT
```

### Run with input.txt, start: A, end: G

```
./prog input.txt A G
```

### Result

```
distance: 12 km
route: 
A to E, 7 km 
E to G, 5 km 
```

