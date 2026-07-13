# first
first
###以此来记录使用github的第一次
|x|y|
|---|---|
|2|3|
|3|4|

---

#示例代码
```hello
private void OnDataBroadcast(object sender, DataBroadcastEventArgs e)
{
    this.Invoke(() =>
    {
        // 更新温度显示、曲线、状态标签...
        foreach (var msg in e.Messages)
        {
            var color = msg.Message.Contains("终止") ? Color.Yellow : Color.White;
            richTextBoxLog.SelectionColor = color;
            richTextBoxLog.AppendText($"{msg.Time}  {msg.Message}\n");
            richTextBoxLog.ScrollToCaret();
        }
    });
}
```
第一次写.md文档 - [x]
继续练习后续文档 - []
