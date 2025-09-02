# Declaring_variables_in_Ruby
การประกาศตัวแปรในภาษาRubyนั้น ชื่อของตัวแปรจะต้องประกอบไปด้วย ตัวอักษร ตัวเลขและเครื่องหมาย _ (Underscore) 
และไม่สามารถขึ้นต้นด้วยตัวเลขได้ เพื่อให้สามารถแยกแยะระหว่างตัวแปรและรหัสอื่นๆในโค้ดได้
#!/usr/bin/ruby

$global_variable = 10
class Class1
   def print_global
      puts "Global variable in Class1 is #$global_variable"
   end
end
class Class2
   def print_global
      puts "Global variable in Class2 is #$global_variable"
   end
end

class1obj = Class1.new
class1obj.print_global
class2obj = Class2.new
class2obj.print_global
