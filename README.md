# Insert-at-the-Beginning
#Write a function that takes a tuple and a value, and returns a new tuple with the value inserted at the beginning of the #original tuple

def insert_value_front(input_tuple, value_to_insert):
    
   list1 = (list(input_tuple))
   list1.insert(0,value_to_insert)

   new_tuple = tuple(list1)  
   return new_tuple

   
input_tuple = (2,3,4)
value_to_insert = 6
print(insert_value_front(input_tuple, value_to_insert))
