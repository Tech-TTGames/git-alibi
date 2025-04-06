# git-alibi
Create a Trusted Timestamp Authority note for each git commit and store it in `git notes --ref=alibi`.

## Configuration
```
TSA="https://freetsa.org/tsr"
TSA_CERT="cacert.pem"
```
Set the above variables in the post-commit script to your preferred Time Stamp Authority, and it's certificate.


Made by Tech. TTGames for no reason at all.

Licensed under the AGPL-3.0.