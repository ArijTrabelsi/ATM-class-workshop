class ATM:
    
    def __init__(self, bank_name, balance):
        self.bank_name = bank_name
        self.balance = balance
        self.withdrawals_list = []
        
    def withdraw(self, request):
        print('current balance = ', self.balance)
        
        if self.balance < request :
            print ('cant give you all the money !!')
            
        elif request < 0 :
            print ('more then zero plz !!')
            
        else:
            self.withdrawals_list.append(request)
            self.balance -= request
            
            notes = [100, 50, 10, 5]
            for note in notes :
                while request >= note :
                    request -= note
                    print('give ' + str(note))
                if request < 5 and request > 0 :
                    print('give ' + str(request))
                    request = 0        
   
            return self.balance
   
    def show_withdrawals(self):
        for withdrawal in self.withdrawals_list :
            print(withdrawal)
            
balance1 = 1000
balance2 = 755
            
atm1 = ATM('savings bank', balance1 )
atm2 = ATM('central bank', balance2 )

print('savings bank :') , atm1.withdraw(700)
print('savings bank :') , atm1.withdraw(300)         

print('central bank :') , atm2.withdraw(544)
print('central bank :') , atm2.withdraw(133)

print('withdrawal :')
atm1.show_withdrawals()
atm2.show_withdrawals()
