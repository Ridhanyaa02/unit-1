# Quiz 10
### Paper solutions 
![image](https://github.com/user-attachments/assets/984288fc-ada3-4259-baa7-818a6366ef4c)

### Code 
```.py
def poweroften(input=int):
    name = ["pico","nano","micro","milli","unit","kilo","mega","giga","tera"]
    item_index = 0
    for i in range(-12,15,3):
        item = name[item_index]
        if i < -4:
            n = i+1
        multiplier = 10**i
        output = input * multiplier

        output = f'{output:.12f}'
        print(f'{format(output).rstrip('0').rstrip('.')} {item}')
        item_index += 1

poweroften()
```

### Proof of work 
![image](https://github.com/user-attachments/assets/94e8f628-7c6d-4639-af51-056a2a61af69)

### Flowchart
![Quiz 10](https://github.com/user-attachments/assets/2155526e-14bd-48e7-927b-d20d7fc95b03)
