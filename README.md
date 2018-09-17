# Luhn Algorithm

## Context
After completing my capstone for Galvanize, I was fascinated by algorithms that use modulus 10.  In my capstone, modulus 10 was very helpful to predict if a transaction was income or not.  The luhn algorithm was the first one to pop up which I wanted to investigate.

## Background
The Luhn Algorithm is a checksum formula to validate a credit card's numbers to protect against accidental errors, not malicious attacks.  Most credit cards use this algorithm to distinguish valid numbers from mistyped or incorrect numbers.

## Algorithm using Python
I have written up the code in Jupyter Notebooks which you can view within this Repo.

## Taking this algorithm a step further
I want to know of all 16 digit credit cards, what percentage are legit numbers that can be used by Visa, Mastercard, Discovery, etc.

Assumptions:
* The left most digit must be 1-9 and not 0
* Computationally, it would take a long time to go through 10^16 numbers or 7,999,999,999,999,999 or 8 quadrillion numbers.  In other words, if my 3.2 GHz computer can do 3,200,000,000 computations, I estimate it would take me ~694 hours or early a month to compute this

## Mathematical Solution:
(Will be filled in later)

## Conclusion
Based on an initial run, 10% of all numbers are a valid luhn number.  In other words, credit card companies have 800 billion numbers to use at their finger tips.  However, since their are rules for what the first digit must be based on the card you use (example, MasterCard's unique first digit is 5, Visa's is 4, etc) this means if I was Visa I would have:
* ~1 quadrillion numbers to use
* 100 billion are valid luhn numbers

And I have to assume you want to ask if my credit card (Visa) is a valid luhn number?  The answer is yes! :)

Source: https://smallbusiness.chron.com/identify-credit-card-account-number-61050.html
