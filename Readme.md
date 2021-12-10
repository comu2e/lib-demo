
```Rust
[dependencies]
// 1.Cargo.tomlで読み込み
// 2.cargo.build
lib_demo = { git = "https://github.com/comu2e/lib-demo" 
// 3.main関数で読み込み
extern crate lib_demo;
fn main() {
    lib_demo::print_random_number();
}
