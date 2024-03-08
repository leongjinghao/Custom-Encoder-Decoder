# Custom Encoder Decoder
A custom encoder decoder application developed with Java.

Components:
- **EncoderDecoderInterface**: interface class with encoder and decoder methods specifications.
- **EncoderDecoder**: class implementing the interface class, consisting of fields: referenceTable, referenceTableLen, offsetChar; and the implementation of both encoder and decoder methods.
- **CustomEncoderDecoder**: custom encoder decoder application, demonstrating the use of the EncoderDecoder class.

# Usage
1. Construct _EncoderDecoder_ object
2. Configure reference table using _.setReferenceTable()_
3. Configure offset character using _.setOffsetChar()_
4. Encode plain text using _.encode()_
5. Decode encoded text using _.decode()_

# Sample Output
1. Plain text = "HELLO WORLD", Offset character = 'B'

    ![image](https://github.com/leongjinghao/Custom-Encoder-Decoder/assets/73938217/537910d6-6784-478c-8d0e-01abc3d9967b)

2. Plain text = "HELLO WORLD", Offset character = 'F'

    ![image](https://github.com/leongjinghao/Custom-Encoder-Decoder/assets/73938217/16139d7c-5299-45b9-95e0-8379b8ab8902)
