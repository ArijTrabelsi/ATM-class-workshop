def withdraw(balance, request):
# allowed papers: 100 , 50 , 10 , 5 , and cents
    print('current balance= ', balance)
    result = balance
    
    if request > balance:
        print('cant give you all this money !')
        
    elif request < 0:
        print('more then zero plz!')
        
    else:
        result = balance - request
        while request>0:
        
            if request >= 100:
                request -= 100
                print('give 100')
                
            elif request >= 50:
                request -= 50
                print('give 50')
                
            elif request >= 10:
                request -= 10
                print('give 10')
                
            elif request >= 5:
                request -= 5
                print('give 5')
                
            elif request < 5:
                print('give' + str(request))
                request = 0
        return result

balance = 500

balance = withdraw(balance, 277)
balance = withdraw(balance, 30)
balance = withdraw(balance, 5)
balance = withdraw(balance, 500)
