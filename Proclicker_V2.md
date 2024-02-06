# Proclicker V2
Points: 700

### Description
Get your fingers ready because you will be clicking like you never have before. The old Proclick was found to have been infested with cheating hackers. Revamp your creds by winning our game the right way.

http://chal.bearcatctf.io:43320

## My Approach
1. I visited the provided link and it was a login page.
2. I logged in with `test` and it redirected me to a game.
3. The game was to click on the button as many times as possible.
4. I opened the network tab in the developer tools and reviewed the html file.
5. There was a web-assembly file linked in script tag. First I thought there was something in the web-assembly file.
6. I read the javascript part in the html file again carefully and found a `if` condition which was checking for the number of clicks.
7. Condition was checking if the number of clicks is divisible by some number.
8. I calculated the LCM (Largest Common Multiple) of the numbers and set the number of clicks in cookies.
9. I refreshed the page and a new button showed up.
10. I clicked on the button and got the flag.