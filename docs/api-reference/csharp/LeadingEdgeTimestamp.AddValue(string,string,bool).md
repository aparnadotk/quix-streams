#### [QuixStreams.Streaming](index.md 'index')
### [QuixStreams.Streaming.Models](QuixStreams.Streaming.Models.md 'QuixStreams.Streaming.Models').[LeadingEdgeTimestamp](LeadingEdgeTimestamp.md 'QuixStreams.Streaming.Models.LeadingEdgeTimestamp')

## LeadingEdgeTimestamp.AddValue(string, string, bool) Method

Adds a value to the row

```csharp
public QuixStreams.Streaming.Models.LeadingEdgeTimestamp AddValue(string parameter, string value, bool overwrite=false);
```
#### Parameters

<a name='QuixStreams.Streaming.Models.LeadingEdgeTimestamp.AddValue(string,string,bool).parameter'></a>

`parameter` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

Parameter name

<a name='QuixStreams.Streaming.Models.LeadingEdgeTimestamp.AddValue(string,string,bool).value'></a>

`value` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')

Value of the parameter

<a name='QuixStreams.Streaming.Models.LeadingEdgeTimestamp.AddValue(string,string,bool).overwrite'></a>

`overwrite` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')

If set to true, it will overwrite an existing value for the specified parameter if one already exists.  
            If set to false and a value for the specified parameter already exists, the method ignore the new value and just return the current TimeseriesDataRow instance.

#### Returns
[LeadingEdgeTimestamp](LeadingEdgeTimestamp.md 'QuixStreams.Streaming.Models.LeadingEdgeTimestamp')  
Returns the current LeadingEdgeTimestamp instance. This allows for method chaining