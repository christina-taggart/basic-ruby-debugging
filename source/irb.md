===========================
Release 0:
===========================

Welcome to Ruby Console User
>> def say_hi(name)
>>   p "Hi, #{name}"
>>   end
nil
>> say_hi "Shareef"
"Hi, Shareef"
"Hi, Shareef"

===========================
Release 1:
===========================

>> int_a = 3
3
>> int_b = 5
5
>> int_a + int_b
8
>> arr = [5,4,3,-1]
[
    [0] 5,
    [1] 4,
    [2] 3,
    [3] -1
]
>> arr.sort!
[
    [0] -1,
    [1] 3,
    [2] 4,
    [3] 5
]
>> arr_b = [-1,3,4,5]
[
    [0] -1,
    [1] 3,
    [2] 4,
    [3] 5
]
>> arr == arr_b
true
>> arr.object_id
70361110834700
>> arr_b.object_id
70361111046080
>> arr.object_id == arr_b.object_id
false
>> arr_c = arr
[
    [0] -1,
    [1] 3,
    [2] 4,
    [3] 5
]
>> arr_c.object_id == arr.object_id
true
>> me = "David"
"David"
>> name = "David"
"David"
>> me.object_id == name.object_id
false
>>

===========================
Release 2:
===========================

>> Math.sqrt(1282)
35.805027579936315
>> include Math
Object < BasicObject
>> Math.sqrt(1282)
35.805027579936315
>> Time.now
2014-01-06 17:34:59 -0800
>> Array.new(10, 'bee')
[
    [0] "bee",
    [1] "bee",
    [2] "bee",
    [3] "bee",
    [4] "bee",
    [5] "bee",
    [6] "bee",
    [7] "bee",
    [8] "bee",
    [9] "bee"
]
>> sqrt 64
8.0