# Quiz 11 
### Paper solutions 
![image](https://github.com/user-attachments/assets/a41bba63-1361-442e-8f89-5347d0ba527f)

### Code
```.py
import calendar

def dates(month:str):
    month1 = ["January","Febuary","March","April","May","June","July","August","September","October","November","December"]
    months = {
        "January":31,"Febuary":28,"March":31,"April":30,"May":31,"June":31,"July":30,"August":31,
    "September":31,"October":31,"November":30,"December":31}

    for key in months:
        if key == month:
            i = key
            days = months[key]

    week = ["Mon","Tue","Wed","Thu","Fri","Sat","Sun"]
    month_number = month1.index(month) + 1
    first_day, _ = calendar.monthrange(2024, month_number)

    print(month, "2024")
    w = first_day

    for i in range(1,days + 1):
        weekday = week[w]
        w += 1

        if w > 6:
            w = 0

        print(weekday, i)

dates("Febuary")
```

### Proof of work
![image](https://github.com/user-attachments/assets/00f61ac3-f27d-4d96-87f2-8aef6452026b)
![image](https://github.com/user-attachments/assets/be4ec864-173d-4fe3-8542-4cddb9ec5f05)


### Flowchart
![Quiz 11](https://github.com/user-attachments/assets/6503fc17-4764-4a3b-881e-8187650e5b09)
