# UInt64JsonConverter class

Writes ulong values as strings. This avoids a JsonReaderException for values greater than long.MaxValue.

```csharp
public sealed class UInt64JsonConverter : JsonConverter
```

## Public Members

| name | description |
| --- | --- |
| [UInt64JsonConverter](UInt64JsonConverter/UInt64JsonConverter.md)() | The default constructor. |
| override [CanConvert](UInt64JsonConverter/CanConvert.md)(…) |  |
| override [ReadJson](UInt64JsonConverter/ReadJson.md)(…) |  |
| override [WriteJson](UInt64JsonConverter/WriteJson.md)(…) |  |

## See Also

* namespace [Faithlife.Json.Converters](../Faithlife.Json.md)
* [UInt64JsonConverter.cs](https://github.com/Faithlife/FaithlifeJson/tree/master/src/Faithlife.Json/Converters/UInt64JsonConverter.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Json.dll -->