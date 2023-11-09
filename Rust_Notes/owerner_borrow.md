## Owerner and Borrower

- Owner
    ```rust
        let x = String.from("helo");
        let y = x; //now y is the owener
        // x is dead i.e goes out scope
    ```
- Borrow
    ```rust
        let x = String.from("helo");
        let y = &x; //now y is a Borrower but x is still the owner
        /*
         You can have only once mut Borrower but mutiple read only borrower can be present
         */ 
    ```

- Once the variable goes out of the scope it is understood that, it is Dead 