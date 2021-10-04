# TestChain

Step 1: Create a Record Data Class
* Create a new data class named `Record`. This class will serve as the
blueprint for the financial transaction records that the blocks of the ledger
will store.

Step 2: Modify the Existing Block Data Class to Store Record Data
* Change the existing `Block` data class by replacing the generic `data`
attribute with a `record` attribute that’s of type `Record`.

Step 3: Add Relevant User Inputs to the Streamlit Interface
* Create additional user input areas in the Streamlit application. These
input areas should collect the relevant information for each financial record
that you’ll store in the `PyChain` ledger.

Step 4: Test the PyChain Ledger by Storing Records
* Test your complete `PyChain` ledger.


Verify the block contents and hashes in the Streamlit drop-down menu.
Take a screenshot of the Streamlit application page, which should detail a
blockchain that consists of multiple blocks. Include the screenshot in the
`README.md` file for your Challenge repository.
![image](https://user-images.githubusercontent.com/84469885/135788542-0ff3a62f-39a9-4bd0-95de-0c9e539c23ef.png)


Test the blockchain validation process by using the web interface.
Take a screenshot of the Streamlit application page, which should indicate
the validity of the blockchain. Include the screenshot in the `README.md`
file for your Challenge repository.
![image](https://user-images.githubusercontent.com/84469885/135788642-75a9ba06-2e45-4827-9dbd-70750955146f.png)
