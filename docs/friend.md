# 好友 (Friend)

## 属性

| 属性名 | 类型                            | 描述         |
| ------ | ------------------------------- | ------------ |
| id     | Integer                         | 好友的 qq 号码 |
| bot    | [`Bot`](/docs/bot.md) | bot 对象      |
| nick | String | 昵称 |
| nameCardOrNick | String | 备注（若不存在备注则返回昵称） |
| avatarUrl | String | 头像地址 |
| isActive | Boolean | 是否在线 |

## 方法


### sendMessage (发送消息)

#### 参数列表：

| 参数 | 类型                            | 描述     |
| ---- | ------------------------------- | -------- |
| message  | [`Message`](/docs/message.md) | 消息对象 |

#### 返回值：

| 类型                          | 描述                   |
| ----------------------------- | ---------------------- |
| [`Message`](/docs/message.md) | 消息对象，可用于撤回。 |



### sendImage (发送图片消息)

#### 参数列表：

| 参数 | 类型                            | 描述     |
| ---- | ------------------------------- | -------- |
| url  | String | 图片 URL |

#### 返回值：

| 类型                          | 描述                   |
| ----------------------------- | ---------------------- |
| [`Message`](/docs/message.md) | 消息对象，可用于撤回。 |

