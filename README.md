# Inspirational Quotes Generator

A simple Python project that generates random inspirational quotes to keep you motivated.import random

# List of inspirational quotes
quotes = [
    "Believe you can and you're halfway there. - Theodore Roosevelt",
    "The only way to do great work is to love what you do. - Steve Jobs",
    "Success is not final, failure is not fatal: It is the courage to continue that counts. - Winston Churchill",
    "The best way to predict the future is to create it. - Peter Drucker",
    "The only limit to our realization of tomorrow will be our doubts of today. - Franklin D. Roosevelt"
]

# Function to print a random quote
def get_quote():
    return random.choice(quotes)

# Print a random quote
print(get_quote())
