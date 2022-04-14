#30DaysOfCode
# Day 2
# List to set
# Create a function that takes in a list as input and returns 
# it a new list with all the repittions reduced to one appearances alone.


# we converts the list in to a set, a set will return the list item without repition
 
def convert_list_to_set(hot_list):
    cold_list = set()
    mo_de = max(set(hot_list), key = hot_list.count )
    for i in hot_list:
        cold_list.add(i)
    print("the Mode  of the set is (%s)" %mo_de)
    return cold_list   

# we creat a list
hot_list = [1,1,1,12,2,2,2,3,3,3,3,4,4,4,5,6,6,6,6,6,6,6,6,4,45,4,56,5,6,65,6,6,7,898,7,8,9,87,87,'r','r','t''r','t''r','t']
miyagi = convert_list_to_set(hot_list)
print(miyagi)