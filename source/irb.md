Welcome to Ruby Console User
>> def say_hi (name)
>>   puts "Hello there #{name}"
>>   end
nil
>> say_hi("Joe")
Hello there Joe
nil
>> a = "Hello"
"Hello"
>> a.upcase
"HELLO"
>> a
"Hello"
>> a.upcase!
"HELLO"
>> a
"HELLO"
>> b = "goodbye"
"goodbye"
>> a.object_id == b.object_id
false
>> a.object_id
70315418471700
>> b.object_id
70315418628360
>> a.inspect
"\"HELLO\""
>> b = { "name" => "Austin", "state" => "confused", "age" => 44}
{
     "name" => "Austin",
    "state" => "confused",
      "age" => 44
}
>> b.inspect
"{\"name\"=>\"Austin\", \"state\"=>\"confused\", \"age\"=>44}"
>> Math.sqrt(1282)
35.805027579936315
>> Time.now
2014-01-06 18:41:08 -0800
>> c = a
"HELLO"
>> c.object_id
70315418471700
>> a.object_id
70315418471700
>> b = "hello"
"hello"
>> a = "hello"
"hello"
>> a.object_id
70315419166760
>> b.object_id
70315419172580
>> Math.sqrt(64)
8.0
>> include Math
Object < BasicObject
>> sqrt(8)
2.8284271247461903
>>