# UFC Fighter Centrality App 👊💥
This app made in Rust calculates the centrality using the Petgraph library (https://crates.io/crates/petgraph) between UFC fighters depending on the fights they had.


## Run the app
```
$ cargo run
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/ufc-centrality`
The closeness centrality of Dustin Poirier is 0.33
Dustin Poirier has a centrality of 0.33, implying they had less fights compared to Conor McGregor but more than Khabib Nurmagomedov and Jose Aldo.
-----------------
The closeness centrality of Khabib Nurmagomedov is 0.50
Khabib Nurmagomedov has the highest centrality of 0.50 as they have fought with the least number of fighters.
-----------------
The closeness centrality of Jose Aldo is 0.50
Jose Aldo has the highest centrality of 0.50 as they have fought with the least number of fighters.
-----------------
The closeness centrality of Conor McGregor is 0.25
Conor McGregor has the lowest centrality because he has fought with all other fighters in the network. In this context, a lower centrality value means a higher number of fights.
-----------------
The closeness centrality of Nate Diaz is 0.33
Nate Diaz has a centrality of 0.33, implying they had less fights compared to Conor McGregor but more than Khabib Nurmagomedov and Jose Aldo.
-----------------
```
