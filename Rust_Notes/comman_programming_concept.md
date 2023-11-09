## Variables
- let x = 100 <!-- Non mutable variable --> 
- let mut x = 100 <!-- mutable variable -->
- const Y:i32 = 2000; <!-- constant variable -->
-   let x = "shrira"; 
    let x = 100;    <!--Shadowing redeclaring and also we can change the type  -->


## Data type

- Integer
    Length	    Signed	    Unsigned
    8-bit	    i8	        u8
    16-bit	    i16	        u16
    32-bit	    i32	        u32
    64-bit	    i64	        u64
    128-bit	    i128	    u128
    arch	    isize	    usize

- Floating:   f32, f64
- Boolean:  bool
- Charactor:
    let x:char = 'Z'
- Tuple type
        let tup:(i32, char) = (10,'s');
        let (x, y) = tup;
        tup.0 <!--accessing the first tuple i.e i32 -> 10  -->
        tup.1

## Array

- let arr:[i32;4] = [1,2,3,4]; <!--[type; size]--> 
- let arr = [3,432,4,234];


## Control statment

- If Else statment 
    ```rust 
    if number % 4 == 0 {
            ------
        } else if number % 2 == 0 {
            ----
        } else {
            --
        }
    ```
- One line if else
    ```rust
        let number = if condition { 5 } else { 6 };
    ```


## Looping

- loop keyword
    ```rust
        loop{
            statments
        } //loop forever
    

        let x:i32 = loop{
            statment....
            if cond{ break a;} // after break a will be stored to x i.e x = a
        } 
    ```
- while keyword
    ```rust
        while i < 10{
            //statments
        }
    ```

- for keyword
    ```rust
    
    ```