Gruppeinnlevering 1: IS-118, Høst 2026
======================================
# Oppskrift på Git
1. Hent ned repoet med kommandoen `git pull git@github.com:umbraqqw/is118-innlevering.git`
2. Gjør endringer på filen "besvarelse.md" i IDE (eks. VSCode, VSCodium, Vim). [Cheatsheet for Markdown](https://www.markdownguide.org/cheat-sheet/)
3. Åpne terminalen
    - I VSCode: Terminal -> New Terminal
4. Lag din egen branch 
    1. Med kommandoen: `git switch -c <brukernavn>-<navn-paa-branch>`
    2. Eller med kommandoen: `git branch <brukernavn>-<navn-på-branch>` og `git switch <brukernavn>-<navn-på-branch>`
5. Bruk kommandoen `git status` for å få opp hvilke filer du har gjort endringer på
6. Legg til filen(e) du ønsker å pushe med `git add <navn-på-fil>`, f.eks. `git add besvarelse.md`
7. Lag en commit med en melding med kommandoen `git commit -m "skriv noe om hva du har gjort her"`
8. Push til branch med `git push -u origin <brukernavn>-<navn-på-branch>`
9. Gå til linken du får opp i terminalen
11. Lag en ny pull request, og velg type commit (*merge:* du kombinerer endringer fra en branch til en annen og beholder all commithistorikk. *rebase:* du flytter endringene dine til toppen av en branch - renere historikk, men kan være risikabelt. *squash:* du kombinerer flere commits til én, men må brukes med merge eller rebase. Som regel bør rebase brukes, men det avhenger av tilfelle)
