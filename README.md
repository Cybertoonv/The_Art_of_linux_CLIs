# The_Art_of_linux_CLIs
RICING -- BRAIN ROTS
r/UNIXPORN

# TERMINAL 
  
### Neofetch 
Default neofetch with w3m coomand, command goes like this (neofetch --w3m "path to image" ) but dont forget to install w3m :)

![yws79f1rkeg81](https://github.com/user-attachments/assets/23537911-8787-4e24-a52d-5a83d6868821)


Todays Years old and saw a post i.e r/unixporn and went to customize my own terminal in the hope of Seeing an image while running the command. In the end it was just a discovery, wasn't able to gain what i want but here what i found 

# Tips & Tricks
###customize
* You can customize neofetch according to your liking i.e info u wanna see, image, colors and ......
* It uses a bash script(they are easy to understand), Do check it out **~/.config/neofetch/config.conf**  Personally love to use **nano**
* It support different kind of images i.e ascii (default one u see containing number, signs) | Image formats u love(png,jpg ...)  |  The blur one u can see in the image + more but they didn't work me... will tell why
* U can easilt change jpg|png image to ascii using a simple command **jp2a**, it could easily change your image to ascii and the best one far better than one found in Websites.
### What u can do
* Uncomment the option u don't love and comment the one u don't wanna see
* change the image_backend to w3m || other to support images and different format (**Default:ascii**)
* Love the Default ascii logo but wanna add a custom ascii-image use **jp2a --colors** To keep the original colors or check -h **man-page**  
* If u wanna give it a rainbow like color (which i don't usually prefer u can use **lolcat**)

### Issue:
* As a kali user i found it disturbing to not be able to use image with neofetch, since it **Doesn't support**  But u can use them on kde, Gnome and other

Since i got this issue wasn't able to do much but before changing the script will recommand u to use this command :
Take from config file:
### Image backend.
 Default:  'ascii'
 Values:   'ascii', 'caca', 'chafa', 'jp2a', 'iterm2', 'off',
'pot', 'termpix', 'pixterm', 'tycat', 'w3m', 'kitty'
Flag:     --backend
image_backend="chafa"
*These are all the backend it support change according to your liking.
COMMAND: **neofetch  --image_backend  /pathtoimage** i.e  **Neofetch --jp2a /Pictures/image.jpg|png **

The following link contains 9 ways to use neofetch  https://itsfoss.com/using-neofetch/  (do check it out)  link to someone config file https://gist.github.com/mokshchaudhary/1b6cb27620077c109ed805113cea4a2d#file-config-conf



### In the end  i just dump all the info and will hope to change it to more understandable manner changing to eye catching and easy to read format rather than the info dump up and down
 



