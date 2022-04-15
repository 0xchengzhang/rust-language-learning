

[rust权威指南](https://kaisery.github.io/trpl-zh-cn/ch03-05-control-flow.html)

[rust版本控制](https://rustwiki.org/zh-CN/edition-guide/rust-2018/rustup-for-managing-rust-versions.html)

```
/**
* 比较耗费时间，少用
**/
cargo build

/**
* 为发布而构建，编译正式版本，比较耗时，生成的target下会有release文件
**/
cargo build --release

/**
* 快速编译
**/
cargo check

/**
* 编译并且直接运行
**/
cargo run

/**
*
**/
cargo update

/**
* 清楚target文件
**/
cargo clean
```
