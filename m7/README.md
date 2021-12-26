> I've created file script for:

displaying the IP addresses and symbolic names of all hosts in the current subnet
displaying a list of open system TCP ports
![1](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m7/%20task7.1%201.png)

> Results:
![2](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m7/task7.1%202%20.png)
![3](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m7/task7.1%203.png)

>I've created file script for analize apache log file and use in it next commands:

awk '{print $1}' $1 | sort | uniq -c | sort -gr

awk '{print $7}' $1 | sort | uniq -c | sort -gr

awk '{print $1 " : " $7}' $1 | grep 'error404' | sort | uniq -c | sort -gr

awk '{ print $4}' $1 | awk -F : '{ print $2 ":" $3}' | sort | uniq -c | sort -gr

awk '{ print $14 " \t " $1}' $1 | grep -i 'bot' | sort | uniq -c | sort -gr

![4](https://github.com/anastasiia-honcharenko/DevOps_online_Dnipro_2021Q4/blob/main/m7/task7.1%204.png)
