# Summer Of Code with Datafuse Labs: 2023

This list of ideas is created for the [Google Summer of Code](https://summerofcode.withgoogle.com/) and [Open Source Promotion Plan](https://summer-ospp.ac.cn/) in 2023.

Note that we may update ideas list before the application cycle officially begins.

## Ideas

- [Supporting UDFs in Databend with WebAssembly](#supporting-udfs-in-databend-with-webAssembly)

### Supporting UDFs in Databend with WebAssembly

#### Description

WebAssembly, also known as WASM, is a binary format for representing executable code. It also a perfect candidate for a user-defined functions (UDFs) back-end, thanks to its ease of integration, performance, and popularity. 

By adding support for WASM UDFs to Databend, users will be able to write specific functions in a language they are familiar with.

#### Expected Outcomes

- Write the RFC for supporting webAssembly UDFs
- Implement an MVP that provides the ability to create, delete and load WASM UDFs
- Write relevant tests and docs.

#### Skills Required/Preferred

1. Rust
2. WebAssembly
3. Git

#### Mentors

[Chojan Shang](https://github.com/psiace)

#### Expected Size of Project (175 hour or 350 hour)

350 hour

#### Rating (Easy, Medium or Hard)

Hard
