# Brixel CTF Winter Edition 2020

Ctf At: https://ctf.brixel.space/

## Easy

**Challenge Link**

On the homepage there is a hidden flag. It's a Source of easy points!
<br />

**Solution**

Inspect Element to find the Flag!

## Hidden Code

**Challenge Link**

Something strange happens on the brixel website when you enter the konami code
flag = the character you see floating by

<br />

https://www.brixel.be/

**Solution**

This is a reference to the konami code. 
Go to the site, press up-up-down-down-left-right-left-right-b-a and you see mario appear on the screen.

## robotopia

**Challenge Link**

I found this cool website, it claims to be 100% robot-free!

There's nothing there yet at the moment, but at least it's robots-free. I wonder how they keep it that way?
<br />

http://timesink.be/robotopia/

**Solution**

This problem references a very common file found on most websites, the robots.txt file.  Just go to `http://timesink.be/robotopia/robots.txt` to get the flag.

## login1

**Challenge Link**
My buddy is trying to become a web developer, he made this little login page. Can you get the password?
<br />

http://timesink.be/login1/index.html

**Solution**

If you inspect element, you can see the login details in the javascript.

## login2

**Challenge Link**
Cool, you found the first password! He secured it more, could you try again?

http://timesink.be/login2/index.html

**Solution**

If you inspect element, you can see the parts of the password all split up.  If you read the code, you can piece together the different pieces of the password.

## login3

**Challenge Link**
Nice! you found another one! He changed it up a bit again, could you try again?

http://timesink.be/login3/index.html

**Solution**
This time, when you inspect element, you can see that the password is stored in the password.txt file.  Simply go to http://timesink.be/login3/password.txt to get the flag.

## login4

**Challenge Link**
Whow, another one! You're good! So I told my buddy how you managed to get the password last time, and he fixed it. Could you check again please?

http://timesink.be/login4/index.html

**Solution**
This time, when you go to http://timesink.be/login4/password.txt, you see the password encrypted in base64.  Decode it to get the flag.

## login5

**Challenge Link**
Ok, THIS time it should be fine! if you find this one he is going to quit trying.

http://timesink.be/login5/index.html

**Solution**
This time the javascript is heavily obfuscated and basically impossible to read.  However, the password is still stored there, and you can copy the code, and compile/run it on your own to get the password.  
https://repl.it/@Teddygat0r/MediumorchidFilthyIntranet#index.js

## Browsercheck

**Challenge Link**
I found this weird website, but it will only allow 'ask jeeves crawler' to enter?

Can you get me in?


http://timesink.be/browsercheck/

**Solution**

This challenge basically checks what browser you're using, and will only let you in if you're using an "Ask Jeeves Crawler" browser.  Just search up "Ask Jeeves Crawler User agent" and set that as your user agent to get the flag.

## SnackShack awards

**Challenge Link**
A friend of mine owns a snackbar and is entered in a competition to win an award.

It seems he is not going to win because he has a low amount of votes :(

Do you think you can boost his votes? adding 5000 votes at once should do the trick!

His snackbar is called Cafetaria 't pleintje


timesink.be/snackshackaward/

**Solution**
When you go to this site, you are able to vote for a snack shack, and give it a specific amount of points.  You need to modify the amount of points you give to 5000.  To do this, you can go into inspect element, and modify the amount of points you enter to 5000.  
Here is an example: `https://prnt.sc/wbx1sp`

