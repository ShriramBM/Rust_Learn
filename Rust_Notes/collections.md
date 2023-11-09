## Vector
```rust
    let mut vector:Vec<i32> = Vec::new();
    vector.push(23); 
    vector.push(323); 
    let third: Option<&i32> = vector.get(0);
    let v = vec![1, 2, 3]; //initials
```

## HashMap
```rust
    let mut scores:HashMap<String,i32> = HashMap::new();  
    scores.insert("A".to_string(), 100);
    scores.insert("B".to_string(), 101);
    scores.insert("C".to_string(), 102);
    scores.insert("D".to_string(), 103);

    // Update
    scores.insert("A".to_string(), 1000); 
    let val_ref = scores.entry("A".to_string()).or_insert(0);
    *val_ref+=1;  // update A from 1000 to 1001
    
    //If there leave it otherwise insert new
    scores.entry("C".to_string()).or_insert(9595);


    // Accessing
    scores[&"A".to_string()];
    scores.get(&"A".to_string());
    
    scores.iter()
    .for_each(|x| println!("{}: {}", x.0,x.1));     
```