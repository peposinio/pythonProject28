# pythonProject28


#f = open("first.txt", "w")
#f.write("hello world!!!")

#import shutil

#shutil.copyfile("first.txt", "second.txt")

import shutil

test = open("C:\\Users\\User\\Desktop\\test1\\test_image.jpg", "rb")
root = open("C:\\Users\\User\\Desktop\\test2\\test_image.jpg", "ab")


shutil.copyfile(test, root)
