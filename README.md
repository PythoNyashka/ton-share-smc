### ton-share-smc

Allows incoming transactions to be divided into two parts. Can be useful, for example, when you want to share profits with your partner. During initialization the share in percent of each of the two partners is set.

#### Build

```bash
func -SPA -o auto/simple-share-code.fif lib/stdlib.fc simple-share.fc
```