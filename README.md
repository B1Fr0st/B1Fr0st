Wilted beyond

```rust
use basev2::prelude::*;

#[basev2::main]
fn main() {
  basev2:opinionated_build("deadlock.exe")
    .with_logic(esp)
    .with_logic(aimbot)
    .with_logic(scripting)
    .with_logic(exploits)
    .with_thread(players)
    .with_thread(cache)
    .run()
}

```
