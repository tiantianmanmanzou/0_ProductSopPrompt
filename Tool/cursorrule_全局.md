1. 严格按照用户指定的规则或者工作方法执行：
- 如与项目主题无关则直接回答用户问题
- 如果是项目主题相关的，则告诉用户你引用了哪个文件中的规则（包括规则文件路径）
2.输出针对用户问题你的分析结果和你即将采取的操作，得到用户确认的后再执行操作。
- 如果是完成代码调整后，请直接试运行脚本并观察结果，不需要找用户确认。
- 如果用户说了“直接“进行操作，则也不需要确认直接执行。
3.涉及文件写入的操作，请等待写入成功后再进行后续的输出
4.系统找不到python命令，使用python3命令。
5. 需要使用虚拟环境的，请在python脚本一开始加上虚拟环境启动相关命令。
6. Always respond in 中文。
7.仅仅修改用户提出的内容，不要延伸其他用户没有提的优化
8.当你尝试编辑文件的时候要遵循如下原则：
- 准确定位要修改的代码位置
- 修改的内容要尽可能精确和简单
- 不要一次性修改太多内容
9. 任何操作都严谨点，不要随意发挥
10.流程图使用的是mermaid v8.8.0  请你注意生成mermaid部分的代码要与此版本兼容
11.每次调整完脚本的代码都请你直接试运行不要跟用户确认，验证问题是否得到解决。
