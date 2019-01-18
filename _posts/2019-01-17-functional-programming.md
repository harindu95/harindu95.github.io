---
title: Functional Programming 
layout: post
date: Thu Jan 17 19:53:20 MST 2019
categories: functional programming update
comments: true
---

I am sure many of you have heard about functional programming before. Many articles on web seemed to focus on the following aspects of functional programming.

1. Higher Order functions
2. Immutable data
3. Pure functions or programming without side effects

But I think they forget the most important aspect of functional programming. That is 'functions'. Functions as mathematical functions not procedures.

## What is a mathematical function?

Mathematical function is a relation between two sets such as X and Y. Each element of X is associated with only one element of Y.

## What does it have to do with programming?

The beauty of mathematical functions is that they are declarative. They only define the relationship and don't care how you achieve that. That is they are 'declarative'.

In my opinion, this is something we should apply for programming. 

Lets give you an example.

* Concatenate a list of strings.

1. Procedural approach

```python

  words = [ 'abc', 'bcd', 'efg']
  result = ''
  for word in words:
      result += word
  
```
2. Functional approach

```python

  words = [ 'abc', 'bcd', 'efg']
  result = ''.join(words)

```

This is a simple example and doesn't offer anything of value.
But I think programming should move towards being more declarative. 

