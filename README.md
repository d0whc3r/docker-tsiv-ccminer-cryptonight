# What is tsiv-ccminer-cryptonight?

tsiv-ccminer-cryptonight is a modification of Christian Buchner's & Christian H.'s ccminer project by tsiv for Cryptonight mining.

## Links

- [Discussion](https://bitcointalk.org/index.php?topic=656841.msg7487737#msg7487737)
- [Source Code](https://github.com/tsiv/ccminer-cryptonight)
- [Dockerfile](https://github.com/minecoins/docker-tsiv-ccminer-cryptonight)

# How to use this image

Run in background:

```console
$ docker run -td --name some-tsiv-ccminer-cryptonight minecoins/tsiv-ccminer-cryptonight -o stratum+tcp://monerohash.com:3333 -u 4GdoN7NCTi8a5gZug7PrwZNKjvHFmKeV11L6pNJPgj5QNEHsN6eeX3DaAQFwZ1ufD4LYCZKArktt113W7QjWvQ7CWBJdGgaYb2mTrUqjfM -p x
```

Fetch logs of a container:

```console
$ docker logs some-tsiv-ccminer-cryptonight
```

# Donations

Donations for work on dockerizing are accepted at:

- XMR: `4GdoN7NCTi8a5gZug7PrwZNKjvHFmKeV11L6pNJPgj5QNEHsN6eeX3DaAQFwZ1ufD4LYCZKArktt113W7QjWvQ7CWBJdGgaYb2mTrUqjfM`
