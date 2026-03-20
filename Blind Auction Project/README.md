# Blind Auction System

A simple and interactive command-line Blind Auction system built using Python.

This project allows multiple users to place bids secretly. Each participant enters their name and bid amount, and the system determines the highest bidder without revealing others' bids during the process. Once all bids are submitted, the program announces the winner with the highest bid.

The project demonstrates core Python concepts such as dictionaries, loops, conditionals, functions, and user input handling.

---

## Features

- Multiple users can participate in the auction  
- Each bidder enters their name and bid amount  
- Bids are stored securely using a dictionary  
- Continuous bidding until users choose to stop  
- Automatically determines the highest bidder  
- Displays the winner and winning bid  
- Clean and simple command-line interaction  

---

## Technologies Used

- Python  
- Dictionaries  
- Loops (while loop)  
- Conditional statements (if-else)  
- Functions  
- User input handling  
- Basic console formatting  

---

## Project Structure

blind-auction  
├── main.py  
├── art.py  

---

## How It Works

1. The program starts and displays the auction logo.  
2. A user enters their name and bid amount.  
3. The bid is stored in a dictionary with name as key and bid as value.  
4. The program asks if there are more bidders.  
5. If yes, the screen clears and the next user enters their bid.  
6. If no, the program compares all bids.  
7. The highest bidder is identified and displayed as the winner.  

---

## Learning Outcomes

Through this project, I learned how to:

- Use dictionaries to store dynamic data  
- Implement loops for repeated user input  
- Write functions to process and compare data  
- Handle user interaction in command-line programs  
- Build simple real-world logic (auction system)  
- Structure Python programs cleanly  

---

## Example Output


Please enter your name: Vaishu  
Please enter your bid: 300  

Are there any new bids? Type 'yes' or 'no': no  

The winner is Vaishu with a bid of $300  


---

## Conclusion

This project is a beginner-friendly implementation of a real-world auction system using Python. It strengthens understanding of data structures, control flow, and user interaction, making it a valuable addition to a beginner's programming portfolio.
