<b> WhatsApp like batch-chat with <br>Username is typing.. support</b>
<br><font size=23>Update: Now with end-to-end encryption#</font></br>
<br> # *Is there really end-to-end encryption?*</br>
<br>Encryption as a term might be misleading. Obsufucation, encryption, ciphers all serve the same purpose except
<br>in the context of the Modern World encryption is commonly used which is unbreakable again the assumption is that what
<br>needs to be hidden is some sort of a state secret and that technically able people have the motivation, time and technical ability (rare) 
<br>to try to crack the code. all but one will most likely be missing. but if the lame data that ur trying to hide does in fact fall in the
<br>hands of some technical mastermind the like i described above then u r screwed. or may be he is...given how lame the artifact you are 
<br>trying to protect is. this is where the people cribbing about encryption, security and the likes i tend to disagree with. u see the biggest
<br>companies compromised. all of their data. u use a key to encrypt and write down the key somewhere or enter it eventually. what is the attacker
<br>gains hold of the key. that was not a lot of work. or the hash... or something else. rather u should risk assess whats important and where in
<br>fact u should be putting ur resources. but more than that my point is obsufucation serves the purpose in most cases. stop over doing things.
<br>be street smart that's all.
the fact that u r implementing chat
<br>in batch is simply already a lot of heavy lifting.
<br>It is not encryption in the technical sense of the word but rather in terms
<br>of it's history. Call it cipher text. 
In so much as the server chat files are not stored in plain text,
You need to<br> understand end-to-end encryption on a batch scripting is a tall ask.
While the<br> chat (cipher text) could be decrypted by some one who knows / sees the key<br> or by brute
forcing it was never meant for security but rather for obsufcation. So<br> that when some one
opens the chat server file they are not immediately privy to the chats.</br>

A mechanism could be implemented for rotating / multiple / changing keys. A project <br>called 'tokenism'
generates keys. Key is implemented in key.bat. First line in key.bat is only <br>for reference. Keys can
be changed manually. Both users must have the same keys to communicate. <br>Symbols can be incorporated in
keys.<br>
<br>Banned Symbol List:<b>``` | & " ^ (  ) = < > * ```</b> WARNING: Don't Use

#### Allowed List
<br>To quote something, use back ticks: ``` `something` ```
<br>To use brackets, use square/curly: ``` [something] ```


<br>To use emoji (text): ``` :sad: ```
<br>To use full stop: ``` A sentence. ```
<br>E-mail address: ``` myemail@pun.rubb ```
<br>Other symbols: ``` ~ $ # ```
<br>These symbols will be ignored anyways: <b>```, ! %```</b>

If key.bat is deleted, encryption is ( automatically ) disabled.
<br>For any symbol to show up while using keys, those (allowed list) symbols must be included in the key.

<b>Please take it with a pinch of Salt.</b>

Servers can be implemented by mounting a remote location (or drive) locally and running the batch script in that
folder.

#### Generating Keys
Call tokenism.bat from the command prompt
<br>Example - ```tokenism.bat k h z a j m s f d u y n r l b c e g i o p q t v w x : . [ { ] } # @ ~ ` $```

