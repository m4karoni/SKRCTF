# Welcome to m4karoni SKRCTF write-ups
Hi! This is my first ever write-up for challenges based on my senior's CTF project, [skrctf.me](skrctf.me) which is a ctf site for beginner players.

# Web

## Web warmup

Can you find the flag in this website?
<br/><br/>
Flag format: SKR{flag_flag}
<br/><br/>
At first, it shows a simple html header and a body:<br/>
!["Header and body"](https://user-images.githubusercontent.com/70287409/122788142-9f318380-d2e8-11eb-8f8e-ba98d1f4837a.png)
<br/><br/>
My first action is to inspect the webpage for the flag:<br/>
!["Inpect element"](https://user-images.githubusercontent.com/70287409/122788412-e455b580-d2e8-11eb-89ab-e08f7739cd0d.png)
<br/><br/>
Just like that, I got the flag!
> Flag: SKR{imp0rt4nt_c0mm3nt_a24996}

<br/><br/>
## Where is the flag?
I remember that I put a flag in this website, but I just can't find it. Can you help me?
<br/><br/>
Flag format: SKR{flag_flag}
<br/><br/>
As hinted in the image, "It's too bright"<br/>
!["Header and body"](https://user-images.githubusercontent.com/70287409/122788945-647c1b00-d2e9-11eb-948a-5fb9bd5d0e1e.png)
<br/><br/>
So I have an idea of looking into the css file of the site.<br/>
!["Inspect css"](https://user-images.githubusercontent.com/70287409/122789167-98efd700-d2e9-11eb-8de5-015e963d5d9c.png)
<br/><br/>
> Flag: SKR{wh0_turn_th3_light5_0n?\_10621b}

<br/><br/>
## My First SQL
I made a website with login using PHP and MySQL! Feel free to try it
<br/><br/>
The challenge is about SQLi (SQL injection) attack<br/>
![image](https://user-images.githubusercontent.com/70287409/122853262-8656bb80-d344-11eb-8042-c0c2720318f3.png)
<br/><br/>
Using a simple sql injection payload
> ' OR '1' = '1

<br/><br/>
![image](https://user-images.githubusercontent.com/70287409/122853643-2280c280-d345-11eb-9e95-9fefd7f41fb8.png)
<br/><br/>
> Flag: SKR{Do_not_forget_to_escape_user_input_c75983}

