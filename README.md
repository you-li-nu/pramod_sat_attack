Prof. Pramod Subramanyan's original SAT attack on HOST'15.

```
cd bin
./sld ../benchmarks/rnd/c880_enc50.bench ../benchmarks/original/c880.bench
./lcmp ../benchmarks/original/c880.bench ../benchmarks/rnd/c880_enc50.bench key=000000110011111011100110110100001001000100000001000010111010001100111111100100001101000010111000010000010011110000111111011001010000001110110011101011111010010100010101110000010110000110000101

```

UFlorida's SAT and AppSAT attacks.

```
sudo apt-get install libboost-all-dev
```

```
./neos -d ex ../benchmarks/nangos/seq.bench ../benchmarks/nangos/seq_skew10_enc.bench

./neos -d app ../benchmarks/nangos/seq.bench ../benchmarks/nangos/seq_skew10_enc.bench 2048 1 1 1 2048

```
