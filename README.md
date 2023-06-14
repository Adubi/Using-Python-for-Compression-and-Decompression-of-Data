## Using python for DATA COMPRESSION and DECOMPRESSION
This algorithm is designed to compress and decompress text data using a mapping of unique characters to hexadecimal values. It performs the following steps:

The input text is analyzed to determine the number of unique characters and their frequency using the computeText function.

The compression function assigns a hexadecimal value to each unique character and generates a compressed output by replacing each character with its corresponding hexadecimal value.

The decompression function reverses the compression process by mapping the hexadecimal values back to the original characters.

The main function serves as the entry point for the algorithm. It takes user input for the text to be compressed, validates the input, and restricts the input size to 1000 characters. It then performs the compression and decompression operations on the text.

## Usage
To use this algorithm, follow these steps:

Run the Python script.

Enter the text you want to compress when prompted.

The algorithm will display the assigned hexadecimal values for each character, the compressed data, and the decompressed data.

## Limitations
The algorithm is designed for text data and may not be suitable for other types of data.

The maximum input size is limited to 1000 characters to prevent potential memory overload.

The algorithm utilizes a fixed mapping of characters to hexadecimal values, which may not be optimal for all types of data.

## Dependencies
This algorithm uses the Counter class from the collections module.

Please ensure that the required dependencies are installed before running the algorithm.

For more details, refer to the code comments and documentation within the script.

