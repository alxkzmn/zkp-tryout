# zkp-tryout

A part of my exploration of Zero-Knowledge Proofs, following the https://www.shirpeled.com/2018/09/a-hands-on-tutorial-for-zero-knowledge.html

To construct the witness run:

```
python -c 'import zkp; print zkp.get_witness([4,11,8,1],[1,-1,1,-1])'
```

To construct a naive witness without any obfuscation override the default argument values:

```
python -c 'import zkp; print zkp.get_witness([4,11,8,1],[1,-1,1,-1], side_obfuscator=1, shift=0)'
```
