
Step 1
------

bubble sort

.. code-block:: java

    class BubbleSort implements SortAlgorithm {
        /**
         * This method implements the Generic Bubble Sort
         *
         * @param array The array to be sorted
         *              Sorts the array in increasing order
         **/

        @Override
        public <T extends Comparable<T>> T[] sort(T array[]) {
            for (int i = 0, size = array.length; i < size - 1; ++i) {
                boolean swapped = false;
                for (int j = 0; j < size - 1 - i; ++j) {
                    swapped = less(array[j], array[j + 1]) && swap(array, j, j + 1);
                }
                if (!swapped) {
                    break;
                }
            }
            return array;
        }

something more `Python <http://www.python.org/>`_
