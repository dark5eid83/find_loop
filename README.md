# find_loop
Determine if there is a loop in a linked list

Write a function that takes in the head of a singly linked list that contains a loop (i.e., the list's tail node points to some node in the list instead of the null value). The function should return the actual node from which the loop originates in constant space. Every node, in the singly linked list has a value and a next pointer which points to the next node in the list.

Sample input:
n0 -> n1 -> n2 -> n3 -> n4 -> n5 -> n6
                        |           |
                        n9 -> n8 -> n7
                        
                        
Sample output: n4                      
