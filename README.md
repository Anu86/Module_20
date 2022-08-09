# Module_20
# Module_20
To automate the creation of joint savings accounts this solidity smart contract accepts two user addresses and enables the functionality to deposit and withdraw funds from the account.

## Implementation
1. Declare variables for account 1 & 2 of the type address payable . That way these addresses can send & transfers . These data types can store 20 bytes, that's the size f typical ether addresses. 
2. Declare unsigned intgers lastWithdrawAmount, contractBalance
3. Declare address lastToWithdraw
4. Function to deposit where we set the contractBalance to the balance in the address.
5. Witdraw funactionality to transfer to confirm address of recipient & transfer and update balance
6. Include fallback function 

## Reference to Images added  
1. Image 1: Set up Ethereum address 
2. Image 2: Test the deposit functionality - Send 1 ether as wei. Verify contract balance
3. Image 3 : Test the deposit functionality - Send 10 ether as wei. Verify contract balance
4. Image 4 :Test the deposit functionality - Send 5 ether 
5. Image 5 : Test the contract’s withdrawal functionality - withdraw 5 ether into accountOne 
6. Image 6 : Test the contract’s withdrawal functionality - 
withdraw 10 ether into accountTwo
7. Check contract balance
8. Check lastToWithdraw & lastWithdrawAmount


 
