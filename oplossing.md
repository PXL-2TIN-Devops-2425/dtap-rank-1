Vul onderstaande aan met de antwoorden op de vragen uit de readme.md file. Wil je de oplossingen file van opmaak voorzien? Gebruik dan [deze link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) om informatie te krijgen over
opmaak met Markdown.

a)
We hebben een error gekregen toen wij de test.jenkinsfile wouden runnen. Het had geen permission om docker te runnen vanuit de jenkins server, dus we hebben de jenkins user 
toegevoegd in de docker group met het volgende commando:
sudo usermod -aG docker jenkins
En dan jenkins herstart met deze commando: sudo systemctl restart jenkins

