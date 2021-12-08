# Read30 Summary

![hash-tables](https://static.javatpoint.com/ds/images/hash-table.png)

Hash table is one of the most important data structures that uses a special function known as a hash function that maps a given value with a key to access the elements faster. A Hash table is a data structure that stores some information, and the information has basically two main components, i.e., key and value. The hash table can be implemented with the help of an associative array. The efficiency of mapping depends upon the efficiency of the hash function used for mapping.

Hash tables are made up of two parts:

* Object: An object with the table where the data is stored. The array holds all the key-value entries in the table. The size of the array should be set according to the amount of data expected.
* Hash function (or mapping function): This function determines the index of our key-value pair. It should be a one-way function and produce the a different hash for each key.

Hash tables provide access to elements in constant time, so they are highly recommended for algorithms that prioritize search and data retrieval operations. Hashing is ideal for large amounts of data, as they take a constant amount of time to perform insertion, deletion, and search.

![hash-function](https://res.cloudinary.com/practicaldev/image/fetch/s--7x2naWJ6--/c_imagga_scale,f_auto,fl_progressive,h_1080,q_auto,w_1080/https://cl.ly/dcc906e5110a/Image%25202019-05-12%2520at%252011.38.16%2520PM.png)

A hash function is a method or function that takes an item’s key as an input, assigns a specific index to that key and returns the index whenever the key is looked up. This operation usually returns the same hash for a given key. A good hash function should be efficient to compute and uniformly distribute keys. Hash functions help to limit the range of the keys to the boundaries of the array, so we need a function that converts a large key into a smaller key. This is the job of the hash function.

![buckets](https://databricks.com/wp-content/uploads/2018/12/hash-buckets.jpg)

```
Bucket 0: [{Renton: 98055} --> {Capital Hill: 98102} --> {Greenwood: 98103} --> {Greenlake: 98103} --> {Pioneer Square: 98104} --> {University District: 98105} --> {Columbia City: 98118}]
Bucket 1: [{Bellevue: 98005} --> {Seattle: 98101}]
Bucket 2: [{Mercer Island: 98040} --> {Alki Beach: 98116} --> {Northgate: 98125}]
Bucket 3: [{Downtown: 98101} --> {Laurelhurst: 98105} --> {Bainbridge Island: 98110} --> {Magnolia: 98199}]
Bucket 4: [{Kirkland: 98033} --> {Lynnwood: 98037} --> {Ballard: 98107} --> {Queen Anne: 98109} --> {West Seattle: 98116}]
Bucket 5: [{International District: 98104} --> {Mount Baker:98144}]
Bucket 6: [{Redmond: 98052} --> {Freemont: 98103} --> {South Lake Union: 98109} --> {Madrona: 98110} --> {Belltown: 98121}]
```

A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs. Hash Maps can have any number of buckets. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

![collisions](https://miro.medium.com/max/1313/1*wHiuDrmhLsyJbgGWCEBBcQ.png)

```
Bucket 0: []
Bucket 1: []
Bucket 2: []
Bucket 3: []
Bucket 4: []
Bucket 5: []
Bucket 6: []
Bucket 7: []
Bucket 8: []
Bucket 9: []
Bucket 10: []
Bucket 11: []
Bucket 12: [{South Lake Union: 98109}]
Bucket 13: [{Madrona: 98110}]
Bucket 14: []
Bucket 15: []
Bucket 16: [{Magnolia:98199}]
Bucket 17: []
Bucket 18: []
Bucket 19: [{Greenlake:98103}]
Bucket 20: [{Redmond:98052}]
Bucket 21: []
Bucket 22: []
Bucket 23: []
Bucket 24: [{Kirkland:98033}]
Bucket 25: []
Bucket 26: []
Bucket 27: []
Bucket 28: [{Bellevue:98005}]
Bucket 29: [{Seattle:98101}]
Bucket 30: []
Bucket 31: []
Bucket 32: []
Bucket 33: []
Bucket 34: []
Bucket 35: []
Bucket 36: [{Renton:98055}]
Bucket 37: [{Queen Anne:98109}]
Bucket 38: [{Capital Hill:98102}]
Bucket 39: []
Bucket 40: [{Freemont:98103}]
Bucket 41: []
Bucket 42: []
Bucket 43: []
Bucket 44: []
Bucket 45: []
Bucket 46: []
Bucket 47: [{Greenwood:98103}  --> {Belltown:98121}]
Bucket 48: []
Bucket 49: [{Northgate:98125}]
Bucket 50: [{Bainbridge Island:98110}]
Bucket 51: []
Bucket 52: []
Bucket 53: [{Mercer Island:98040}]
Bucket 54: []
Bucket 55: []
Bucket 56: []
Bucket 57: []
Bucket 58: [{Mount Baker:98144}]
Bucket 59: []
Bucket 60: [{International District:98104}]
Bucket 61: []
Bucket 62: []
Bucket 63: []
Bucket 64: []
Bucket 65: [{Columbia City:98118}]
Bucket 66: [{Lynnwood:98037}]
Bucket 67: []
Bucket 68: []
Bucket 69: []
Bucket 70: []
Bucket 71: []
Bucket 72: [{Downtown:98101}]
Bucket 73: []
Bucket 74: []
Bucket 75: []
Bucket 76: []
Bucket 77: []
Bucket 78: []
Bucket 79: [{University District:98105}]
Bucket 80: []
Bucket 81: []
Bucket 82: []
Bucket 83: []
Bucket 84: [{West Seattle:98116}]
Bucket 85: []
Bucket 86: []
Bucket 87: []
Bucket 88: []
Bucket 89: []
Bucket 90: [{Laurelhurst:98105}]
Bucket 91: []
Bucket 92: [{Pioneer Square: 98104} --> {Alki Beach:98116}]
Bucket 93: []
Bucket 94: []
Bucket 95: []
Bucket 96: [{Ballard:98107}]
Bucket 97: []
Bucket 98: []
```

A collision occurs when more than one key hashes to the same index in an array. As mentioned earlier, a “perfect hash” will never have any collisions. To put this into perspective, the worst possible hash is one that hashes every single key to the same exact index of an array. The more keys you have hashed to a specific index, the more key/value pair combos you can potentially have. Collisions are solved by changing the initial state of the buckets. Instead of starting them all as null we can initialize a LinkedList in each one! Now if two keys resolve to the same index in the array then their key/value pairs can be stored as a node in a linked list. Each index in the array is called a “bucket” because it can store multiple key/value pairs.