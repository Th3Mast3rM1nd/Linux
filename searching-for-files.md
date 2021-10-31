# Searching For Files 

* ```Locate ``` :  Find Files By name

***before running locate you should update the database*** ```updatedb```

<img width="422" alt="Screen Shot 2021-10-30 at 21 52 16" src="https://user-images.githubusercontent.com/92652606/139556733-9b1be283-737f-4a1e-a72f-2c64e44e58e1.png">

* ```find ``` : Find Files on the system

```find ~ ``` :  will search on our home directory.

***Some Find Tests***

***-type  search by type*** : ```f``` ***regular file****  , ```l``` ***symbolic link***  , ```d``` ***directory***  , ```c``` ***character special device file*** , ```b``` ***block*** 
<img width="388" alt="Screen Shot 2021-10-30 at 22 07 43" src="https://user-images.githubusercontent.com/92652606/139557120-ee3d92db-f41a-4cbc-bace-664f5814f2d7.png">

***-name search by name*** 

<img width="584" alt="Screen Shot 2021-10-30 at 22 13 07" src="https://user-images.githubusercontent.com/92652606/139557211-9c114024-9a60-491c-802b-146880343ce3.png">

***-size : by size*** : ```b``` ***512 byte block*** , ```c``` ***bytes*** , ```w``` ***2-byte words*** , ```k``` ***kilobytes ( 1024 bytes )*** , ```M``` ***Megabytes*** , ```G``` ***GigaBytes***

<img width="548" alt="Screen Shot 2021-10-31 at 10 04 28" src="https://user-images.githubusercontent.com/92652606/139575498-a93fdaa4-7ccc-4915-aaf1-207de12c33c2.png">


***-user : find files belonging to user***

```
find ~ -type f -name "*.txt" -user root

```

***-perm : find files with a specfic***

<img width="439" alt="Screen Shot 2021-10-31 at 10 07 22" src="https://user-images.githubusercontent.com/92652606/139575612-00b9b7f3-e8aa-4227-a0be-43cd57373829.png">

***Operators***: ```-and``` ```-or``` ```-not``` ```( -a -o )```

<img width="561" alt="Screen Shot 2021-10-31 at 10 09 05" src="https://user-images.githubusercontent.com/92652606/139575678-ef2952d8-9706-40de-941a-9981a67d7c94.png">

<img width="667" alt="Screen Shot 2021-10-31 at 10 10 32" src="https://user-images.githubusercontent.com/92652606/139575739-e44c3ffe-0f5c-4021-9a26-94b1e42a0682.png">

***Actions***: ```-delete``` , ```-ls``` , ```-print``` , ```-quit```

<img width="864" alt="Screen Shot 2021-10-31 at 10 12 20" src="https://user-images.githubusercontent.com/92652606/139575776-da00d594-dc6c-4b9e-95a6-3a610fd05742.png">

***user-Defined Actions*** : ```-exec commad '{}' ';'```

<img width="925" alt="Screen Shot 2021-10-31 at 10 16 28" src="https://user-images.githubusercontent.com/92652606/139575884-80cf908c-c0ad-4b69-8903-53a075b26745.png">

<kbd>we could as well use <b>xargs</b> the same as <b>-exec</b> with find command</kbd>

```
find . -type f -empty | xargs ls -la
````





