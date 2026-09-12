# Day Care Intake & Report Tool

一个纯前端、单文件的手机端病人快速记录工具，供 day care 护理人员在接待病人时快速点选记录病史，并按手术类型自动生成 PRE / POST 护理报告文字。

A single-file, offline-friendly mobile tool for day care nursing staff to quickly record patient intake information via tap-based selection, and auto-generate PRE/POST surgical nursing report text by procedure type.

## 功能 Features

- 点选式记录（最后进食、用药、病史、手术史、过敏史、假牙、财物保管、病房饮食、同意与宣教），减少手动打字
- 支持 5 种手术类型模板：PHACO 白内障手术 / INJECTION 眼内注射 / PTERYGIUM 翼状胬肉切除术 / COLONOSCOPY 肠镜检查 / BCF 动静脉瘘造瘘术
- 根据已选资料自动生成对应的 PRE / POST 报告文字，缺项会标注 `[PENDING]` 提醒补充
- 报告文本框可直接手动编辑微调
- 一键复制（自动把换行转成空格，方便贴入不支持换行的病历系统）
- 纯前端，无需联网、无服务器、不上传任何数据

## 使用方法 Usage

1. 打开页面（建议通过 GitHub Pages 链接，而不是本地文件，以避免 iOS 浏览器对本地文件的访问限制）
2. 依次点选各项资料
3. 选择手术类型，补充左右眼/麻醉方式/医生姓名/复诊安排等
4. 复制 PRE / POST 报告文字，粘贴到你们的病历系统
5. 换下一位病人前点击「清空重填」

建议在手机浏览器中打开后，使用「添加到主屏幕」，可像 App 一样一键启动。

## 隐私说明 Privacy

本工具所有数据只保存在当前页面的浏览器内存中，不会上传、存储或发送到任何服务器；关闭或刷新页面后数据即清空。

## 技术 Tech

纯 HTML + CSS + 原生 JavaScript，无第三方依赖，可离线运行。
