# Data-Compression-Huffman-Algorithm
Using Huffman Encoding to compress data

<!---[alt text](https://media.giphy.com/media/26BoChCaUUgVhCKHu/giphy.gif)
![alt text](https://media.giphy.com/media/l0MYuZRGumMHcj2tG/giphy.gif)--->
![alt text](https://media.giphy.com/media/2FayYXU90QS9MmAIo/giphy.gif)


Huffman encoding is a lossless data compression algorithm and we will talk a bit about variable and fixed length encoding, prefix rules and construction of Huffman Tree.

## Fixed length encoding
Consider my name, ASHUTOSH, if I store this then every character uses a sequence of 8 bits (0s and 1s)

> Number_of_characters = 8

> Size = 8 bytes or  8 * 8 = 64 bits

This is fixed length encoding as every character uses the same number of fixed bits of storage

This might not seems like much but it's just one word, when we use a large text file then the storage space can dry up pretty quickly, how do we fix this?

## Variable length encoding
The idea behind variable length encoding exploits the frequency of characters to design an algorithm that can represent the same piece of text using lesser number of bits. This means that we have a solution, but we dont.

The problem is decoding the encoded text

...More on this soon
