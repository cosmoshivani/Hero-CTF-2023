# Hero-CTF-2023
:mushroom: [HeroCTF](https://www.heroctf.fr/) 

Hi! :wave:

## 1. PNG-G [easy, steganography] - 50 points

### Don't let appearances fool you. Good luck!
Format : Hero{}
Author : Thibz

Here is the image for this challenge --

![pngg](https://github.com/cosmoshivani/Hero-CTF-2023/assets/47838688/54ecc13e-71f1-4aa2-bd78-b8f41e4c848f)

:thought_balloon: 
> HxD editor doesnt show anything. But opening it in the exif tool shows that its file type is apng
and as the challenge description indicates 'dont let appearances fool you', so the extension is png and its first frame will load as a png file but it is a gif file known as animated Portable Network Graphics [APNG]. so to change the extension, I'd copy all the bytes in a new file and give it a random name such as dd.apng

Opening it in a apng file opener and you'll see two images or two frames 

:mushroom: [view APNG files online](https://products.groupdocs.app/viewer/apng)

The second frame has the flag watermarked and that solved this easy steganography challenge

