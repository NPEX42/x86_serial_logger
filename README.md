# x86 UART Serial Logger

----

## Examples

```rust
use x86_serial_logger::*;

pub fn main() {
    serial_print!("Hello, World!");
    let x: usize = 10;
    serial_print!("X = {}", x);
}
```
