# Storage Media 

* ```Mount ``` : Mount a filesystem

<img width="720" alt="Screen Shot 2021-10-30 at 21 08 39" src="https://user-images.githubusercontent.com/92652606/139555651-d265b969-93b9-4bc2-9e8e-738391f8cfd8.png">

<b> Filesystem Types : </b>

```ext3 , ext4 ```: ***linux***

```FAT26 ``` : ***msdos***

```FAT32``` : ***vfat***

```NTFS``` : ***Windows Filesystem***

```iso9660``` : ***CD-ROM***

```apfs ``` : ***appel filesystem***

* ```Umount ``` : Umount a filesystem.
  
  ```umount /dev/sdb1 ```
  
  <b> now we mount it in a different location </b>
  
![Screenshot at 2021-08-19 15-54-23](https://user-images.githubusercontent.com/92652606/139555845-a9dd54a5-7bd5-4cb7-8cab-2c3a78cc4e05.png)

* ```free ``` : Display amount of free and used memory in the system.

![Screenshot at 2021-08-19 15-57-36](https://user-images.githubusercontent.com/92652606/139555894-b456968b-9802-40e1-92c8-50bb3c643df0.png)

* ```df ``` : report file system disk space usage.

![Screenshot at 2021-08-19 16-09-02](https://user-images.githubusercontent.com/92652606/139555910-c39c162a-401f-4f37-845f-0e082a5edbce.png)

* ```fdisk ``` : Manipulating Partitions

![Screenshot at 2021-08-19 16-12-32](https://user-images.githubusercontent.com/92652606/139555943-ac9f8a46-ac13-4846-abf2-39bf1f0101fd.png)

* ```mkfs ``` : Creating a New Filesystem.

```sudo mkfs -t ext3 /dev/sdb1```

![Screenshot at 2021-08-19 16-17-54](https://user-images.githubusercontent.com/92652606/139555975-a8688fd4-1af5-4c5d-a96b-170300b6f511.png)

``` -t ``` : type of filesystem ( vfat , apfs , ntfs ..... )

* ```fsck ``` : Testing and Repairing Filesystems.

```fsck /dev/sdb1 ```

* ```dd ``` : Moving Data Directly to and From Devices .

```dd if=input_file of=output_file```

![Screenshot at 2021-08-19 16-55-16](https://user-images.githubusercontent.com/92652606/139556043-58bd1583-b5aa-4d75-8c4a-3fd08da69158.png)





