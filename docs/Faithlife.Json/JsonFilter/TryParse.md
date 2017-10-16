# JsonFilter.TryParse method (1 of 2)

Attempts to create a filter from a string.

```csharp
public static JsonFilter TryParse(string value)
```

| parameter | description |
| --- | --- |
| value | The string. |

## Return Value

The corresponding filter, or null.

## Remarks

A filter string is one or more JSON paths separated by commas. Each JSON path is one or more property names separated by periods. A JSON path prefixed with an exclamation point is excluded rather than included. If no JSON paths are found, this method returns null.

## See Also

* class [JsonFilter](../JsonFilter.md)
* namespace [Faithlife.Json](../../Faithlife.Json.md)

---

# JsonFilter.TryParse method (2 of 2)

Attempts to create a filter from a string.

```csharp
public static JsonFilter TryParse(string value, string rootPath)
```

| parameter | description |
| --- | --- |
| value | The string. |
| rootPath | The root path. |

## Return Value

The corresponding filter, or null.

## Remarks

This overload automatically prefixes each JSON path with the specified root path, if specified.

## See Also

* class [JsonFilter](../JsonFilter.md)
* namespace [Faithlife.Json](../../Faithlife.Json.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Json.dll -->