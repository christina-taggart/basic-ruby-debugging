>> def say_hi(name)
>>   "Hi, #{name}"
>>   end
nil
>> say_hi("henry")
"Hi, henry"
>>

>> henry_hsu.object_id
70123897767660
>> henry_hsu.inspect
"{:first_name=>\"Henry\"}"
>> pair = ["Henry", "Patrick]
^C
>> pair = ["Henry", "Patrick"]
[
    [0] "Henry",
    [1] "Patrick"
]
>> pair.sort!
[
    [0] "Henry",
    [1] "Patrick"
]
>> pair.map{|x| x.uppercase}
NoMethodError: undefined method `uppercase' for "Henry":String
  from (irb):16:in `block in irb_binding'
  from (irb):16:in `map'
  from (irb):16
  from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> pair.map{|x| x.upcase}
[
    [0] "HENRY",
    [1] "PATRICK"
]
>> pair
[
    [0] "Henry",
    [1] "Patrick"
]
>> pair.map!{|x| x.upcase}
[
    [0] "HENRY",
    [1] "PATRICK"
]
>> pair
[
    [0] "HENRY",
    [1] "PATRICK"
]

>> include Math
Object < BasicObject
>> sqrt 64
8.0
>> Time.now
2014-01-06 18:29:42 -0800