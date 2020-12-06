# Guide

## GitHub Guide

### Initial config
1. Start FL Studio
2. Options => Project General Settings
3. Data folder aanpassen door op auto te klikken => nieuwe folder onder projects aanmaken
4. rechtermuisklik in nieuwe folder => open git bash here
5. open github.com/ANightAtThePlasky
6. Druk New (repository)
7. Voer de volgende stappen uit in de git bash voor initiele configuratie
    * git init
    * git add *
    * git commit -m "kick drum changed"
    * git remote add origin git@github.com:ANightAtThePlasky/<repository_naam>.git
    * git push
  
### Get new song from collaborator
1. go to github, naar de repository van het nieuwe nummer
2. duw op de groene "clone or download" knop
3. kopieer link
4. go to projects folder in documents (FL Studio)
5. open git bash here
6. Voer de volgende stappen uit in de git bash
    * git clone <gekopieerde link>
  
### Changed something
1. Voer de volgende stappen uit in de git bash voor het desbetreffende nummer voor changes
    * git add *
    * git commit -m "snare drum changed"
    * git push
      * als dit misgaat, ga maar "Other Collaborator changes"
  
### Other collaborator changes
1. Voer de volgende stappen uit in de git bash voor changes
    * git pull
      * dan gaat die mogelijks notepad++ openen, met en bepaald bericht, maar dat maakt niet uit, gewoon sluiten en doorgaan
    * git push
      * als dit misgaat, ga maar "Other Collaborator changes"
      
### Undo change
1. git log
 -- find the commit id you want
2. git checkout <commitId> . 
 -- IMPORTANT NOTE: the trailing `.` in the previous line is important!
   
## Mixing Guide

### Tips 'n Tricks
**Gain Staging**
* Add Gain Unit at start of effects chain and at end
* Volume to feed into plugins: -18dB
* This way: your mixer faders won't be all the way down
* Vid: https://www.youtube.com/watch?v=pinNLBnBRe8
