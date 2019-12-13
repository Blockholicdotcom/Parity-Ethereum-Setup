# Welcome to Blockholic

The Repo is a part of our <b>Build your Private Parity PoA Ethereum Blockchain Network<b> Course.

If you get any error in parityGenesis.json file.<br>
```Spec json is invalid: data did not match any variant of untagged enum HashOrMap at line 57 column 1```

Please replace the below line with 

```"0x0000000000000000000000000000000000000008": { "builtin": { "name": "alt_bn128_pairing", "activate_at": 0, "pricing": { "alt_bn128_pairing": { "base": 100000, "pair": 80000,"eip1108_transition_base": 45000, "eip1108_transition_pair": 34000 } } } }```

with this

```"0x0000000000000000000000000000000000000008": { "builtin": { "name": "alt_bn128_pairing", "activate_at": 0, "pricing": { "alt_bn128_pairing": { "base": 100000, "pair": 80000} } } }```

You can check the mode details here
https://www.udemy.com/course/parity-ethereum/
