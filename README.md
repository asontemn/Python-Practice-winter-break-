# Python-Practice-winter-break-
Random little programs I made to practice Python

Name = 'jj'

if len(Name) < 3:
    print('name longer')
elif len(Name) > 50:
        print ('name shorter')
else:
    print('you good')
    
                                      New (Weight converter)
                                      
weight = int(input('weight: ')) #get user input and convert it to int
unit = input('(L)bs or (K)g: ')
if unit.upper() == "L": #converts user input to upper case.
    converted = weight * 0.45
    print(f'you are {converted} kilos')
else:
    converted = weight / 0.45
    print(f"you are {converted} pounds")
    
   
                                   New (While loop practice)
                                   
i = 1 #define i
while i <=5: #add condition for loop to continue over and over
    print(i) #print i everytime code loops 
    i = i + 1 #add 1 to i everytime code loops
print ("Done") #printt done when it loops enough times to equal 6                                  
    
