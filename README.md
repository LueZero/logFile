# LogFile

```C#
var json = new Logger(LogTypeEnume.json);
json.createLog("D:\\", "test", "{}");
Console.WriteLine(json.getLogString());
json.deleteLog("D:\\", "test");
```