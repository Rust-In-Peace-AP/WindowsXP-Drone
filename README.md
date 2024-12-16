# WindowsXP Drone :floppy_disk:
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_rustinpeace_windowsXPdrone = { git = "https://github.com/Rust-In-Peace-AP/WindowsXP-Drone.git" }
  ```

  Then in the code like this: :laptop. :window:

  ```rust
  use ap2024_rustinpeace_windowsXPdrone;
  ...
  
  fn main(){
  
    let drone = ap2024_rustinpeace_windowsXPdrone::WindowsXPDrone::new(...);
  
  }
  
  