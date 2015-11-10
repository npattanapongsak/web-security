Cross-site scripting 

cross-site scripting is a type of computer security vaulnerability. Attackers find a way to execute his/her javascript code on to target website

Example

- GET parameter dose not encrypt

```
ex. http://targetwebsite.com?name=<script src='attacker.js'></script>
```
- Form data does not encrypt 

```
ex. POST
http://targetwebsite.com

firstname=<script src='attacker.js'></script>

lastname="dale"
```

Scenario
- attackers get the vulnerable url 
- attackers send email with this url to lure victim to click on the link
- victim click on the link, attackers' script run and get cookies data, user info etc..
