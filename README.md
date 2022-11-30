# Electricity-Bill
name=input('Name of the consumer:')
num=int(input('Enter Power bill number:'))
units=int(input('Enter no. of units you consumed:'))
if units>200:
    amount=units*5.2
elif units>100:
    amount=units*3.2
elif units>50:
    amount=units*2.6
else:
    amount=units+100
print('Consumer Name:',name)
print('Power bill number:',num)
print('No. of units:',units)
print('Total Amount:',amount)
