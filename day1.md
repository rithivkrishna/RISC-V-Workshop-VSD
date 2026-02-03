On Day 1, a cloud-based RISC-V development environment was set up using GitHub Codespaces. The RISC-V GCC toolchain, Spike simulator, and Icarus Verilog were verified, and a sample C program was successfully compiled and executed on both the native system and the RISC-V simulator. A GUI Linux desktop via noVNC was also used for editing and running programs, establishing the foundation for further RISC-V and hardware development.

•Step 1: A new GitHub Codespace was created, the environment was built, and the          RISC-V toolchain setup was verified using the below commands.
         → riscv64-unknown-elf-gcc --version
         → spike --version
         → iverilog -V
          
   
