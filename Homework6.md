[homework](https://launchschool.com/books/ruby/read/intro_exercises)> your homework should be in a new branch, pushed to your fork within `<your_name>/lesson6/homework.rb`

```rb
sturcture of file
# problem 1
# pasted task
# in multiline format

< your solution>
# problem 2...
```

### for instance:
```
# problem 1
# Use the each method of Array to
# iterate over [1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
# and print out each value.
arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# one line version
arr.each { |number| puts number }

# multi-line version
arr.each do |number|
  puts number
end
```
#### good luck :)

# Problem 1
Use the each method of Array to iterate over [1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
and print out each value.

# Problem 2
Same as above, but only print out values greater than 5.

# Problem 3
Now, using the same array from #2, use the select method to extract all odd numbers into a new array.

# Problem 4
Append 11 to the end of the original array. Prepend 0 to the beginning.

# Problem 5
Get rid of 11. And append a 3.

# Problem 6
Get rid of duplicates without specifically removing any one value.

# Problem 7
Tell what's the major difference between an Array and a Hash?

# Problem 8
Suppose you have a hash h = { a:1, b:2, c:3, d:4 }
1. Get the value of key `:b`.
2. Add to this hash the key:value pair `{e:5}`
3. Remove all key:value pairs whose value is less than 3.5

# Problem 9
Can hash values be arrays? Can you have an array of hashes? (give examples)

# Problem 10
Given the following data structures. Write a program that copies the information from the array
into the empty hash that applies to the correct person.

contact_data = [["joe@email.com", "123 Main st.", "555-123-4567"],
            ["sally@email.com", "404 Not Found Dr.", "123-234-3454"]]

contacts = {"Joe Smith" => {}, "Sally Johnson" => {}}

# Expected output:
{
  "Joe Smith"=>{:email=>"joe@email.com", :address=>"123 Main st.", :phone=>"555-123-4567"},
  "Sally Johnson"=>{:email=>"sally@email.com", :address=>"404 Not Found Dr.",  :phone=>"123-234-3454"}
}

# Problem 11
Using the hash you created from the previous exercise,
demonstrate how you would access Joe's email and Sally's phone number?

# Problem 12
Use Ruby's Array method delete_if and String method start_with? to delete
all of the words that begin with an "s" in the following array.

arr = ['snow', 'winter', 'ice', 'slippery', 'salted roads', 'white trees']

Then recreate the arr and get rid of all of the words that start with "s" or starts with "w".

# Problem 13
Take the following array:

a = ['white snow', 'winter wonderland', 'melting ice','slippery sidewalk', 'salted roads', 'white trees']

and turn it into a new array that consists of strings containing one word.
(ex. ["white snow", etc...] → ["white", "snow", etc...].
Look into using Array's map and flatten methods, as well as String's split method.

# Problem 14
What will the following program output?

hash1 = {shoes: "nike", "hat" => "adidas", :hoodie => true}
hash2 = {"hat" => "adidas", :shoes => "nike", hoodie: true}

if hash1 == hash2
  puts "These hashes are the same!"
else
  puts "These hashes are not the same!"
end

# Problem 15
Programmatically loop or iterate over the contacts hash from exercise 10,
and populate the associated data from the contact_data array.
Hint: you will probably need to iterate over ([:email, :address, :phone]),
some helpful methods might be the Array shift and first methods.



