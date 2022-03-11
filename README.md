# LogFile

```C#
var json = new Logger<JObject>(LogTypeEnum.Json);

json.CreateLogFile("D:\\", "test", "{}");

Console.WriteLine(json.GetLogFile());

json.DeleteLogFile("D:\\", "test");
```