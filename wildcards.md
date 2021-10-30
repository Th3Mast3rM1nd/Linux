# Wildcards 

****: any Characters***
* ``` ls * ``` 
* ``` cp *.txt ~/Desktop ``` :  will copy each file in the working dir thats ends with ```txt```
* ``` mv * ~/Downloads ``` : move all files to Downloads Folder .

<img width="1062" alt="Screen Shot 2021-10-30 at 17 15 55" src="https://user-images.githubusercontent.com/92652606/139539108-67939ecb-2782-4b10-990b-f7c5d10327a7.png">

***? : any single Characters***

```cp file?.txt``` : copy any file start with file and followed with exactly 1  char.
```rm file.???``` : remove any file that ends with 3 char exactly .

<img width="544" alt="Screen Shot 2021-10-30 at 17 23 32" src="https://user-images.githubusercontent.com/92652606/139539315-3a89e6b4-5da4-4295-8493-a6135577649a.png">

***[ char ] : any char that is a member of set characters***

* ```rm [pmn]*.txt``` : wil remove any file start with ```p``` , ```m``` or ```n```
* ```cp [ abc]* ``` : any file beginning with either ```a``` , ```b``` , ```c```. 

