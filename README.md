# Morse Code and Dictionary BST

A generic binary search tree in Java, used to build a Morse code translator and a searchable dictionary.

## Binary search tree (`BSTree.java`)

- Generic `BSTree<T extends Comparable<T>>` with add, contains, and remove
- Pre-order, in-order, and post-order traversals
- Height, number of levels, node count, leaf count, internal node count, and full-tree check
- Builds a balanced tree from a sorted list by recursively inserting the middle element
- Prefix lookup (`getGroup`) using a custom `Comparator`

## Morse code translator (`MorseTree.java`)

- Builds a binary tree from a Morse code table where a dot goes left and a dash goes right
- Translates Morse code input into letters, with a Swing GUI

## Dictionary (`Dictionary.java`)

- Loads about 127,000 words into a balanced BST
- Swing GUI that shows every word starting with the prefix you type

## Built with

Java, Swing
