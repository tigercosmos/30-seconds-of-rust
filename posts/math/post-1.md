title: if let
label: if_let
category: math

---

if let is cleaner for this use case and in addition allows various failure options to be specified:

```rust
// The `if let` construct reads: "if `let` destructures `number` into
// `Some(i)`, evaluate the block (`{}`).
if let Some(i) = number {
    println!("Matched {:?}!", i);
}
```
