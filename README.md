# Hitch-Hikers-Guide-To-Data-Compression
Following My Journey From Beginner to Pro for Data Compression.

## Intro 
The journey for understanding data compression is not one that is fast and takes a lot to become a master in. This will follow me through my journey of learning data compression. Hopefully this helps others in the future!

## Start 

### Run-length Encoding
To start to understand how data compression works I searched the internet to find one that clicks. For me the simplest and most straightforward starting poing was for `Run-length Encoding`. RLE(Run-length Encoding) is a form of lossless data compression that involves finding consecutive data elements. 

An example such as the one below is not something that would be seen in a text document but would be seen in a black and white image.

<ins> Example </ins> 
```
WWWWWWWWWWWBWWWWWWWWWWWWBBBWWWWWWWWWWWWWWWWWWWWWWWWBWWWWWWWWWWWWWW
```

<ins> Converted </ins>
```
12W1B12W3B24W1B14W
```

(Source: https://en.wikipedia.org/wiki/Run-length_encoding)

As can be seen from above the original 67 characters is now only 18 characters which is a dramtic difference between the two of them. Now even though this is shown in ASCII as mentioned in the Wiki Article it does not matter because the principle is still the same for both. There is also other ways this data can be interpreted and compressed to handle situations with less repetition. More of this can be read about in the above wiki article that was linked. The last part that I will cover is that with some of these you have to overcome the data and escape symbols from the run lengths allowing them to be handled independently such as these two outputs: `"WWBWWBBWWBWW"` & `(12,12,3,24,14)`. 

### Lempel–Ziv–Welch
(Source: https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Welch)

### Huffman coding
(Source: https://en.wikipedia.org/wiki/Huffman_coding)
