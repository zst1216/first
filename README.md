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
## 📋 今日待办

### 工作事项
- [x] 完成项目架构图设计
- [x] 评审同事的代码
- [ ] 部署测试环境到服务器
- [ ] 编写 API 接口文档
- [ ] 下午 3 点参加周会

### 个人事务
- [ ] 健身房打卡
- [x] 买菜（鸡蛋、牛奶、面包）
- [ ] 给父母打电话
- [ ] 预约周末体检

### 学习计划
- [x] 阅读《设计模式》第 3 章
- [ ] 完成 Mermaid 教程练习
- [ ] 看一节 React 视频课
- [ ] 整理笔记到 Obsidian
