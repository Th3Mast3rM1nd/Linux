# Sed 

* The syntax for substitute command ``` sed 's/regxp/Replacemnet/flag'```

```g```: global replacment.

<img width="557" alt="Screen Shot 2021-11-01 at 10 43 17" src="https://user-images.githubusercontent.com/92652606/139652924-46717a26-51ed-4304-81b5-81e215625984.png">

```d``` : delete 

<img width="439" alt="Screen Shot 2021-11-01 at 10 47 28" src="https://user-images.githubusercontent.com/92652606/139653514-1955be71-8cf0-43a3-abd6-818e37931d62.png">

```q``` : quit ***will exit sed immediately after finding the matched word***

<img width="642" alt="Screen Shot 2021-11-01 at 10 51 49" src="https://user-images.githubusercontent.com/92652606/139653929-d1b26925-3e06-425e-aba5-7ef52b0ee1fc.png">

```-n "Np;Np"``` : sed will print number lines where N is line number 

<img width="499" alt="Screen Shot 2021-11-01 at 10 57 12" src="https://user-images.githubusercontent.com/92652606/139654681-387ea66d-e6a5-4e93-88a9-198e857274a2.png">

```-n /word/=``` : Print just the line number 

<img width="494" alt="Screen Shot 2021-11-01 at 11 00 39" src="https://user-images.githubusercontent.com/92652606/139654876-ba7092ff-c8b4-47fe-a0a9-abaff667c28b.png">

***sed and Regular expressions*** [ Check this for regular experssions ](https://github.com/Th3Mast3rM1nd/Linux/blob/master/regular-expressions.md)

```^```: start of the line

```$```: end of the line 

<img width="524" alt="Screen Shot 2021-11-01 at 11 09 48" src="https://user-images.githubusercontent.com/92652606/139655835-a5f6bb54-2a9c-4e83-a15a-df232b4f24e6.png">

<img width="524" alt="Screen Shot 2021-11-01 at 11 09 48" src="https://user-images.githubusercontent.com/92652606/139656603-436500e7-1543-4284-ad74-fe82edceb4ee.png">
                  
<img width="563" alt="Screen Shot 2021-11-01 at 11 16 26" src="https://user-images.githubusercontent.com/92652606/139656684-b704d8b0-09ec-4f52-a4be-65d02a259f28.png">

# awk 

***print first field***

<img width="481" alt="Screen Shot 2021-11-01 at 11 24 21" src="https://user-images.githubusercontent.com/92652606/139657596-3abefb1d-0d8f-4f90-967e-09309a26fa48.png">

***print second field***

<img width="429" alt="Screen Shot 2021-11-01 at 11 25 10" src="https://user-images.githubusercontent.com/92652606/139657674-cc21621b-d69e-4195-8095-bc3b3500569b.png">

```-F``` : field separator 

<img width="589" alt="Screen Shot 2021-11-01 at 11 28 45" src="https://user-images.githubusercontent.com/92652606/139658079-04a4a958-d86a-41f5-8bbb-0248fde8f6a2.png">

```$NF``` : last field 

<img width="644" alt="Screen Shot 2021-11-01 at 11 30 01" src="https://user-images.githubusercontent.com/92652606/139658238-d31aa9e4-38c2-47c7-93c0-f30dfe12c331.png">

<img width="573" alt="Screen Shot 2021-11-01 at 11 37 34" src="https://user-images.githubusercontent.com/92652606/139659119-4d98382a-90c2-4d2a-8e4f-77b1ed9f62fb.png">

***awk and Regular expressions***

<img width="664" alt="Screen Shot 2021-11-01 at 11 39 38" src="https://user-images.githubusercontent.com/92652606/139659425-ad2b7c79-49f0-48d5-b6ef-4ce6ddae3f4a.png">

<img width="510" alt="Screen Shot 2021-11-01 at 11 43 43" src="https://user-images.githubusercontent.com/92652606/139659802-8aa990a1-e890-43d5-aea3-dac08388e7da.png">




                                                               

