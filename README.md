# Dictionary
Data_Structures_&amp;_Algorithms 

Brief

This assignment contains an application of AVL Trees which is a Dictionary application. The user is required to enter a valid and the meaning(s) of that words are displayed to the user.

Technical Approach

Initially, the application loads the words and their respective meaning from a CSV file and then stores them in an AVL Tree, while informing the user of the realtime progress of the operation. Each TreeNode has a meaning attribute which is a Singly Linked List of strings of the meaning(s) associated with that word (Assuming a single word can multiple associated with it). Each time user enters a word it is searched in the Tree and then the pointer to that node is returned and we use that pointer to extract all our relevant information.
