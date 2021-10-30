# Redirection & Pipelines .

***( Standard Output = 1  , Standard Input  = 0 , Standard Error = 2 )***

* Standard Output : ```>```

<img width="338" alt="Screen Shot 2021-10-30 at 18 07 23" src="https://user-images.githubusercontent.com/92652606/139540695-0fab426a-319e-44ac-9a7e-c0ea145c278d.png">

* ```ls -la > file.txt ```  redirecting stdoutput to file.txt.
* ```> file.txt```  will create an empty file.txt 
* ```ls -la >> file.txt ``` the output of ls -la will be appended to the file.

* Standard Error : ``` 2>```

* ``` ls -la 2> file.txt``` : redirecting stderror to the file.txt .

<img width="380" alt="Screen Shot 2021-10-30 at 18 11 19" src="https://user-images.githubusercontent.com/92652606/139540782-a4200048-329f-45c9-94c0-1073699afce0.png">

* Redirecting Standard Output and Error to one file: ```&>``` or ```2>&1```

<img width="787" alt="Screen Shot 2021-10-30 at 18 13 53" src="https://user-images.githubusercontent.com/92652606/139540853-dc0105cc-dbba-4ce5-bb87-873d18278117.png">

``` ls -la 2> /dev/null``` sending all the errors to /dev/null 

# Pipelines : | 

the standard output of a command can be sent into the standard input of another command using ```|```


