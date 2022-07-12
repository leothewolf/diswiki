# Auto verification system

<br>

> + **Please read the whole sub-doc for better understanding. It barely takes 5 mins.**
> + **Please setup [captcha verification](https://github.com/leothewolf/diswiki/blob/main/docs/manual-verification-system.md) system before setting up auto verification system**

<br>

> Head over to server settings and create two roles
>   + `Auto verified age role` : role assigned on automatic age verification
>   + `Auto verified bot role` : role assigned on automatic bot verification
> <br>
> 
> Let's assume their ID's to be `1234` and `5678` respectively. 
> <br>
> <br>
> Next, head over to any channel and run following command:
> <br>
> <br>
> `.auto_start -avr 1234 -bvr 5678`
> <br>
> <br>
> [Replace `1234` and `5678` with `auto verified age role`'s & `auto verified bot role`'s ID respectively.]

<br>

> After that if you want the bot to auto age verify users type :
> <br>
> `.auto_update -averify yes` 
> <br>
> <br>
> If you want the bot to auto bot verify users type :
> <br>
> `.auto_update -bverify yes` 
> <br>
> <br>
> `Replace yes with no if you want to stop auto verifcation of either`

<br>

> After that let's say you have three roles:
>   + `age role` : role which is assigned manually by staff on age verification
>   + `bot role` : role which is assigned on manual captcha (bot) verification 
>   + `unverified bot role` : role which is assigned on server join and removed on captcha verification
>
> Let's assume their ID's to be respectively `2345` , `3456` & `4567`
> <br>
> <br>
> Now run following command to add that to bot's database
> <br>
> `.auto_update -ar 2345 -br 3456 -bur 4567`
> <br>
> <br>
> [Replace `2345` , `3456` & `4567` with `age role`'s `bot role`'s & `unverified bot role`'s ID respectively.]
