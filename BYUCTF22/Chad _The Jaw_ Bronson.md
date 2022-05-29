
Chad "The Jaw" likes nothing more than pumping iron and looking good. He left behind a favorite song of his for us to analyze. Can you find his deepest, darkest secret?



First the challenge starts you off with an mp3 file, when listening to it there is a strange anomaly at the end, that got me thinking that there was a code so I imediatly uploaded it to a spectrum anaylser and found this: 

![image](https://user-images.githubusercontent.com/46825266/170844536-23f69f75-fdfc-4b7f-8601-6c190f0cdf3c.png)

Doing some OSINT on twitter using that hint I was able to find the Giga Chad himself: https://twitter.com/ChadTheJaw

![image](https://user-images.githubusercontent.com/46825266/170845800-8ed4ebbe-5cf8-405a-8c2f-653e8f0442fb.png)

On this twitter page you can find this suspicious link "look at me now" that lead to an image: 

![image](https://user-images.githubusercontent.com/46825266/170844566-fb8d40d2-780d-413e-9f3e-922996528230.png)
![image](https://user-images.githubusercontent.com/46825266/170845774-961dadae-2d5b-4834-866f-35d9d67c8d0b.png)


Upon downloadling this file I noticed that it was unusually large 16MB for a small jpg, I loaded it into a hex editor and it looked like there was other content hidden in that image, eventually I found that there was a rar file inside: 

![image](https://user-images.githubusercontent.com/46825266/170844653-d58d7051-7889-47b7-b8bc-c99652b27285.png)

I cleaned up the file removing the png section that was before the "Rar!" I was left with an password locked rar file: 

![image](https://user-images.githubusercontent.com/46825266/170844689-827a073b-616f-45c7-b028-d61bb0d75151.png)

Not knowing the password to unlock these files I poked around on the twitter again and found this text file:

![image](https://user-images.githubusercontent.com/46825266/170844726-b5bc9567-997e-4401-9fa1-56a49ea2ce19.png)

Using this I was able to decypt this by counting the ammount of "chads" and "thejaws" the corelated the number to letters in the alphabet you can see my thought process here: 

![image](https://user-images.githubusercontent.com/46825266/170844787-52ca3947-ef30-462d-a089-a59ca7a56068.png)

Now that I had the password I was able to look at the encrypted files and was able to find the flag in one of the pictures:


This was an awesome challange that I was able to get my first "first blood" on and will always remember this one throughout the rest of the CTF's I do!
