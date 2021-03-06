# Summary

* [总览](README.md)
* [帮助说明](help.md)
* [Serde 数据模型](data-model.md)
* [使用 derive 宏](derive.md)
* [属性](attributes.md)
    * [container 属性](container-attrs.md)
    * [variant 属性](variant-attrs.md)
    * [field 属性](field-attrs.md)
* [自定义序列化](custom-serialization.md)
    * [实现 Serialize](impl-serialize.md)
    * [实现 Deserialize](impl-deserialize.md)
    * [单元测试](unit-testing.md)
* [手写数据格式](data-format.md)
    * [惯例](conventions.md)
    * [错误处理](error-handling.md)
    * [实现 Serializer](impl-serializer.md)
    * [实现 Deserializer](impl-deserializer.md)
* [Deserializer lifetimes](lifetimes.md)
* [例子](examples.md)
    * [JSON 与结构体/枚举体](json.md)
    * [用于枚举体](enum-representations.md)
    * [给字段设置默认值](attr-default.md)
    * [结构体展平](attr-flatten.md)
    * [手写泛型 bounds](attr-bound.md)
    * [Deserialize for custom map type](deserialize-map.md)
    * [Array of values without buffering](stream-array.md)
    * [Serialize enum as number](enum-number.md)
    * [Serialize fields as camelCase](attr-rename.md)
    * [Skip serializing field](attr-skip-serializing.md)
    * [Derive for remote crate](remote-derive.md)
    * [Manually deserialize struct](deserialize-struct.md)
    * [Discarding data](ignored-any.md)
    * [Transcode into another format](transcode.md)
    * [Either string or struct](string-or-struct.md)
    * [Convert error types](convert-error.md)
    * [Custom date format](custom-date-format.md)
* [No-std support](no-std.md)
* [Feature flags](feature-flags.md)
