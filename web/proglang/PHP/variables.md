# VARIABLES & DATA TYPES

## Table of Content

## Type System

### Atomic types

- Built-in types
  - *Scalar types*
    - bool
    - int
    - float
    - string  
  - array
  - object
  - resource
  - never
  - void
  - *Relative class types*
  - *Singleton types*: only allow 1 value
    - false
    - true  
  - Unit types: null
- *User-defined types*
  - interfaces
  - classes
  - enumerations  
- callable type

### Composite types

PHP allows types to be combined in the following ways
- Intersection of class-types (interfaces & class names)
- Union of types

### Type alias

PHP supports 2 type aliases:
- mixed
- iterable

PHP does not support user-defined type aliases.

### Strict mode

```
  <?php declare(strict_types=1);
    // Code here
  ?>
```

## Array
An array in PHP is actually an **ordered map**, which associates **values** to **keys**.

There are 3 basic ways to implement the array: 
1. Indexed array
2. Associative array
3. Multidimensional array.

The key can either be an *int* or a *string*.

The value can be of any type.

> [!WARNING]
> The following 

# VARIABLE SCOPE

### Union types

## Type aliases
