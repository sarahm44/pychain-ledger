# PyChain Ledger

![](/Images/application-image.png)

## Overview

In this repository my task was to build a blockchain-based ledger system, complete with a user-friendly web interface (using [Streamlit](https://streamlit.io/)). 

This ledger should allow individuals to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Required Tasks

I was required to make the following updates to the provided Python file:

1. Create a new data class named `Record`. 
2. Modify the existing `Block` data class to store `Record` data.
3. Add Relevant User Inputs to the Streamlit interface.
4. Test the PyChain Ledger by Storing Records.

### Step 1: Create a Record Data Class

I defined a new Python data class named Record. 

I gave this new class a formalized data structure that consists of the sender, receiver, and amount attributes. 

![Alt_text](/Images/screenshot_1.png)

### Step 2: Modify the Existing Block Data Class to Store Record Data

I renamed the data attribute in the Block class to record, and then set it to use an instance of the new Record class that I created in the previous section. 

![Alt_text](/Images/screenshot_2.png)

### Step 3: Add Relevant User Inputs to the Streamlit Interface

I coded additional input areas for the user interface of your Streamlit application. 

I created these input areas to capture the sender, receiver, and amount, for each transaction that will be stored in the Block record.

![Alt_text](/Images/screenshot_3.png)

### Step 4: Test the PyChain Ledger by Storing Records

I tested the complete PyChain ledger and user interface by running the Streamlit application and storing some mined blocks in the PyChain ledger. 

![Alt_text](/Images/screenshot_4.png)

I then tested the blockchain validation process by using the web interface. 

![Alt_text](/Images/screenshot_5.png)
