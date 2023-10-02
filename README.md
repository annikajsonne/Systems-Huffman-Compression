# Systems-Huffman-Compression
For COMP 2355 Intro to Systems

Rula Al-Saloom & Annika Sonne Intro to Systems Programming Daniel Stevenson
05.12.2023
Cover Sheet
The following program implements the Huffman Compression algorithm in C. The files included are hcompress.c and linkedlist.c along with their respected header files.
The algorithm will create a linked list of Huffman tree nodes and implements four other methods to make the code functional. The main method takes to arguments, “-e” or “-d”, and a file name. It then calls other functions to create the frequency table, as well as creates the Huffman tree. It then will encode or decode the file depending on the parameter used.
The GenerateFreqTable method reads a text file and counts all the characters in the file. It then returns a table of struct tnodes in an array as the leaf nodes of the Huffman tree. The encode file method encodes the file using the lead nodes given from the previous method. The decode method will decode the compressed file using the root node of the Huffman tree.
