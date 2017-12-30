Last login: Fri Dec 29 07:58:50 on ttys004
Dominiques-MacBook-Pro:~ dominiquearanda$ irb
irb(main):001:0> puts "What is your first name?"
What is your first name?
=> nil
irb(main):002:0> first=Xitlaly 
NameError: uninitialized constant Xitlaly
	from (irb):2
	from /usr/bin/irb:12:in `<main>'
irb(main):003:0> first= Xitlaly
NameError: uninitialized constant Xitlaly
	from (irb):3
	from /usr/bin/irb:12:in `<main>'
irb(main):004:0> first= gets.chomp
gets.chomp= Xitlaly
=> "gets.chomp= Xitlaly"
irb(main):005:0> puts "What is your middle name?"
What is your middle name?
=> nil
irb(main):006:0> middle= gets.chomp
gets.chomp= Araceli
=> "gets.chomp= Araceli"
irb(main):007:0> puts "What is your last name?"
What is your last name?
=> nil
irb(main):008:0> last = gets.chomp
gets.chomp= Aranda
=> "gets.chomp= Aranda"
irb(main):009:0> puts "Hello " + first + ' ' + middle + ' ' + last + " nice to meet you."
Hello gets.chomp= Xitlaly gets.chomp= Araceli gets.chomp= Aranda nice to meet you.
=> nil
irb(main):010:0> puts "What is your first name?"
What is your first name?
=> nil
irb(main):011:0> first = gets.chomp
Xitlaly
=> "Xitlaly"
irb(main):012:0> puts "What is your middle name?"
What is your middle name?
=> nil
irb(main):013:0> middle = gets.chomp
Araceli
=> "Araceli"
irb(main):014:0> puts "What is your last name?"
What is your last name?
=> nil
irb(main):015:0> last = gets.chomp
Aranda
=> "Aranda"
irb(main):016:0> puts "Hello " + first + ' ' + middle + ' ' + last + " nice to meet you."
Hello Xitlaly Araceli Aranda nice to meet you.
=> nil
irb(main):017:0> puts "What is your favorite number?" 
What is your favorite number?
=> nil
irb(main):018:0> input = gets.chomp.to_i
2    
=> 2
irb(main):019:0> puts "Here is your new favorite number " + (input + 1).to_s + " it's bigger so it's better :D"
Here is your new favorite number 3 it's bigger so it's better :D
=> nil
irb(main):020:0> 
