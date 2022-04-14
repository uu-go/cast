# Cast
Go项目的一个轻量级类型转换包

## 使用条件

  需要Go的版本 > `v1.11` 或更高的版本。

## 安装使用

要安装这个包，请在您的项目路径中运行以下命令；
```bash
go get github.com/uu-go/cast
```

## 使用示例

```go
val, err := cast.FromString("666", "int32")
// `val` type: int32
// `val` value: 666
```

```go
val, err := cast.FromString("1", cast.Bool)
// `val` type: bool
// `val` value: true
```

## 支持的类型

* Int (Int8 .. Int64)
* Uint (Uint8 .. Uint64)
* Float32 and Float64
* Bool
* String

## 许可

[MIT License](https://github.com/uu-go/cast/blob/main/LICENSE)