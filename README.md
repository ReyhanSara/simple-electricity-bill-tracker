# simple-electricity-bill-tracker
A program written in C lang to keep track of electricity bill of a house

The program keeps track of the electricity bill of a house with following features.

When the program is executing for the first time ask for the last months metre reading and the bill amount
Then program would display last metre reading and the bill amount at the top and below it program should display a main menu of different choices 
        [1]. Enter this months reading
        [2]. Enter payment details
        [3]. View payment history
        [4]. View monthly power consuption

The program maintains a text file with three colums Month number, meter reading, payment;
Situation 1 - when meter reading is updated (month =1, reading=251244, payment=0) the new row looks like
3    251244    0
Situation 2- a payment of 500 is made 
3    0    -500


