# Verziókezelés alapjai
## git letöltése
 - [git for windows](https://gitforwindows.org/)
 - [git scm](https://git-scm.com/)
   ## 2. Konfigurációs parancsok
 - git config --global user.name kovacsannabella
 - git config --global user.email kovacs.annabella@students.jedlik.eu
 - git config --global credential.helper wincred
   ## 3. Repository létrehozása
 - git init
  ## 4. Állomány hozzáadása a stage-hez (staging area)
  > A stage-n lévő állományokról tudunk állapotfelvételt (commit-ot) készíteni
  > Üres mappa nem kerül a stage-re
 - git add állomány_neve
 - git add . (összes állomány és mappa hozzáadása)
  ## 5. Állapotfelvétel (commit) készítése
 - git commit -m "commit message"
  ## 6. Git állapot és log lekérdezése
  - git status
  - git log