# Лабораторная работа №2

## Задание 1 
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B2.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B3.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B4.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B5.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B6.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B7.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B8.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B9.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B10.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B11.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B12.png)
![](https://github.com/igritt13/LabY/blob/master/images/za1%3B14.png)  
### Мы установили виртуальную машину и настроили в ней RAID и LVM.

## Задание 2  
![](https://github.com/igritt13/LabY/blob/master/images/15.png)  
![](https://github.com/igritt13/LabY/blob/master/images/16.png)  
![](https://github.com/igritt13/LabY/blob/master/images/17.png)  
![](https://github.com/igritt13/LabY/blob/master/images/18.png)  
![](https://github.com/igritt13/LabY/blob/master/images/19.png)  
![](https://github.com/igritt13/LabY/blob/master/images/20.png)  
![](https://github.com/igritt13/LabY/blob/master/images/21.png)  

### Мы проимулировали отказ одного из дисков и воостановили его с помощью RAID.  

## Задание 3  
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B2-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B2-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B4.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5-2.png)  
На sdb появились разделы sdb1 и sdb2.
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5-3.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5-4.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B5-5.png)  
Операцию grub-install /dev/YYY мы выполняли чтобы установить загрузчик группы на новый диск.
После команды cat /proc/mdstat мы видим, что повился второй RAID массив.
После команды lsblk -o NAME,SIZE,FSTYPE,TYPE,MOUNTPOINT мы видим, что в директории sbd повился RIAD массив md63.
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-3-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-3-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-4.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B6-5.png)
После команды lsblk -o NAME,SIZE,FSTYPE,TYPE,MOUNTPOINT мы видим, что RAID массив уже подключён.
После команды pvs мы может увидеть, что для нового RAID массива появился физический том.
Сейчас LV var,log,root находятся на старом диске.
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B7.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B8-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B8-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B9-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B10-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B11.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B12-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B12-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B12-3.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B13.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B14.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B15.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B16.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B17.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B18-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B18-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B18-3.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B18-4.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19-2.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19-3.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19-4.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B19-4-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B20.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B21.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B21-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B22.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B22-1.png)
![](https://github.com/igritt13/LabY/blob/master/images/ZA3%3B22-2.png)  
### Мы успешно поставили четыре новых диска и перенесли на них данные системы. 
