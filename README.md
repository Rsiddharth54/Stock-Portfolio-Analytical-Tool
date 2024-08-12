# Stock-Portfolio-Analytical-Tool

This a comprehensive stock portfolio analytic tool that gives new users to the stock market an insight into the factors that actually affect a stock.

# Steps

1. We were able to source data, 128 stocks, that ranged from stocks within the AI/fintech sector to bonds and mutual funds, all from the yahoo finance library on python.

2. We were able to obtain 3 scores;
    a. Raw Total Score =  all the factors of a stock summed up
    b. Total Score =  The score of this was based on each factor being divided by the maximum amount out of all the stocks. For example, if the PE_SCORE minimum was -4.9, the absolute value of that would be added to each PE_SCORE for every stock. We would do this to eliminate all negative values. Then, we divided each columnn values by the maximum to create a scale of 0-1.
   c. Normalized Total Score = We simply took the Total Score and created a more reasonable scaling. It ranged from -100 to 100.
<img width="704" alt="Screenshot 2024-08-12 at 3 30 15 PM" src="https://github.com/user-attachments/assets/7c660c63-979c-42bb-a937-3e0095fa41d5">

4. Using the scores we were able to determine statistical outcomes when comparing to the factors that affected a stock.

5. Results = 
<img width="663" alt="Screenshot 2024-08-12 at 3 31 24 PM" src="https://github.com/user-attachments/assets/05b4903a-9cff-4f8e-9240-bf3bac883810">
<img width="693" alt="Screenshot 2024-08-12 at 3 31 47 PM" src="https://github.com/user-attachments/assets/f0a9cc69-b5a0-4bf5-b0b6-1632c9f0dc91">
<img width="704" alt="Screenshot 2024-08-12 at 3 32 02 PM" src="https://github.com/user-attachments/assets/d12ab3fd-9cf0-433b-9b84-991ed18b25fd">
<img width="684" alt="Screenshot 2024-08-12 at 3 32 14 PM" src="https://github.com/user-attachments/assets/aa1f5675-5e28-493f-8d9d-7f0740c697eb">
<img width="681" alt="Screenshot 2024-08-12 at 3 33 48 PM" src="https://github.com/user-attachments/assets/cdd8aa9d-e125-41fe-9a36-ca715bec5ed1">
<img width="646" alt="Screenshot 2024-08-12 at 3 34 01 PM" src="https://github.com/user-attachments/assets/d8428c47-3a6d-4364-b585-08ee2a71482d">
