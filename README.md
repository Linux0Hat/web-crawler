# Web Crawler

Web crawler explore the web and save every pages he found.

## Build

### Dependences

- `cmake`
- `ninja` or `make`
- `gcc`
- `sqlite3`
- `curl`
- `[SQLiteCpp](https://github.com/SRombauts/SQLiteCpp)` clone on /libs/SQLiteCpp

### Build

- **with Ninja :**

```
mkdir build
cd build
cmake -G Ninja ..
ninja
```

- **with Make**

```
mkdir build
cd build
cmake ..
make
```

## Use
```
web-crawler <url> --clear-waitlist
