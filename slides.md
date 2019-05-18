layout: true

.signature[@algogrit]

---

class: center, middle

# Internals of Go Maps

Gaurav Agarwal

---

class: center, middle

![Me](assets/images/me.png)

Software Engineer & Product Developer

Principal Consultant & Founder @ https://agarwalconsulting.io

ex-Tarka Labs, ex-BrowserStack, ex-ThoughtWorks

---

# Agenda

- What is a map?
- Internals
- Maps in action
- Go's implementation details
- Concurrency?
- Peeking into the standard library

---

class: center, middle

# 🙋‍♂️

## Survey!

# 🙋

---

class: center, middle

## What is a map?

![Map](assets/images/map-icon.svg)

---

### aka

Dictionary, Hash, HashMap, Hashtable, ...

---
class: center, middle

```golang
m := make(map[string]Vertex)
```

or

```golang
m := map[string]Vertex{}
```

---
class: center, middle

### Maps in action

![Gopher Typing](/assets/images/gopher-typing.gif)

---
class: center, middle

## Internals

---

### Internals

.left-column[
Buckets
]

.right-column.white[
  ![HashMapInternals](/assets/images/hash-map-1.svg)
]

---

### Internals

.left-column[
Hashing function
]

.right-column.white[
  ![HashMapInternals](/assets/images/hash-map-1.svg)
]

---

### Internals

.left-column[
#### Collision Resolution

- Chaining
- Open addressing
]

.right-column.white[
  ![HashMapInternals](/assets/images/hash-map-1.svg)
]

---

### Internals

.left-column[
Rehashing
]

.right-column.white[
  ![HashMapInternals](/assets/images/hash-map-1.svg)
]

---
class: center, middle

## Go's implementation details

---
class: center, middle

## Is it concurrent?

---
class: center, middle

## Implementing our own concurrent implementation

---
class: center, middle

## Peeking into the standard library!

---

class: center, middle

![Mic Drop](assets/images/gopher-mic-drop-small.png)

Code
https://github.com/Chennai-Golang/101-workshop/tree/master/examples/maps

Slides
https://internals-of-go-maps.slides.algogrit.com
