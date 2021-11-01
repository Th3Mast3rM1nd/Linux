# Regular Expressions 

```^``` : start of the line 

<img width="466" alt="Screen Shot 2021-10-31 at 11 27 01" src="https://user-images.githubusercontent.com/92652606/139578272-ccd8d6f8-00bd-48a2-a1bd-e8d931e11ae8.png">

```$``` : end of line

<img width="506" alt="Screen Shot 2021-10-31 at 11 28 23" src="https://user-images.githubusercontent.com/92652606/139578324-77225ce2-ed90-4908-a482-ded72b75ae5f.png">

```.``` DOT : any single char 

<img width="477" alt="Screen Shot 2021-10-31 at 11 29 42" src="https://user-images.githubusercontent.com/92652606/139578366-38981791-e703-4876-830c-270e704c210e.png">

```[...]``` : character class 

```
[a-z]
[A-Z]
[abcdr]
[0-9]
```

<img width="463" alt="Screen Shot 2021-10-31 at 11 35 44" src="https://user-images.githubusercontent.com/92652606/139578559-8aa28dd8-dedf-466b-991c-f67781612752.png">

```[^...] ``` : negation 

```[^abc] : search for anythingf instead abc ```

<img width="387" alt="Screen Shot 2021-10-31 at 11 40 41" src="https://user-images.githubusercontent.com/92652606/139578755-3d4d0b19-0f37-4eba-92ea-64cc1e61d81b.png">

```\``` : escape a char 

<img width="461" alt="Screen Shot 2021-10-31 at 11 43 36" src="https://user-images.githubusercontent.com/92652606/139578893-45dad8d4-5b57-4e85-af0d-abb9d725aa28.png">

```\< ``` : start of a word 

<img width="632" alt="Screen Shot 2021-10-31 at 11 45 22" src="https://user-images.githubusercontent.com/92652606/139578966-c7988e98-4778-40a5-83fa-9d87cf917f61.png">

```\>``` : end of a word 

<img width="532" alt="Screen Shot 2021-10-31 at 11 46 44" src="https://user-images.githubusercontent.com/92652606/139579025-efa37ac5-7d7f-4a48-b44d-53e02f0493c7.png">

```*``` : general wildcard 

![Screenshot at 2021-08-21 16-01-43](https://user-images.githubusercontent.com/92652606/139648353-145d3f1f-7fec-42dd-b076-e9e6c93ab383.png)

```-``` : range 

```
[0-9]
[a-z]
[A-Z]
[A-Za-z0-9]
```

```?``` : Optional match
```
'colors?' S  here is optional so the resulat may be color or colors
```

![Screenshot at 2021-08-21 16-11-03(1)](https://user-images.githubusercontent.com/92652606/139649043-103b2d35-0654-4a1a-be82-3786e29eae2c.png)

```+``` : repetitive match 

<img width="452" alt="Screen Shot 2021-11-01 at 10 15 25" src="https://user-images.githubusercontent.com/92652606/139649541-3008c4ec-27d5-4f79-93b4-ae7f1b77b17e.png">

```{N}``` : match exactly N times

![Screenshot at 2021-08-21 16-33-10](https://user-images.githubusercontent.com/92652606/139649591-0ae270fb-8409-4b7e-926a-29525eb8dbcb.png)

```{N,}```: match at least N times

![Screenshot at 2021-08-21 16-35-46](https://user-images.githubusercontent.com/92652606/139649686-344d1516-9bf7-40e8-a55a-70ae40f7022c.png)

```{N,M}``` : match between N and M times

![Screenshot at 2021-08-21 16-37-55](https://user-images.githubusercontent.com/92652606/139649783-94ce30bf-d0db-4ff6-808c-4c9f342597c5.png)

```|``` : alternation 

![Screenshot at 2021-08-21 16-37-55](https://user-images.githubusercontent.com/92652606/139649888-9a792847-961e-4397-8296-66e238350549.png)

```()```: subpattern 

![Screenshot at 2021-08-21 17-04-31](https://user-images.githubusercontent.com/92652606/139650092-2a99a5c2-7998-47c4-bc3a-ad08588e8e1a.png)

<h> Some Usefull Regx Experssion</h>

* ***ip adresses***

```
egrep -rhi '[0-9]{1,3}(\.[0-9]{1,3}){3}'
```

<img width="594" alt="Screen Shot 2021-11-01 at 10 24 11" src="https://user-images.githubusercontent.com/92652606/139650555-3db61c17-0155-4469-8ec7-d6457d0c4a2e.png">

 * ***MAC adresses***

```
ifconfig | egrep -oi '[0-9a-f]{2}(:[0-9a-f]{2}){5}'
```

* ***IVP6***
```
ifconfig | egrep -oi '[0-9a-f]{4}(:+[0-9a-f]{1,4}){1,8}'
```
* ***email addresses***

```
egrep -i "[a-zA-Z0-9]+\@[a-zA-Z0-9]+\.(com|net|fr|ch|de)"
```
<img width="755" alt="Screen Shot 2021-11-01 at 10 30 58" src="https://user-images.githubusercontent.com/92652606/139651354-1987deb5-fb29-40c0-a59a-bd8509526df2.png">

[ to  Test Regular Expressions ](https://regexr.com/)








