## Read The Rules
Please follow the rules for this CTF!<br>
https://ctf.nahamcon.com/rules<br>

Check out the source code and the flag is in comment line

**flag{90bc54705794a62015369fd8e86e557b}**

## Shoelaces
Do you double-knot your shoelaces? You gotta keep'em tied!<br>
Download shoelaces.jpg

![image](https://user-images.githubusercontent.com/50519199/123905499-25019e80-d97b-11eb-89d2-3a5b9d6e34dc.png)

I used CyberChef to analyze the file

![image](https://user-images.githubusercontent.com/50519199/123905671-70b44800-d97b-11eb-8631-a8027542095d.png)

**flag{137288e960a3ae9b148e8a7db16a69b0}**

## esab64
Was it a car or a cat I saw?<br>
Download esab64 file.<br>

I changed the file extension as txt and in the file *mxWYntnZiVjMxEjY0kDOhZWZ4cjYxIGZwQmY2ATMxEzNlFjNl13X*<br>
There is a clue in the question Base64 but when I decoded it *....ÙÙ.XÌÄHØÒ@Î...áÈØÄ..Á .Ø.ÌÄLÍ.XÍ.]×* has no meaning but the question is spelling in half backward.<br>
So that I changed it from *mxWYntnZiVjMxEjY0kDOhZWZ4cjYxIGZwQmY2ATMxEzNlFjNl13X* to *X31lNjFlNzExMTA2YmQwZGIxYjc4ZWZhODk0YjExMjViZntnYWxm* and then I try to decode as Base64.
The answer looked like *_}e61e711106bd0db1b78efa894b1125bf{galf* then reverse it again

![image](https://user-images.githubusercontent.com/50519199/123906345-a9085600-d97c-11eb-8fc5-b888878f1049.png)

**flag{fb5211b498afe87b1bd0db601117e16e}**

## Chicken Wings
I ordered chicken wings at the local restaurant, but uh... this really isn't what I was expecting...<br>
Download chicken_wings file.<br>

I changed the file extension as txt and in the file ♐●♋♑❀♏📁🖮🖲📂♍♏⌛🖰♐🖮📂🖰📂🖰🖰♍📁🗏🖮🖰♌📂♍📁♋🗏♌♎♍🖲♏❝<br>
I researched every single charachter to understand the typing and I found these are [Wingdings](https://en.wikipedia.org/wiki/Wingdings)<br>
The I used this [dcode](https://www.dcode.fr/wingdings-font) website to solve it.

![image](https://user-images.githubusercontent.com/50519199/123906985-d7d2fc00-d97d-11eb-84fb-ceb79d129bf9.png)

**flag{fb5211b498afe87b1bd0db601117e16e}**

## Pollex
Download the file below.<br>
Download pollex.jpg

When I downloaded and opened it I saw a there is a thumb picture

![image](https://user-images.githubusercontent.com/50519199/123907199-3304ee80-d97e-11eb-878c-f8239e42f9de.png)

I used CyberChef to analyze the file

![image](https://user-images.githubusercontent.com/50519199/123907299-5e87d900-d97e-11eb-8d1a-1ca3a74c6e5f.png)

There are four different file and I focused the jpg extensions.
1. *extracted_at_0x0.jpg* has the same file size so that it is the original file.
2. I download both *extracted_at_0x14e.jpg* and *extracted_at_0x350.jpg* file.
3. There is the answer

![image](https://user-images.githubusercontent.com/50519199/123907551-c5a58d80-d97e-11eb-9a14-094498c4e482.png)

**flag{65c34a1ec121a286600ddd48fe36bc00}**
