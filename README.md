# Shopping Cart Project NYU

## Installation

Clone or download from https://github.com/jsr512/shopping-cart then navigate to the local repositorty:

    ''
    cd shopping-cart
    ''

Create and activate a new a virtual enviorment "shopping-env"

    ''
    conda create -n shopping-env
    conda activate shopping-env
    ''

Install the sendgrid package within the virtual enviorment 

    ''
    pip install sendgrid==6.0.5
    ''

## Usage 

Run the program:

    ''
    python shopping-cart.py
    ''

Enter the items purchased using the number of each item
Enter "DONE" once complete
Your receipt will be printed 
A prompt will ask if you would like to received an email. Entere "Y" or "N"


