# Doujar Privacy Policy

Last updated: November 17, 2026

## English

### Scope and purpose

Doujar is a Chrome extension that helps you understand webpages using the native Doubao website in Chrome's side panel. This policy describes how the extension handles data for page summaries, selected-text questions, source references, and guided reading. Doujar uses your existing Doubao login and does not require an API key.

### Data the extension handles

- **Website content and page information:** rendered webpage text, selected text, page titles, URLs, capture times, and source markers. When the sidebar opens or its associated page changes, loads, or is refreshed, Doujar extracts relevant page content locally. It does not scan every page's body in the background or access Chrome's browsing history database. URLs can include query parameters and other sensitive information.
- **Questions and conversations:** questions you submit, guided reading answers you submit for feedback, and related native Doubao messages and replies. Doujar reads relevant native replies locally to display reading exercises and feedback. Messages and replies remain visible in the native conversation.
- **Preferences:** interface language, sidebar scope, selection toolbar settings, custom actions, and page or domain exclusions. These preferences are saved locally without account synchronization by Doujar.

The selection toolbar handles selections locally on ordinary HTTP and HTTPS webpages. Its password-field exclusion does not guarantee that other page text or messages contain no sensitive information. Doujar does not automatically detect or redact sensitive content.

### When data reaches Doubao

Doujar submits webpage text, selected text, or reading answers as native Doubao chat messages when you explicitly invoke an AI action or send a message. Submitting a guided reading answer can include its question, earlier answers and feedback for that question, and the source snapshot used for the exercise. Multiple-choice selections and their local grading results are not submitted again to Doubao.

Before you submit a chat message, Doujar also places the current page's title and URL, and recent source URLs and source markers, inside the embedded Doubao page to display context and recognize source references. Scripts running on that page may read this metadata. You do not need to send a chat message for this metadata to become available to the embedded page.

The embedded Doubao website loads when the sidebar opens. Its own network requests, login, cookies, data retention, and use of submitted messages are governed by Doubao's policies and your account settings. This policy does not promise that Doubao will delete, retain, or use data in any particular way.

### Local storage and retention

Doujar keeps up to 30 recent page snapshots and source mappings, plus pending selected-text requests, in Chrome's extension session storage. This storage is cleared when the browser session ends or the extension is reloaded, updated, disabled, or removed. Preferences remain in local extension storage until changed or removed.

Reading progress, multiple-choice answers, and unfinished guided reading answers remain in the current sidebar instance's memory. Minimizing a reading view preserves that state; disposing of or reloading the sidebar instance does not restore it. Doujar does not copy chats or drafts into persistent extension storage for restoration. A fresh sidebar instance clears the native input's existing unsent draft once; reconnecting or reloading the AI page within that instance does not trigger another clear.

### Data use and developer access

Doujar has no developer-operated backend or analytics. The extension does not send webpage content, conversations, or local settings to the developer. It does not sell user data or use it for advertising, profiling, creditworthiness, lending, or purposes unrelated to webpage reading assistance.

Doujar does not extract login passwords or authentication cookies, request device geolocation, or keep click, mouse-movement, or keystroke logs. It uses selection and input events to provide its immediate interface interactions. The Copy action writes selected content to your local clipboard.

Developer-enabled diagnostics, when used, stay in sidebar memory and may include task identifiers, reading counters, and a reply excerpt of up to 300 characters. They are not automatically uploaded or persisted. Copying diagnostics requires an explicit action and writes them to the local clipboard.

Data obtained through Chrome APIs is used only for the disclosed reading features, in accordance with the Chrome Web Store User Data Policy and its Limited Use requirements. Doujar requests sidePanel, storage, scripting, and HTTP/HTTPS website access; it does not request tabs or declarativeNetRequestWithHostAccess.

### Your controls

You can disable the selection toolbar globally or for a page or domain, pause it for 24 hours, change extension settings, and close or remove the extension. Removing the extension deletes its local preferences and session storage. It does not retract messages already sent to Doubao; manage those messages through Doubao's own controls.

### This policy page and contact

This page is hosted on GitHub Pages. GitHub's own privacy statement applies to visits to this website. The page includes no added analytics or advertising scripts.

