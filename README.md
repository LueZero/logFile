# LogFile

```C#
var json = new Log(LogTypeEnume.json);
json.CreateLogFile("D:\\", "test", "{}");
Console.WriteLine(json.GetLogFile());
json.DeleteLogFile("D:\\", "test");
```