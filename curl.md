# Curl 

* ```curl ``` : transfer a URL.

```-i``` : curl will send a GET request and print as well the headers .

<img width="1067" alt="Screen Shot 2021-10-30 at 20 45 02" src="https://user-images.githubusercontent.com/92652606/139555049-bd3b4ad9-d617-4f4c-8002-b346f1b36004.png">

```-I``` : get just the head respons without the body .

<img width="563" alt="Screen Shot 2021-10-30 at 20 47 10" src="https://user-images.githubusercontent.com/92652606/139555109-f1b3b8cb-474d-4d58-bdf5-e6affaf4c9b5.png">

```curl -I -L www.example.com/redirect``` : here will curl follow redirect if hearder is ***302***

```curl example.com/[0-9].html -o save.html``` : URL globing [a-z] -o to save output to a file 

```-v``` : verbose mode for curl 

```curl -I example.com -H "User-agent: firefox" ``` : sending a curl request with header user-agent . 

<img width="754" alt="Screen Shot 2021-10-30 at 20 51 45" src="https://user-images.githubusercontent.com/92652606/139555232-fd78da55-0b0a-4bdd-baee-94071000bc5d.png">