For privacy questions, contact the developer through [raywill/doujar Issues](https://github.com/raywill/doujar/issues). Updates to extension data practices will be reflected in this policy and the Chrome Web Store disclosures.

## 简体中文

### 适用范围与用途

Doujar 是一款 Chrome 扩展，通过侧栏中的豆包原生网页帮助你理解网页内容。本政策说明网页总结、选中文字提问、原文引用和阅读练习涉及的数据处理。Doujar 复用你的豆包登录，无需 API Key。

### 扩展处理哪些数据

- **网页内容与页面信息：** 渲染后的正文、选中文字、标题、URL、读取时间和原文定位标记。打开侧栏，以及侧栏关联的网页切换、加载或刷新时，扩展会在本地提取相关页面内容。扩展不在后台扫描所有网页的正文，也不读取 Chrome 的历史记录数据库。URL 可能包含查询参数等敏感信息。
- **提问与对话：** 你提交的问题、明确提交给 AI 获取反馈的深读回答，以及相关的豆包原生消息和回复。扩展在本地读取相关原生回复，用于展示阅读题目和反馈；消息与回复仍正常显示在豆包原生对话中。
- **偏好设置：** 界面语言、侧栏范围、选区工具条设置、自定义动作，以及禁用工具条的页面或域名。这些设置保存在本地，Doujar 不通过账号同步。

选区浮动条在普通 HTTP/HTTPS 网页中本地处理选区。它不会在密码框中启用，但网页正文或消息仍可能包含敏感信息；扩展不会自动识别或脱敏这些内容。

### 何时会将数据交给豆包

你明确执行 AI 操作或发送消息时，扩展才会把正文、选中文字或阅读回答作为豆包原生聊天消息提交。提交深读回答时，可能一并发送本题、同题此前的作答及反馈，以及本次练习使用的原文快照。速读选择题的选项选择和本地判题结果不会再次发送给豆包。

**在发送聊天消息之前，扩展也会把当前页面的标题与 URL，以及近期原文的 URL 和定位标记放入嵌入的豆包页面，用于显示上下文和识别原文引用。该页面的脚本可能读取这些元信息；即使你尚未发送消息，这些元信息也可能已对嵌入页面可见。**

侧栏打开时会加载豆包原生网页。其自身的网络请求、登录、Cookie、数据保留和已发送消息的使用，适用豆包的政策及你的账号设置。本政策不替豆包承诺具体的数据删除、保留或使用方式。

### 本地存储与保留时间

扩展使用 Chrome 扩展会话存储，暂存最近最多 30 份网页快照和原文映射，以及待处理的选区请求。浏览器会话结束，或扩展被重新加载、更新、停用或卸载时，该会话存储会被清除。偏好设置保存在扩展本地存储中，直到被修改或移除。

阅读进度、选择题作答和未提交的深读回答保留在当前侧栏实例的内存中。收起阅读视图会保留这些状态；侧栏实例被回收或重新加载后不恢复。扩展不会把聊天和草稿复制到持久存储用于恢复。新侧栏实例启动时会清空原生输入框当时的未发送草稿一次；同一实例内的 AI 页面重连或重载不触发再次清空。

### 数据用途与开发者访问

Doujar 没有开发者自建后端或使用分析服务。扩展不会将网页内容、对话或本地设置上传给开发者，不出售用户数据，不将其用于广告、用户画像、信用评估、贷款或与网页阅读辅助无关的用途。

扩展不提取登录密码或认证 Cookie，不请求设备地理位置，也不记录点击日志、鼠标轨迹或键盘输入日志。选区和输入事件仅用于即时界面交互。点击 Copy 时，选中内容会写入本地系统剪贴板。

开发者启用诊断时，诊断信息仅在侧栏内存中处理，可能包含任务 ID、读取计数及最多 300 字符的回复片段，不自动上传或持久化；只有明确点击复制诊断信息时才写入本地剪贴板。

通过 Chrome API 获取的数据仅用于已说明的阅读辅助功能，并遵守 Chrome Web Store 用户数据政策及 Limited Use 要求。Doujar 申请 sidePanel、storage、scripting 和 HTTP/HTTPS 网站访问权限，不申请 tabs 或 declarativeNetRequestWithHostAccess。

### 你的控制方式

你可以全局关闭选区工具条、按页面或域名禁用、暂停 24 小时、修改设置，以及关闭或卸载扩展。卸载会删除扩展的本地设置和会话存储，但不会撤回已发送给豆包的消息；请通过豆包自己的功能管理这些消息。

### 政策页面与联系

本页面通过 GitHub Pages 托管，访问本网站适用 GitHub 自身的隐私声明。本页面未添加统计或广告脚本。

如有隐私问题，可通过 [raywill/doujar Issues](https://github.com/raywill/doujar/issues) 联系开发者。扩展数据处理方式发生变化时，会同步更新本政策和 Chrome Web Store 申报。
