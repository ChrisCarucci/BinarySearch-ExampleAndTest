<h1> Binary Search and Test </h1>

Most basic Binary Search with an accompanying test to measure efficieny vs Linear Search.

Creates a random number using:

    for (let i = 0 ; i < 30000; i++) {
        valuesToSearch.push(Math.floor(Math.random() * 2 * n) - n);
    }

Fills an Array with 1,000,000 numbers. 

    n = 1000000;
    arr = [];
    for (let i = 0 ; i < n ; i ++) {
        arr.push(i);
    }