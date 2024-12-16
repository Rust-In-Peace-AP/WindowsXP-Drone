# WindowsXP Drone :floppy_disk:
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_rustinpeace_windowsxpdrone = { git = "https://github.com/Rust-In-Peace-AP/WindowsXP-Drone.git" }
  ```

  Then in the code like this: :window:

  ```rust
  use ap2024_rustinpeace_windowsxpdrone;
  ...
  
  fn main(){
  
    let drone = ap2024_rustinpeace_windowsxpdrone::WindowsXPDrone::new(...);
  
  }
```

---

If you wanna look at a different drone come back [here](https://github.com/Rust-In-Peace-AP/sound-effects).  
