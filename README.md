<b> WhatsApp like batch-chat with Username is typing.. support</b>
<br><font size=23>Update: Now with end-to-end encryption</font></br>
<br>- *Is this really end-to-end encryption?*</br>
<br>Ans: Encryption might be misleading, the fact that u r implementing chat
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
keys. Please avoid using the following:<b> |  & " ^ % ! (  ) = </b>

If key.bat is deleted, encryption is ( automatically ) disabled.

<b>Please take it with a pinch of Salt.</b>

Servers can be implemented by mounting a remote location (or drive) locally and running the batch script in that
folder.
