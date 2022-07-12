First of all setup two roles from `server settings`.
> + `Unverified bot role` : Role assigned on server join and removed on bot verification
> + `Verified bot role` : Role assigned on bot verification 

<br>

Next,

> + Create a channel `✅┇get-verified`
> 
> + Head over to channel settings of `✅┇get-verified` 
>   + Set everyone's permission for not to send message
>   + Set `verified bot role` to not view channel
> 
> + Next, for all other channel and categories except `✅┇get-verified` set permission for `unverified bot role` to no

<br>

> Once done head over to server settings copy `verified bot role`'s ID & `unverified bot role`'s ID. Let's say the IDs are `1234` and `5678` respectively. Now head over to `✅┇get-verified` channel and run the following command:
> <br>
> 
> `.vstart -r 1234 -ur 5678`
> <br>
> 
> **Note:** Replace `1234` and `5678` with the role IDs of `verified bot role`'s ID & `unverified bot role`'s ID respectively.


<br>

> **Q. How to add image to verification embed?**
>
> You just need to add `-i` followed by image URL with `.vstart` command. Example,
>
> `.vstart -r 1234 -ur 5678 -i https://cdn.dribbble.com/users/778626/screenshots/5064153/verify.gif`


