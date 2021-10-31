# Text Processing

```cat``` : Concatenate Files and Print on Standard Output

* ```-n```: print number of lines 

<img width="346" alt="Screen Shot 2021-10-31 at 11 55 09" src="https://user-images.githubusercontent.com/92652606/139579487-c4d2e2e4-25b8-447d-903e-26870213e1e0.png">

```Sort``` : Sort lines  of text Files

```
sort file1.com file2.com file3.com > sorted_file.txt
```

<img width="374" alt="Screen Shot 2021-10-31 at 11 57 17" src="https://user-images.githubusercontent.com/92652606/139579573-83673af4-7442-4c44-b1e9-8de230d0cbc2.png">

* ```-b``` : --ignore-leading-blanks
* ```-f``` : --ignore-case  make sorting case insensitive
* ```-n``` : preforms numeric sorting 

<img width="296" alt="Screen Shot 2021-10-31 at 12 02 31" src="https://user-images.githubusercontent.com/92652606/139579742-0839e130-4081-4b2d-816f-51724ac46bd8.png">

* ```-r``` : sort in reverse order 

<img width="376" alt="Screen Shot 2021-10-31 at 12 02 50" src="https://user-images.githubusercontent.com/92652606/139579764-196ea41e-7aea-49e3-b6cc-48d95499b7ca.png">

* ```-k``` : sort based on key filed : --key=filed1

<img width="805" alt="Screen Shot 2021-10-31 at 12 04 54" src="https://user-images.githubusercontent.com/92652606/139579829-1c539e92-2650-498a-ad76-1469f9312bfa.png">

* ```-o``` : sent sorted output to a file

<img width="751" alt="Screen Shot 2021-10-31 at 12 06 01" src="https://user-images.githubusercontent.com/92652606/139579877-34d2d85c-4955-41fc-af35-d200bc205202.png">

* ```-t``` : define the field seprator

<img width="739" alt="Screen Shot 2021-10-31 at 12 07 54" src="https://user-images.githubusercontent.com/92652606/139579986-7d2e72b4-5ce3-4f06-88c9-922f93fbb0bd.png">


* ```-u```: remove duplicated from the output

```Uniq```: Report or Omit Repeated Lines.

* ```-c``` : output duplicated lines
* ```-d``` : only repeated lines
* ```-i``` :ignore case
* ```-u``` : dont print any line that has a duplicate

```cut``` : Remove Sections From Each Line of File

* ```-f```: filed 
* ```-d```: delimeter char 

![Screenshot at 2021-08-22 22-00-46](https://user-images.githubusercontent.com/92652606/139601280-7732b843-3423-4ca7-bbd4-55abffc89f9a.png)

```Paste``` : Merge Lines of Files 

![Screenshot at 2021-08-22 22-11-38](https://user-images.githubusercontent.com/92652606/139601298-663a7562-548b-4d46-80cb-dcdfb650ee9c.png)

```Join```: Join LInes of two files on a command Field

```
join file1.txt file2.txt 
```
```Comm```: Compare Two sorted Files line by Line 

<img width="422" alt="Screen Shot 2021-10-31 at 22 12 05" src="https://user-images.githubusercontent.com/92652606/139601378-a9d5ded1-0dfa-4d4e-88a1-96f3a6c6a73f.png">

```Diff```: Compare Files LIne by Line.

<img width="510" alt="Screen Shot 2021-10-31 at 22 13 35" src="https://user-images.githubusercontent.com/92652606/139601421-3700bb54-0961-41fa-bb70-6de10aded2d1.png">

```tr```: Transliterate or Delete Characters.

<img width="793" alt="Screen Shot 2021-10-31 at 22 15 29" src="https://user-images.githubusercontent.com/92652606/139601491-98fe5a92-54dd-42b6-88fd-b32cddd455ff.png">

***tr can be used to encode  and decode  ROT13***

<img width="517" alt="Screen Shot 2021-10-31 at 22 18 01" src="https://user-images.githubusercontent.com/92652606/139601565-a65ced86-09d2-47e5-a336-0baa521fa64d.png">






