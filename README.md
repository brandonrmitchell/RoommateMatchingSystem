Roommate Matching System

========================

### Git setup notes:
1. Download Git: http://git-scm.com/download
  * Install - make sure the **Git Bash Here** option is selected
2. Create Github account
3. Add ssh key for your computer
  1. Open Git Bash in any folder
  2. Generate ssh key: `ssh-keygen -t rsa`
    * Hit enter a couple of times - you will most likely not want a password and the default location is fine
  3. Retrieve your new key
    * Navigate to the new key's location - *C:/Users/<user>/.ssh*
    * Open **id_rsa.pub** with Notepad
    * Select all and copy to clipboard
  4. Add the key to your GitHub account
    * Go to your GitHub account settings
    * Select *SSH keys* on the left
    * Choose *New SSH key* at the top
    * Title is a simple name for you to recognise which computer the key belongs to
    * Paste the key in the *Key* box
    * **If the key contains *username@computer* at the end, you must remove it**
    * Click *Add SSH key*
4. Clone project repository