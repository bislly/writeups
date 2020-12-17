## GET - Writeup :triangular_flag_on_post:

-----

**Category :  Web**\
**Points : 200**\
**Author : @Vanisco**

-----

#### # Writeup

We have a file.php page that returns a random base64 sentence and a following random character.
The base64 sentences mean nothing. and the random char after then does not lead to something special.

the way to solve it is to add the header Rage to the get request.
Range: bytes=0-1000

and we get the flag.

#### # **Flag :** 

```hf0x01{1NCR3453_Y0UR_R4NG3_HTTP}```
