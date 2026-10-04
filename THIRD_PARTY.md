# 第三方说明

wcdb_keys.py 的配置对象解析方法改编自 [wechatauto-replica](https://github.com/fanyuantaier/wechatauto-replica)，提交 91dc0e1a601013b759b261061d8f7642f736af90，Apache License 2.0。完整许可证见 LICENSE-wechatauto.txt。

修改：仅保留选定账号的只读读取参数发现和验证；移除自动切换账号、持久保存密钥、发送消息、UI 控制等能力；增加进度回调。源项目其余模块没有执行或随本软件分发。

统计采用 jieba、SnowNLP、wordcloud、Matplotlib；读取采用 cryptography、psutil、zstandard。具体版本见 requirements.txt；打包附带各安装包原始许可证。SnowNLP 情感分数是中文通用模型的估计，不是人工标注或心理评估。
