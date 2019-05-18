# Outline

- Introduction
  - Its not Google maps
  - Python: dictionary, Ruby: hash, Java: HashMap
- What is a hashmap exactly?
  - Internals
    - Buckets
    - Hashing function
    - Collision resolution
    - Rehashing vs linkedList/BinaryTree
- Go's implementation details:
  - https://github.com/golang/go/blob/master/src/runtime/map.go
  - https://www.ardanlabs.com/blog/2013/12/macro-view-of-map-internals-in-go.html
- Can Go's map work concurrently?
- Introducing syncmap/map
