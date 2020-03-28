---
title: "Python Basic Lesson 1"
date: 2020-3-28 11:33:00 +0800
img: "https://imgur.com/0Il2wJ0.png"
categories: [Cx0404, Code, Python]
tags: [python]
---
Python Basic Lesson 1


# Variable in python

***
## 1. Assign values to variables

To assign values to variables we use "="

Syntax: < name variable > = < value of variable >

Example:

```python
name = "John"
age = 20
```
## 2. Assign multiple values at once

To assign multiple values at the same time, each value is separated by ","

Syntax: < name1 > , < name2 > = < value1 > , < value2 > 

Syntax: < name1 > , < name2 > = < value >

Example:

```python
name, age = "John", 20
name1, name2 = "John"
```
## 3. Changes in value

To change the value, we will assign the old variable name with a new value

Syntax: < old name > = < new vale >

Example:

```python
name = "John" 
print(name) # => Output: John
name = "Devil"
print(name) # => Output: Devil
```

# Data types in python

***
## 1. Type of string

The string style is written in "" or ''

Example:

```python
string1 = "Full name" 
string2 = 'My name'
```

## 2. Type of number

Type of number include two types: integers and real

Real numbers are separated by "."

Example:

```python
number = 1234 # type of integers
pi = 3.14 # type of float
```
## 3. Case type in python

In python, we can cast types from number to string, or from integer to real

Example:

```python
# convert string to number
string = "10"
string = int(string)
print(type(string)) # => Output: <class 'int'>

# convert number to string
num = 20 
num = str(num)
print(type(num)) # => Output: <class 'str'>

# conver number to float
num1 = 30
num1 = float(num1)
print(type(num1)) # => Output: <class 'float'>
```

## 4. Type of list



## Paragraph

I wandered lonely as a cloud

That floats on high o'er vales and hills,

When all at once I saw a crowd,

A host, of golden daffodils;

Beside the lake, beneath the trees,

Fluttering and dancing in the breeze.

## Block Quote

> This line to shows the Block Quote.

## Tables

|Company|Contact|Country|
|:---|:--|---:|
|Alfreds Futterkiste | Maria Anders | Germany
|Island Trading | Helen Bennett | UK
|Magazzini Alimentari Riuniti | Giovanni Rovelli | Italy

## Link

[http://127.0.0.1:4000](http://127.0.0.1:4000)


## Footnote

Click the hook will locate the footnote[^footnote].


## Image

![Desktop View]({{ "/assets/img/sample/mockup.png" | relative_url }})


## Inline code

This is an example of `Inline Code`.


## Code Snippet

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Languages

#### Console

```console
$ date
Sun Nov  3 15:11:12 CST 2019
```


#### Terminal

```terminal
$ env |grep SHELL
SHELL=/usr/local/bin/bash
PYENV_SHELL=bash
```

#### Ruby

```ruby
def sum_eq_n?(arr, n)
  return true if arr.empty? && n == 0
  arr.product(arr).reject { |a,b| a == b }.any? { |a,b| a + b == n }
end
```

#### Shell

```shell
if [ $? -ne 0 ]; then
    echo "The command was not successful.";
    #do the needful / exit
fi;
```

#### Liquid

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

#### HTML

```html
<div class="sidenav">
  <a href="#contact">Contact</a>
  <button class="dropdown-btn">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-container">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
  <a href="#contact">Search</a>
</div>
```

**Horizontal Scrolling**

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading" id="{{ category_name }}">
      <i class="far fa-folder"></i>
      <p>This is a very long long long long long long long long long long long long long long long long long long long long long line.</p>
      </a>
    </div>
  </div>
</div>
```


## Reverse Footnote

[^footnote]: The footnote source.
