# Marks-to-Percentage-convertor
#Simple Mark to percentage convertor in python in just 9 line
print('------Marks to Percentage Convertor------')
subject = input('Subject name : ')
mark = input('how many marks is the '+subject+' exam : ')
percentage = 100 / int(mark)
leave = input("""'how many marks did you leave' or 'how many marks will be cut' in 
 paper (approximately) : """)
cutmark = percentage * float(leave)
a = 100 - float(cutmark)
print('you get',a,'% mark out of 100 %')

#thankyou
