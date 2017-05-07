Based on tutorial from [https://bheisler.github.io/post/writing-raytracer-in-rust-part-1/](https://bheisler.github.io/post/writing-raytracer-in-rust-part-1/)

## Get Started:
Make sure [cargo][cargo] is installed.
```
cd raytracer/app
cargo run scenes/test.yml out.png
```

### Example Images
![Example One][ex1]
![Example Two][ex2]
![Example Three][ex3]


[cargo]: https://rustup.rs/
[ex1]: ./app/out.png
[ex2]: ./app/out2.png
[ex3]: ./app/room.png

## Release mode

In release mode the raytracer runs a lot faster.

To build for release mode:
```
cd app; cargo build --release
```

To run: 
```
cd app; ./target/release/raytracer-app scenes/test.yml out.png
```


