
# Sift for TriggerServerEvents and Strings


The filtering-tool "Sift" helps you search and find Triggers that can be exploited, once you have dumped the desired FiveM-Server.



![unknown](https://user-images.githubusercontent.com/77595905/109565724-2dd48780-7ae3-11eb-9109-19307c4ba9c1.png)
(Ham Mafia Executor)


Once you've dumped the server, by pressing **Save to Folder**, you are able to see the dump-folder on your c-drive. // **C:\dmps\**
The name of the server, is the same name that you entered in the executor.

Drag the files from the **Sift.rar** into **C:\dmps\SERVERNAME**

Now, go ahead and open the **Sift.bat** and you should be able to see, something like this picture.
![Screenshot_3](https://user-images.githubusercontent.com/77595905/109566294-f5817900-7ae3-11eb-837f-fb247f14b931.png)

To search for words, you use **sift _word_**.
In our case, we will look for client-events, so in that case we'll do "**sift TriggerServerEvent** (case sensitive!!!!)

...
![Screenshot_4](https://user-images.githubusercontent.com/77595905/109566491-3e393200-7ae4-11eb-9127-d571a5e747ed.png)

Now, what you should be able to see, should be **many** different strings all being server-events. 
What you want to find, would be something that gives you an item, spawns money or anything else, that would make the RP-experience better for you, kek.

**I'll look for money now.**


![Screenshot_5](https://user-images.githubusercontent.com/77595905/109566715-8d7f6280-7ae4-11eb-8c15-fe7a3d922deb.png)

Something that I personally like to do, is to press **CTRL + F** and put in stuff, such as **"money, value, success, price" **__ to search for.

Woopsie - ![image](https://user-images.githubusercontent.com/77595905/109566813-b3a50280-7ae4-11eb-910d-601184155295.png)
This would indicate that I'd finish my job as a taxi-driver, and that I'd get paid for what I did(**n't**) do.


Now, go ahead and paste the found trigger, in my case that would be **TriggerServerEvent('esx_taxijob:success')**, into our executor, and press "**Run**.
Welp, now I got paid!
