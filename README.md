# DOM-XSS

## What I have learned from Hacksplained’s DOM XSS

- In the search bar, key in <iframe src="javascript:alert(`xss`)">. Here firefox is in the Inspect mode

<img src="https://i.imgur.com/HfQPmdt.png" width="400" />

*Ref 1: Search Bar*

- Hit Enter

<img src="https://i.imgur.com/ualwCZs.png" width="400" />

*Ref 2: 127.0.0.1 says xss*

- In Elements tab, Ctrl-F to invoke Search. Search for iframe. Attacker has successfully inserted iframe in DOM (a no-no).

<img src="https://i.imgur.com/zmVoenV.png" width="400" />

*Ref 3: Iframe in DOM*
