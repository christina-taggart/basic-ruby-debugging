```shell
~ $ irb
Welcome to Ruby Console User
>> def say_hi(name)
>>   puts "Hi, #{name}"
>>   end
nil
>> say_hi("Shereef")
Hi, Shereef
nil
>> say_hi("Spencer")
Hi, Spencer
nil
>> say_hi(matt)
NameError: undefined local variable or method `matt' for main:Object
	from (irb):6
	from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> array = ["Matt", "Spencer", "Emily"]
[
    [0] "Matt",
    [1] "Spencer",
    [2] "Emily"
]
>> array.downcase!
NoMethodError: undefined method `downcase!' for ["Matt", "Spencer", "Emily"]:Array
	from (irb):8
	from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> array.map! {|person| person.downcase!}
[
    [0] "matt",
    [1] "spencer",
    [2] "emily"
]
>> matt = "Matt"
"Matt"
>> number = 3
3
>> hash = {}
{}
>> hash.object_id
70185886194800
>> hash.inspect
"{}"
>> number.inspect
"3"
>> array.inspect
"[\"matt\", \"spencer\", \"emily\"]"
>> Math.sqrt(9)
3.0
>> sqrt(9)
NoMethodError: undefined method `sqrt' for main:Object
	from (irb):18
	from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> include Math
Object < BasicObject
>> sqrt(9)
3.0
>> Math.sqrt(9)
3.0
>> include Time
TypeError: wrong argument type Class (expected Module)
	from (irb):22:in `include'
	from (irb):22
	from /Users/apprentice/.rvm/rubies/ruby-1.9.3-p448/bin/irb:16:in `<main>'
>> Time.now
2014-01-06 17:59:51 -0800
>>
```
