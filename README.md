<h1># In The Name Of God</h1><br>
<h2># Telegram_Message_Forwarder</h2>

<pre>
<h3>what does this script do ?</h3>

<h4>it will forward messages you sent to some chats automatically .</h4>


<h3>proxy supported ? </h3>
<h4>
 YES !
you can use proxy (mtproto not supported because i used pyrogram ! )
set proxy in login_credential config file
</h4>
<h3>how can i use it ?</h3>
<h4>
first of all you must go to <b>my.telegram.org</b> and register for getting <b>api_id</b> and <b>api_hash</b>

after those works you must complete <b>login_credential</b> file requirements such as api_id,api_hash,phone_number and stuff like that ....

after that create folders it can be one folder or more and add chats you wanna forward message to them automatically to those folders and add them to folder_name in login_credential config file ...

sleeping recommended for forwarding message , you can set that in randint_range in login_credential config file ...
set numbers bigger as soon as possible to prevent getting banned ....
my program will sleep a random number from range you get as input to my program ...

after doing that jobs do next jobs 
</h4>
<h3>install requirements of script with <b>pip install -r requirements.txt</b> </h3>

<h3>enable script for forwarding messages</h3>
<h4>
go to saved messages of your telegram account then write /start for enable forwarding messages to chats that you added to folders you write in login_credential config file ...
after writing /start everything you send (except /stop) there will forward to chats ...
</h4>
<h3>disable script for forwarding messages </h3>
<h4>
for disabling this mode you must send /stop in saved message and done [+]
</h4>
</h4>
</pre>