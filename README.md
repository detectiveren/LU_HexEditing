# LU_HexEditing
Tutorial on how to Hex Edit the Client Version and NET Version (Incomplete)

# What you will need

You will need a LEGO Universe client of course and you will need a program called HxD which you can download here https://mh-nexus.de/en/hxd/

# Using HxD to edit the Client Version

Click on File and then click on Open then navigate to your LEGO Universe client folder and open up legouniverse.exe
![image](https://user-images.githubusercontent.com/55319774/180182263-6a9c2c7b-8229-44ba-bceb-c361290f1141.png)

Press Ctrl+F and then make sure you are on the Text-string tab, change Text Encoding from (Editor encoding) to Unicode (UTF-16 little endian)
![image](https://user-images.githubusercontent.com/55319774/180183136-d621067f-e086-4b95-b38c-989b6d3b8747.png)
I already changed my client version to 1.11.72 but yours is likely 1.10.64 so search for that instead

Click OK and it should show you this
![image](https://user-images.githubusercontent.com/55319774/180183383-f62ac820-f262-473f-9bd1-604b3a38887e.png)

If you look closely at this 

![image](https://user-images.githubusercontent.com/55319774/180183557-3cc33766-be02-469a-bd27-6d84003b531d.png)

You will see the Client Version that I changed it to present

Its "1...1.1...7.2." as you can see

Now to change this to lets say 1.12.40, all we would have to do is change it from "1...1.1...7.2." to "1...1.2...4.0." which will display as 1.12.40 in the client. 

To do this you highlight the number you are trying to change like this
![image](https://user-images.githubusercontent.com/55319774/180185342-c4daf967-77b0-4b90-8e21-efab79e90cb2.png)
I highlighted "1" and if I want to change that to the number 2 then all I do is press 2 and it will change to this 

![image](https://user-images.githubusercontent.com/55319774/180185642-50b15f45-2564-4979-ade7-9302428ccf50.png)

As you can see the "2" is highlighted in red, this indicates you changed something

Now you do that same process for the rest of the numbers you are trying to change like what I did below

![image](https://user-images.githubusercontent.com/55319774/180186240-04ad04e1-3959-47b5-bdb2-73e64e0c8e13.png)

Once you are done, click on File then Save As, navigate to your client folder and save it there, you can choose to name it what you want or keep the same name legouniverse.exe, keep in mind that will replace your already existing legouniverse.exe if you haven't backed it up somewhere else
![image](https://user-images.githubusercontent.com/55319774/180186954-7dd4326f-0450-4423-abbc-d6efdc941a83.png)

You can now navigate to your updated legouniverse.exe file (or whatever you named it) and open it
![image](https://user-images.githubusercontent.com/55319774/180187440-1aee793a-6fb1-4875-9ab0-a7580e5f21d2.png)

I named mine legouniverse_test.exe for this tutorial

Click on it and once it opens you will see the Client Version you changed it to
![image](https://user-images.githubusercontent.com/55319774/180187781-52b652c2-57e1-429a-9992-b386054959b9.png)





