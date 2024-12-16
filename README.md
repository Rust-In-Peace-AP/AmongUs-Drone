# AmongUs Drone :astronaut:
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_rustinpeace_amongusdrone = { git = "https://github.com/Rust-In-Peace-AP/AmongUs-Drone.git" }
  ```

  Then in the code like this: :rotating_light:

  ```rust
  use ap2024_rustinpeace_amongusdrone;
  ...
  
  fn main(){
  
    let drone = ap2024_rustinpeace_amongusdrone::AmongUsDrone::new(...);
  
  }
```

---

If you wanna look at a different drone come back [here](https://github.com/Rust-In-Peace-AP/sound-effects).
