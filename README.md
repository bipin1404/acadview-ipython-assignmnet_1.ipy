# acadview-ipython-assignmnet_1.ipy
##question 1
list1=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16]
#original list
print(list1)
list2=list1[7:12]#positive slicing
list3=list1[-9:-4]#negative slicing
#updated list
print(list2)
print(list3)
##question 2

lis1=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16]
print(lis1[1::2])

##question 3

lis2=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16]
lis3=lis2[::4]
print(lis3)
output:
question 1:
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16]
[8, 9, 10, 11, 12]
[8, 9, 10, 11, 12]
question 2:
[2, 4, 6, 8, 10, 12, 14, 16]
question 3:
[1, 5, 9, 13]
