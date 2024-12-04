This Java program implements a **Doubly Linked List** with basic operations such as inserting elements at the beginning of the list and inserting a new node at a specified position in the middle of the list. The program allows users to create a doubly linked list by repeatedly entering integers until they input `-1`, at which point the list is constructed. The user can then insert a new node at a given position by specifying the position number. The `insert_At_Middle` method allows insertion at any valid position within the list, and if the position is beyond the current length, the new node is added at the end. The `display` method is used to print the elements of the list. Each node in the list contains an integer value along with pointers to the previous and next nodes, ensuring bidirectional traversal of the list. This implementation demonstrates key concepts of doubly linked lists, such as node creation, insertion at specific positions, and list traversal in Java.
Sample input:
10 20 30 40 -1
Sample ouput:
Enter the items to insert:
10 20 30 40 -1
Enter the item to insert in middle:
59
Enter the position:
2
40 30 50 20 10 
