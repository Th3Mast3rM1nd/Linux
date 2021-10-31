# Grep 

``` 
grep pattern file.txt 
cat file.txt | grep pattern 
grep pattern file.txt | vim - 
```
<img width="427" alt="Screen Shot 2021-10-31 at 10 54 43" src="https://user-images.githubusercontent.com/92652606/139577063-813053d7-536f-42cb-b935-df593a8e16ea.png">

***Some*** ```grep``` ***Options :***

* ```-e ``` : to use a regex pattern.

```
grep -e "-sytle" doc.txt
```

* ```-f ``` : grep will take patterns from file to search

<img width="378" alt="Screen Shot 2021-10-31 at 10 59 57" src="https://user-images.githubusercontent.com/92652606/139577269-509d2b8b-8aba-4b33-ad7e-3d08782121a8.png">

* ``` i``` : ignore case.

* ```-v ``` : invert match.

```
grep -v 'help' test.txt ( will returen lines that dosent match 'help' )
```

* ```-w ``` : match only the exact word

<img width="450" alt="Screen Shot 2021-10-31 at 11 03 30" src="https://user-images.githubusercontent.com/92652606/139577425-9bae4467-4e01-4ecb-998d-798eb0c603eb.png">

* ```-x ``` : match the entire line

* ```-c ``` :  just a count of how many lines matched

<img width="453" alt="Screen Shot 2021-10-31 at 11 05 10" src="https://user-images.githubusercontent.com/92652606/139577479-faf09032-5c9e-4a05-817d-b44662918563.png">

* ```-l ``` : only files that matches

<img width="402" alt="Screen Shot 2021-10-31 at 11 07 03" src="https://user-images.githubusercontent.com/92652606/139577548-3812e1a1-fb40-4a1e-9259-27dadd4169d6.png">

* ```-L ``` : files without match

<img width="438" alt="Screen Shot 2021-10-31 at 11 08 23" src="https://user-images.githubusercontent.com/92652606/139577588-f5eb286e-0988-43c2-bc85-0f350fbe0588.png">

* ```-o ```: print only the text that matches


<img width="398" alt="Screen Shot 2021-10-31 at 11 09 58" src="https://user-images.githubusercontent.com/92652606/139577655-99815154-ba1b-49b9-8766-dabf496fe444.png">

* ```-H ``` : with filename 

<img width="407" alt="Screen Shot 2021-10-31 at 11 11 40" src="https://user-images.githubusercontent.com/92652606/139577743-0c944d2c-d96f-4fdf-923b-bcf7c973b0d1.png">

* ```-h ``` : without filename 

<img width="395" alt="Screen Shot 2021-10-31 at 11 12 39" src="https://user-images.githubusercontent.com/92652606/139577797-f6f43755-d8a4-4cc4-97cf-705dd6e40aa1.png">

* ```-n ``` : number of lines.

<img width="496" alt="Screen Shot 2021-10-31 at 11 13 41" src="https://user-images.githubusercontent.com/92652606/139577825-0df0e6e5-ed29-4224-9af6-3b883f564135.png">

* ```-A NUM ``` : after context=NUM

<img width="421" alt="Screen Shot 2021-10-31 at 11 15 02" src="https://user-images.githubusercontent.com/92652606/139577875-5cab5629-af76-4ebd-8900-a7d64fffa9de.png">

* ```-B NUM ``` : before  context =NUM

<img width="389" alt="Screen Shot 2021-10-31 at 11 16 04" src="https://user-images.githubusercontent.com/92652606/139577911-dcb20ee2-fb11-49fc-87f4-625303f36d7f.png">

* ```-C NUM ```: will display number line before and after.

<img width="398" alt="Screen Shot 2021-10-31 at 11 17 09" src="https://user-images.githubusercontent.com/92652606/139577939-4a7b1ad6-0f70-4357-bd09-08908416ade8.png">

* ```-R -r ```: search recursive

<img width="333" alt="Screen Shot 2021-10-31 at 11 18 16" src="https://user-images.githubusercontent.com/92652606/139577983-98d98caa-9c31-4bc9-9593-c0faee68e91c.png">





