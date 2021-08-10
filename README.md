# File-Opener--Python
Opening multiple system files using python


code:

import os
#importing os module

def fileopen(a):
    if(a=="paint"):
        os.startfile("mspaint.exe")
        #here startfile function in os module will open a corresponding file in mentioned address
        #os.startfile("Mention address of your file")

    elif(a=="wordpad"):
        os.startfile("wordpad.exe")

        
#if you want to add more FILES add up here in ELIF     

        

print("Listing files""\n"
      "paint""\n"
      "wordpad""\n")
#listing files we have to open


a=input("Enter a file to open:")
#Input a file name to open 
fileopen(a)
#Passing a file name value to fileopen()



