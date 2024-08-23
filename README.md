
Web Server for LalaDog
======================

**Running on DigitalOcean Droplet**

**How to Test & Run Web Page**

1. Check the Webpage in the Browser

    http://24.199.97.184:5173/

2. SSH into Droplet

    ssh root@24.199.97.184

3. Change into Web Server Directory

    cd laladog-web-server/laladog-web-server

4. Run Web Server

    npm run dev


**How to Edit the Main Web Page Remotely**

1. SSH into Droplet

    ssh root@24.199.97.184

2. Change into Web Server Directory

    cd laladog-web-server/laladog-web-server

3. Open Emacs to Edit the Web Page

    emacs src/routes/+page.svelte

4. Use Ctrl-X Ctrl-S to save

5. Use Ctrl-X Ctrl-C to exit emacs

6. Commit and Push your Changes to Github

    git commit -am "a description of my chenges"
    git push
    
**How to Edit the Main Web Page Locally**

2. Change into Web Server Directory

    cd Desktop/laladog-web-server/laladog-web-server

3. Open Emacs to Edit the Web Page

    emacs src/routes/+page.svelte

4. Use Ctrl-X Ctrl-S to save

5. Use Ctrl-X Ctrl-C to exit emacs

6. Commit and Push your Changes to Github

    git commit -am "a description of my chenges"
    git push

7. SSH into Droplet

    ssh root@24.199.97.184

8. Change into Web Server Directory

    cd laladog-web-server/laladog-web-server

9. Pull Changes from Github

    git pull


**Generate ssh key**

    ssh-keygen -t RSA -b 4096

**Exit from Server**

    exit
**Show Public SSH Key in Terminal

    cat ~/.ssh/id_rsa.pub                                   

**Clone Web Server GIT Repo**

    git clone git@github.com:Linsetta/laladog-web-server.git

**Add Files to Git Repo**

    git add .

**Commit Changes to Git Repo**

    git commit -am "a description of my changes"

**Push Changes to Github**

    git push

**Pull Changes from Github**

    git pull

