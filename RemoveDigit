+

ifn = input("Please input the file'path that you want to modify!")
ofn = "new.txt"
 
infile = open(ifn,'r+')
outfile = open(ofn,'w')
for eachline in infile.readlines():
    for i in eachline:
        if i.isdigit() == True:
            eachline = eachline.replace(i,'')
    outfile.write(eachline)
infile.close
outfile.close

infile = open(ofn,'r+')
outfile = open(ifn,'r+')
for eachline in infile.readlines():
    outfile.write(eachline)
infile.close()
outfile.close()

import os
os.remove(ofn)
    
