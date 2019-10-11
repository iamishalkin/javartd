DoublyLinkedList
================

.. java:package:: source
   :noindex:

.. java:type:: public class DoublyLinkedList

   This class implements a DoublyLinkedList. This is done using the classes LinkedList and Link.

   A linked list is similar to an array, it holds values. However, links in a linked list do not have indexes. With a linked list you do not need to predetermine it's size as it grows and shrinks as it is edited. This is an example of a double ended, doubly linked list. Each link references the next link and the previous one.

   :author: Unknown

Constructors
------------
DoublyLinkedList
^^^^^^^^^^^^^^^^

.. java:constructor:: public DoublyLinkedList()
   :outertype: DoublyLinkedList

   Default Constructor

DoublyLinkedList
^^^^^^^^^^^^^^^^

.. java:constructor:: public DoublyLinkedList(int[] array)
   :outertype: DoublyLinkedList

   Constructs a list containing the elements of the array

   :param array: the array whose elements are to be placed into this list
   :throws NullPointerException: if the specified collection is null

Methods
-------
delete
^^^^^^

.. java:method:: public void delete(int x)
   :outertype: DoublyLinkedList

   Delete the element from somewhere in the list

   :param x: element to be deleted
   :return: Link deleted

deleteHead
^^^^^^^^^^

.. java:method:: public Link deleteHead()
   :outertype: DoublyLinkedList

   Delete the element at the head

   :return: The new head

deleteTail
^^^^^^^^^^

.. java:method:: public Link deleteTail()
   :outertype: DoublyLinkedList

   Delete the element at the tail

   :return: The new tail

display
^^^^^^^

.. java:method:: public void display()
   :outertype: DoublyLinkedList

   Prints contents of the list

insertHead
^^^^^^^^^^

.. java:method:: public void insertHead(int x)
   :outertype: DoublyLinkedList

   Insert an element at the head

   :param x: Element to be inserted

insertOrdered
^^^^^^^^^^^^^

.. java:method:: public void insertOrdered(int x)
   :outertype: DoublyLinkedList

   Inserts element and reorders

   :param x: Element to be added

insertTail
^^^^^^^^^^

.. java:method:: public void insertTail(int x)
   :outertype: DoublyLinkedList

   Insert an element at the tail

   :param x: Element to be inserted

isEmpty
^^^^^^^

.. java:method:: public boolean isEmpty()
   :outertype: DoublyLinkedList

   Returns true if list is empty

   :return: true if list is empty

