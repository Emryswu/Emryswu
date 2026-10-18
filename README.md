## Hi, I'm Emrys 👋

计算机专业本科在读，方向是 **Java 后端 + AI 应用开发**。
喜欢把并发、幂等、一致性这类"容易出错的地方"做对，并用测试证明它是对的。

**技术栈**：Java 21 · Spring Boot 3 · Spring Security · JPA / MySQL · Redis · RabbitMQ · RAG / 向量检索 · Lucene · ONNX · Next.js / React

### 项目

| 项目 | 简介 |
| --- | --- |
| [ResumeLens](https://github.com/Emryswu/ResumeLens) | 简历与岗位 JD 智能匹配系统：本地 ONNX 向量检索 + Lucene 索引 + Hybrid RAG 证据链，Tool-calling 助手，Spring Boot 3.5 + Next.js |
| [LabFlow](https://github.com/Emryswu/LabFlow) | 实验室设备预约与故障工单平台：Redis 分布式锁 + 数据库行锁防超卖，RabbitMQ 延迟队列处理超时，支付幂等与 T+1 对账，JWT 双令牌鉴权 |

### 开源贡献（已合入）

- **[redisson/redisson #7380](https://github.com/redisson/redisson/pull/7380)**：修复批量执行期间定时 PING 关闭连接的问题
- **[apache/shenyu #7541](https://github.com/apache/shenyu/pull/7541)**：修复缓存插件在规则 handle 为空时的空指针
- **[hutool #4340](https://github.com/chinabugotech/hutool/pull/4340) / [#4341](https://github.com/chinabugotech/hutool/pull/4341)**：修复 ClassScanner 扫描 jar 后关闭共享 JarFile 导致的 `Zip file closed`（v5 / v7 分支）

<details>
<summary>Review 中</summary>

- [spring-ai #7126](https://github.com/spring-projects/spring-ai/pull/7126)：`TransformersEmbeddingModel` 支持自定义 ONNX `SessionOptions`
- [spring-ai #7158](https://github.com/spring-projects/spring-ai/pull/7158)：修复 Elasticsearch NE 过滤器生成非法查询
- [spring-ai #7159](https://github.com/spring-projects/spring-ai/pull/7159)：允许关闭 `OpenAiChatModel` 自建的 OpenAI client
- [langchain4j #6738](https://github.com/langchain4j/langchain4j/pull/6738)：OpenAI Responses 流式失败时保留错误码与类型
- [Sa-Token #990](https://github.com/dromara/Sa-Token/pull/990)：二级认证支持指定 token 操作

</details>
