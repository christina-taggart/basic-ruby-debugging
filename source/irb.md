###Release 0

>> def say_hi(name)
>>   puts "Hello, #{name}!"
>>   end
nil
>> say_hi("John")
Hello, John!
nil
>>

###Release 1
>> my_array = [1, 1, 2, 3, 5]
[
    [0] 1,
    [1] 1,
    [2] 2,
    [3] 3,
    [4] 5
]
>> my_array.inject(:*)
30
>> my_array.inject(*)
SyntaxError: (irb):7: syntax error, unexpected ')'
  from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> factorial = my_array.inject(:*)
30
>> my_array.map { |num| num*3 }
[
    [0] 3,
    [1] 3,
    [2] 6,
    [3] 9,
    [4] 15
]
>> my_array
[
    [0] 1,
    [1] 1,
    [2] 2,
    [3] 3,
    [4] 5
]
>> my_array.map! { |num| num*3 }
[
    [0] 3,
    [1] 3,
    [2] 6,
    [3] 9,
    [4] 15
]
>> my_array
[
    [0] 3,
    [1] 3,
    [2] 6,
    [3] 9,
    [4] 15
]
>>

###Release 2
>> include Math
Object < BasicObject
>> sqrt 64
8.0
>> sqrt 255
15.968719422671311
>> sqrt PI
1.7724538509055159
>> Time.now
2014-01-06 17:28:19 -0800
>> right_now = Time.now
2014-01-06 17:28:42 -0800
>> right_now
2014-01-06 17:28:42 -0800
>>
Display all 384 possibilities? (y or n)
>> right_now is_a? String
NoMethodError: undefined method `right_now' for main:Object
  from (irb):20
  from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> right_now.is_a? String
false
>> right_now.class
Time < Object
>> right_now.is_a? Time
true