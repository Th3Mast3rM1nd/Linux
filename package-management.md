# Package Management 

<b>Finding a Package in a Repository : </b>

* ```apt-get update ```

* ```apt-cache search search_string```


<img width="754" alt="Screen Shot 2021-10-30 at 20 51 45" src="https://user-images.githubusercontent.com/92652606/139555370-00de2fd4-37e0-4f9a-9ee6-628ece3d5fcd.png">

<b> Instaling a Package from a Repository </b>

* ```sudo apt-get install package_name ```

![Screenshot at 2021-08-19 00-45-08](https://user-images.githubusercontent.com/92652606/139555387-15474df8-efcc-4487-92ff-2c59fa751b46.png)

<b> Installing a package From a Package File </b>

* ``` dpkg --install package_file ```


![Screenshot at 2021-08-19 00-48-12](https://user-images.githubusercontent.com/92652606/139555426-43d7828f-a606-4c38-bb82-589cce6ff4f3.png)

<b>Removing a Package </b>

* ```apt-get remove package_name ```

![Screenshot at 2021-08-19 00-50-18](https://user-images.githubusercontent.com/92652606/139555441-fe071534-a6d3-49a7-9353-ed5f137ae8f4.png)

<b> Updating Packages From a Repository </b>

* ```sudo apt-get update ; sudo apt-get upgrade ```

<b>  updating a package from a Package File </b>

* ```dpkg --install package_file```

<b> Listing  Installed Packages  </b>

* ```dpkg --list ```

<b> Determining Whether a Package is Installed  </b>

* ``` dpkg --status package_name ```

![Screenshot at 2021-08-19 00-56-44](https://user-images.githubusercontent.com/92652606/139555519-f12ad223-e736-4e78-9530-2c1c49e970b4.png)

<b> Display info About an installed package_name  </b>

* ```apt-cache show package_name```

![Screenshot at 2021-08-19 00-58-41](https://user-images.githubusercontent.com/92652606/139555547-0a6304ac-fc19-4171-853c-3c66c87367d6.png)





