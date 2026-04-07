## Game Choice
I decided to go with Whack A Mole as my game of choice. I made an alteration and now it's called Whack A Navy where I replaced the moles with my son Navy and the background is a trampline park.

## Functions and Features
I used functions like showAndHide() to show and hide Navy given a delay in time and the hole where Navy is hiding. The gameOver function provides an ending for the game. The startGame feature allows the game to begin once the start button is clicked. I used event listeners so that the game would react to the clicks on the start button and on Navy when he comes out of the holes. The updateScore function tallies up the score as the user clicks on Navy.

## Implementation Plan
The plan was to use the resources that I've collected over my time in the web development course along with the hints provided in this project to create a functional game. For each function, I was able to reference something I had previously done to get it completed. Then I was able to get pictures of my son and get the image link to replace the image of the mole.

## Trade Offs
The main trade offs I made were in the css file where I changed the moles into my son and the background into a trampoline park. I also made a font change to make the words appear in Times New Roman and changed the font color to navy blue. Also aligned the start button to the center of the page for better accessibility

## Troubleshooting Moments
I wasn't able to get the mallet to show up at first. But after looking closely at the code, I realized it wasn't pulling from the right path to get the photo of the mallet. I used "../" to get the path on track so I could use the image of the mallet. I also had an issue where the bottom row of my holes wouldn't show unless the user set the page to full screen. To fix this, I modified the html code to put all of the h1 and h2 into a single div and reduced the margin so that everything would fit in the main browser screen.

## AI Tools
I didn't have much use for AI in this project because of the resources I already had from my previous lessons and the hints that were given in the readme for the project.

## Project Process
This was a challenging process because it caused me to dig deep into my vault of resources to complete it. For each function that the project required of me, I went back to my notes from those lessons and I was able to type out my functions the way they needed to be typed. I used photos from my own device and a picture of a trampoline park from a google search to give myself the backgroud I wanted to use. I went down the list of user stories one at a time and completed the functions before going over to the css file and making my style changes. The easiest part had to be the index.html file where I had to created the divs for the moles. 

## Commit History and Screenshots
xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.html

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   package-lock.json


xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "completed adding holes and creating start button"
[main f4b984d] completed adding holes and creating start button
 1 file changed, 24 insertions(+), 1 deletion(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.js
fatal: pathspec 'index.js' did not match any files

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "got the score and timer elements"
[main caf8e77] got the score and timer elements
 1 file changed, 2 insertions(+), 2 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "added difficulty and chooseHole"
[main 5070ac8] added difficulty and chooseHole
 1 file changed, 16 insertions(+), 3 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "implemented toggleVisibility"
[main c0a703f] implemented toggleVisibility
 1 file changed, 5 insertions(+), 5 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "added start game and game over"
[main 87e382a] added start game and game over
 1 file changed, 12 insertions(+), 5 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "completed functions for upgrade score and clear score"
[main 1a9d4e3] completed functions for upgrade score and clear score
 1 file changed, 4 insertions(+), 2 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "completed whack event and set event listener"
[main 7017505] completed whack event and set event listener
 1 file changed, 4 insertions(+), 2 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "start and update timer"
[main d1ed316] start and update timer
 1 file changed, 5 insertions(+), 1 deletion(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.html

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.js
fatal: pathspec 'index.js' did not match any files

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add styles.css
fatal: pathspec 'styles.css' did not match any files

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/styles.css

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 8 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html
        modified:   src/index.js
        modified:   src/styles.css

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   package-lock.json


xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "replaced mole with Navy and changed the name of the game"
[main 52ee4b2] replaced mole with Navy and changed the name of the game
 3 files changed, 14 insertions(+), 4 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.html

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/index.js

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/style.css
fatal: pathspec 'src/style.css' did not match any files

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add style.css
fatal: pathspec 'style.css' did not match any files

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/styles.css

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "updated background and mallet"
[main 3c94352] updated background and mallet
 2 files changed, 16 insertions(+), 7 deletions(-)

 xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.html

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "rearranged script back into head"
[main feadbcd] rearranged script back into head
 1 file changed, 4 insertions(+), 5 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add index.html

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "took script out of head again, tests are passing"
[main a530720] took script out of head again, tests are passing
 1 file changed, 2 insertions(+), 2 deletions(-)

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git add src/styles.css

xavie@ZayGillette MINGW64 ~/js-dev-final-capstone-starter-whack-a-mole (main)
$ git commit -m "corrected css to allow the mole to show"
[main ea043bb] corrected css to allow the mole to show
 1 file changed, 1 insertion(+)



<img width="1746" height="942" alt="Screenshot 2026-04-01 232914" src="https://github.com/user-attachments/assets/2341834a-ad43-4cc9-b4fa-0547605cbf48" />
<img width="1402" height="877" alt="Screenshot 2026-04-01 233614" src="https://github.com/user-attachments/assets/5d2c2a78-8956-4a73-a081-9f7adf108923" />
<img width="1473" height="946" alt="Screenshot 2026-04-01 234759" src="https://github.com/user-attachments/assets/3f699503-1cbc-473b-bbad-e79c7d697e75" />
<img width="1357" height="957" alt="Screenshot 2026-04-02 000130" src="https://github.com/user-attachments/assets/5cfc5d0a-9b2a-46f5-8f86-f2dec66bf038" />
<img width="1432" height="928" alt="Screenshot 2026-04-02 003734" src="https://github.com/user-attachments/assets/3ac4e848-d512-4511-8f86-f18d2cd97e45" />
<img width="1460" height="951" alt="Screenshot 2026-04-02 004455" src="https://github.com/user-attachments/assets/f77a20ef-d6e5-477c-a20f-fb708734d247" />
<img width="1428" height="942" alt="Screenshot 2026-04-02 005216" src="https://github.com/user-attachments/assets/18a7dc60-41b8-4b16-a19f-39e1771b98b7" />
<img width="1412" height="927" alt="Screenshot 2026-04-02 005619" src="https://github.com/user-attachments/assets/4e59ac66-0931-4f80-a412-807477ac4549" />
<img width="1400" height="935" alt="Screenshot 2026-04-03 002409" src="https://github.com/user-attachments/assets/f1ba3c8f-c0dc-43cd-ae52-809cc55d6517" />
<img width="1377" height="945" alt="Screenshot 2026-04-03 002443" src="https://github.com/user-attachments/assets/2dd08d6f-1f61-436f-b701-070a74e0db26" />
<img width="1455" height="856" alt="Screenshot 2026-04-03 002508" src="https://github.com/user-attachments/assets/b77110d8-cbd9-4f29-8ece-1bf64e5f5bfa" />
<img width="1455" height="856" alt="Screenshot 2026-04-03 002508" src="https://github.com/user-attachments/assets/58b2d68a-63e2-4180-aa0a-77c24d52a71e" />
<img width="1535" height="902" alt="Screenshot 2026-04-06 202604" src="https://github.com/user-attachments/assets/f59cb5a6-7f1f-47d6-a8fd-5fffb284687c" />
<img width="1470" height="846" alt="Screenshot 2026-04-06 202635" src="https://github.com/user-attachments/assets/71f48bcf-f4fc-4b35-b7e2-990d0e064ed2" />











