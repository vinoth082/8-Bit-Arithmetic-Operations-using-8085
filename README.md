# 8-Bit-Arithmetic-Operations-using-8085
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

## Apparatus Required:
•	Laptop with internet connection

## Algorithm:

### For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
   
### Program:


<img width="520" height="431" alt="Screenshot 2025-08-08 161147" src="https://github.com/user-attachments/assets/ed2421bd-6b99-4cc3-9297-378f83698ae3" />


### Output:


<img width="1906" height="1097" alt="Screenshot 2025-08-08 162112" src="https://github.com/user-attachments/assets/20503a76-3a01-45ca-b893-81f70fdb20a4" />

<img width="1830" height="1017" alt="Screenshot 2025-08-08 162056" src="https://github.com/user-attachments/assets/2000861c-62e4-44fd-be47-fee09f36c95e" />



### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program:

<img width="506" height="332" alt="Screenshot 2025-08-24 233607" src="https://github.com/user-attachments/assets/cbf437fa-4460-4631-b448-585a4c409b7a" />


### Output:


<img width="1908" height="1093" alt="Screenshot 2025-08-22 154220" src="https://github.com/user-attachments/assets/d7e10f64-bcf3-498e-9937-4af5fd68c7d3" />



<img width="1883" height="1088" alt="Screenshot 2025-08-22 154158" src="https://github.com/user-attachments/assets/7215f6e0-4d95-456b-853d-f666a166d8a1" />




### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:

<img width="417" height="322" alt="image" src="https://github.com/user-attachments/assets/26f208d3-741c-42b1-b92a-2aecdeaf518d" />


### Output:


<img width="1915" height="1071" alt="Screenshot 2025-08-22 154729" src="https://github.com/user-attachments/assets/66341cde-7464-4788-b636-ca9747590e89" />



<img width="1882" height="1080" alt="Screenshot 2025-08-22 154717" src="https://github.com/user-attachments/assets/2df44210-f752-4b05-a2f0-58a627349296" />



### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:


<img width="497" height="587" alt="image" src="https://github.com/user-attachments/assets/b16491ff-ae9a-47bb-9b0e-6d8a03523d5e" />


### Output:

<img width="1865" height="952" alt="Screenshot 2025-08-22 162320" src="https://github.com/user-attachments/assets/ebba684f-090a-40ff-af63-f18bef68dda4" />


<img width="1884" height="994" alt="Screenshot 2025-08-22 162341" src="https://github.com/user-attachments/assets/284b6ee5-6c69-44e9-ab08-a973c23a8d41" />



## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

