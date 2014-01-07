# release 0
```
>> def say_hi(name)
>>   "Hi, #{name}"
>>   end
nil
>> say_hi("Elliot")
"Hi, Elliot"
>>
```

# release 1
```
>> ary = [1,2,3,4]
[
    [0] 1,
    [1] 2,
    [2] 3,
    [3] 4
]
>> str = "String
"
"String\n"
>> str.upcase!
"STRING\n"
>> str
"STRING\n"
>> str.object_id
70149390883340
>> str1 = "a"
"a"
>> str2 = "a"
"a"
>> str1.object_id == str2.object_id
false
>> str1.inspect
"\"a\""
>>
```

# release 2