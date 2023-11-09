
## Rust function

 - Functions 
    ```rust
    fn main() {
        print_labeled_measurement(5, 'h');
    }

    fn print_labeled_measurement(value: i32, unit_label: char) {
        println!("The measurement is: {value}{unit_label}");
    }
    ```
- scope Expression
    ```rust
            let x =  {
                let mut a = 3;
                a+=1;
                a
            }; 
    ```

- Return Statment
    ```rust
        fn five() -> i32 {
            5
        }
    ```