
def main():
     print(myFirstVariable)

myFirstVariable = "Hello Jesus!!"

main()
print(myFirstVariable)
main()

#count.py
#Prog to ask user for name and number, then count by 2's

#Title
print("                                   ####Counting by 2s##### ")
print("                                                      word ")

myName=input('Your name?').capitalize()

while (myName==""):
    print('Name is blank genius!')
    myName=input('Your name???').capitalize()


while (len(myName)<2 or len(myName)>20):
    print('Name can only be 20 characters max, pay attetion!!')
    myName=input('Your name please??').capitalize()
print("Hello"+" " +myName)
endNum=input('Enter number:')
endNum=int(endNum) #Convert string to integer

input('Counting to' + str(endNum) + '- press enter to start:')

for x in range (0,endNum + 1,1):
    
    print(x)
