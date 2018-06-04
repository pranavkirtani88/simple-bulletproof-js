# simple-bulletproof-js
javascript code for one-round,single range-proof bulletproof for *secp256k1* elliptic curve.

Proof of concept code based on first version of https://eprint.iacr.org/2017/1066.

_To run_: 1) npm install. 2) node bulletproof_single.js

_NPM packages_: elliptic, big-integer.

To configure value and range: (a) change value inside controller() and (b) change bound in Consts.js.  

Verifier should return true if OK. 