# Soundex
A Mendix module that implements the Soundex algorithm.

Soundex is used to try to match similar sounding or mispelled words. It generates an encoded version of a word so words like Knuth and Kant, Gauss and Ghosh, Rogers and Rodgers generate the same code and will be a match.

Donald Knuth describes the algorithm in chapter 6 of Volume 3 of the Art of Computer Programming, and if you are interested in more details it is well worth reading this.

## Usage

### Soundex
* Input - A String with the name to Soundex encode.

Returns a String with the encoded Soundex value

## Dependencies
* none

## Contributing
The source code, examples, and unit tests can be found on [https://github.com/robertprice/Soundex](https://github.com/robertprice/Soundex).

## Author
Robert Price - [Deck Chair Digital Ltd](https://deckchair.digital/)

## See Also
The Art Of Computer Programming - Volume 3, by Donald Knuth

## License
Soundex is licensed under the Apache License, Version 2.0.  
http://www.apache.org/licenses/LICENSE-2.0