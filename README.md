A blockchain with a set of rules for verifying new additions to the database. We'll start off by tracking the accounts of two imaginary people: Alice and Bob, who will trade virtual money with each other.

We'll need to create a transaction pool of incoming transactions, validate those transactions, and make them into a block.

We'll be using a hash function to create a 'fingerprint' for each of our transactions- this hash function links each of our blocks to each other. To make this easier to use, we'll define a helper function to wrap the python hash function that we're using.
