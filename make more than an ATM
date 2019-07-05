# Class ATM
class ATM:
    
    def __init__(self, bank_name, balance):
        self.bank_name = bank_name
        self.balance = balance
        
    def withdraw(self,request):
    
        if request > self.balance :
            print('cant give you all this money!!')
         
        elif request < 0 :
            print('more then zero plz!!')
         
        else:
            self.balance -= request    
            while request > 0:
             
                if request >= 100:
                    print ('give 100')
                    request -= 100
                 
                elif request >50:
                    print ('give 50')
                    request -= 50
                 
                elif request >= 10:
                    print ('give 10')
                    request -= 10
                 
                elif request >= 5:
                    print ('give 5')
                    request -= 5
                 
                else:
                    print ('give'+ str(request))
                    request = 0 
            print('rest=', self.balance )
            return self.balance
        
# Use of Class ATM
def app_sys():
    import sys
    
    bank_Savings= ATM('savings', 700)
    bank_Central= ATM('central', 1150)
    
    while True :
        
        option = input('1 * Savings | 2 * Central | 3 * Exit -> :')

        request = int(input('request :'))
        
        if option == '1' :
            bank_savings.withdraw(request)
        
        elif option == '2' :
            bank_central.withdraw(request)
       
        elif option == '3' :
            sys.exit()
       
        else:
            print('[!] wrong option !')

    app_sys()
