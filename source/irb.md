## Release 0
```ruby
>> def say_hi(name)
>>   return "Hi, #{name}"
>>   end
nil
>> say_hi("Roy")
"Hi, Roy"
```

## Release 1
```ruby
debugging-drill-use-a-repl-challenge (rickANDroy) $ irb
Welcome to Ruby Console User
>> var1 = "Hello"
"Hello"
>> var2 = 123
123
>> var3 = ['cat', 1, 'dog']
[
    [0] "cat",
    [1] 1,
    [2] "dog"
]
>> var4 = :cookie
:cookie
>> var5 = {:cats => 10, :dogs => 2, :birds => 1}
{
     :cats => 10,
     :dogs => 2,
    :birds => 1
}
>> var1.upcase!
"HELLO"
>> var1
"HELLO"
>> var3.pop
"dog"
>> var3
[
    [0] "cat",
    [1] 1
]
>> var5.object_id
70189510475440
>> var4.object_id
528168
>> string1 = "hello"
"hello"
>> string2 = string1
"hello"
>> string1.object_id
70189510505360
>> string2.object_id
70189510505360
>> string2 = "cat"
"cat"
>> string1
"hello"
>> string1.object_id
70189510505360
>> string2.object_id
70189510525120
>> puts var3.inspect
["cat", 1]
nil
>> p var3.inspect
"[\"cat\", 1]"
"[\"cat\", 1]"
>> print var5.inspect
{:cats=>10, :dogs=>2, :birds=>1}nil
```