
# Permissions 

* ```id```  : Display a user identity

<img width="1439" alt="Screen Shot 2021-10-30 at 19 07 00" src="https://user-images.githubusercontent.com/92652606/139542434-3baada9c-f4d5-485c-adbe-e6b6eccd52b2.png">

* ```chmod ``` : Change file Mode

| octal | Decimal | Permission | Representation |
|-------|---------|------------|----------------|
| 000   |    0    | no Permission | --- |
| 001   | 1    | execute    |   --x  |
| 010   | 2     | write |  --w | 
| 011   | 3     | write + write | -wx  | 
| 100   | 4     |  read |  r-- |
| 101   |  5    | read + execute | r-x |
| 110  | 6 | read + write | rw- |
| 111  | 7 | read + write + execute | rwx |

<img width="819" alt="Screen Shot 2021-10-30 at 19 17 28" src="https://user-images.githubusercontent.com/92652606/139542756-9b503413-33a5-4855-9ca1-25b0923d81ba.png">

***symbolic Notation :***

<b>User Type </b> : ```u=user , g=group  o=other(all)```

<b> Add , remove or set Permission </b> : ```+ - =```

<b> Permission </b> : ```rwx read write execute```

<img width="530" alt="Screen Shot 2021-10-30 at 19 23 54" src="https://user-images.githubusercontent.com/92652606/139542969-3c3de1f4-e4fe-4c61-9013-14acef683695.png">

<h1> Some Special Permissions</h1>

* ***setuid bit*** : ( octal 4000 ) most time the root set this permissions to allow other users to run the setuid program.
* ```chmod u+s program``` : here we set setuid to a program .
 <img width="495" alt="Screen Shot 2021-10-30 at 19 29 03" src="https://user-images.githubusercontent.com/92652606/139543127-601896f3-3b0d-4ee3-9755-164dee6c4fab.png">
 
* ***setgid bit*** : ( octal 2000 ) wehen its set in a folder the files created in the folder will be given the group owenership.

* ```chmod u+g folder ```

* ***stickybit octal*** : ( 1000 ) only owner can delete the file or the folder if stickbit is set

* ```chmod u+t folder ```

* ``` su ``` : Run a Shell with Substitute User and Group IDs

```su -l Username```   : switch to other user

```su -c ls usrename``` : run a command as an other user

* ``` Sudo ``` : Excute a Command as Another User.

```sudo su - ``` : here we will excute su and log as root user.

<img width="434" alt="Screen Shot 2021-10-30 at 19 39 04" src="https://user-images.githubusercontent.com/92652606/139543431-fcaca2ef-a6da-4a14-bed6-1040e10bc213.png">

``` sudo -l``` : lists the user’s privileges, or checks a specific command

<img width="1359" alt="Screen Shot 2021-10-30 at 19 39 44" src="https://user-images.githubusercontent.com/92652606/139543457-01b93044-32af-4446-a26a-646bc3bce9f5.png">

``` sudo ls ```:  run the ls command as root user.

* ```Chown``` : Change File Owner and Group.

<img width="529" alt="Screen Shot 2021-10-30 at 19 44 21" src="https://user-images.githubusercontent.com/92652606/139543590-6c64b033-12a0-433c-b513-b3de5958c78e.png">

* ```Passwd``` : Changing Your Password
```passwd username```

    ```passwd mastermind```
    
            Changing password for mastermind.
            
                Current password:
                
                New password:
                
                Retype new password:
                
                passwd: password updated successfully






