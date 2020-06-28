# jwttack
Brute force JSON Web Tokens against a dictionary text file.

### Flags
---
```
--token: JWT token you want to use.
--file: Absolute path of the dictionary file (only .txt).
```

### Benchmarks
---
| Number of passwords      | Timing |
| ----------- | ----------- |
| 100K      | 34.92 seconds       |
| 380K      | 2 minutes |


### Build
---
Your must have node and yarn installed on your machine.
```
foo@bar:~$ git clone https://github.com/rramiachraf/jwttack
foo@bar:~$ cd jwttack
foo@bar:~$ yarn install
foo@bar:~$ node jwttack --token [TOKEN] --file [FILE]
```

