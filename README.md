# 照片海报技能集

六种照片海报风格，加一个 PS 大师选择入口。由 Shirehuhu 整理、精简并分享；
原作者、来源和修改记录见 [NOTICE.md](NOTICE.md)。

**用途：免费个人非商业分享。** 本合集包含受限第三方组件，不能将整包当作 MIT 或无限制商用素材；
各组件的具体许可证分别保留，第 2 种仍遵守原 MIT 授权。

## 六种风格

| 编号 | 风格 | 特征 |
|---|---|---|
| 1 | [实景拼贴](skills/scenes-gathered-zine-v1-3/SKILL.md) | 真实摄影、源图抽象插画、结构性色彩与手撕纤维边缘 |
| 2 | [极简杂志](skills/gc-minimal-zine-poster-v0-3/SKILL.md) | 大留白、小型视觉事件、编辑字体与清晰色彩点 |
| 3 | [场景提炼](skills/scene-distillation-zine-v1-3/SKILL.md) | 原创插画与视觉隐喻，不保留摄影像素；支持单色块模式 |
| 4 | [莫兰迪电影](skills/morandi-cinematic-poster-zeejay/SKILL.md) | 保真摄影底图与克制的电影海报字体 |
| 5 | [水彩海报](skills/watercolor-editorial-poster/SKILL.md) | 低饱和水彩/水粉、米白留白、英文标题和斜体副标题 |
| 6 | [纸浆浮雕海报](skills/paper-pulp-relief-poster/SKILL.md) | 3:4 独立海报、轻薄纸纤维浮雕、中文编辑排版 |

[PS 大师](skills/ps-master/SKILL.md)负责风格选择、先调色、保真检查和可选原图/成品拼图。
第 6 种默认只出单张，不拼图；其他风格作图前确认是否拼图及相关设置。

## 安装

1. [下载照片风格技能.zip](./照片风格技能.zip?raw=1)，解压后在 skills 目录内找到七个技能文件夹。
2. 将七个文件夹放入你当前 Codex 的个人 Skills 目录。当前官方用户级目录是
   Windows 的 %USERPROFILE%\.agents\skills，或 macOS/Linux 的 ~/.agents/skills。
   保持每个目录中的 SKILL.md、references、assets、agents、LICENSE 等文件完整。
3. 不要直接覆盖自己修改过的同名技能；先备份、比较，避免重复安装相同调用名。
4. Codex 会检测技能；未出现时重新打开会话或重启客户端。

也可让 Codex 的 skill-installer 从本仓库的 skills 目录安装需要的组件。
[官方技能说明与目录规则](https://developers.openai.com/codex/skills#where-to-save-skills)

## 使用

在支持图像生成/编辑的环境中上传照片并说明：

> 用 $ps-master 处理这张图，先让我选风格。

也可以直接选择，例如：

> 用 $paper-pulp-relief-poster 处理这张图，保留完整主体，每张单独输出。

本包只有技能说明和必要参考资源，不包含模型、图像生成服务或 API 密钥。
需要运行环境提供图像生成/编辑能力；工具不可用时，不应伪称已经生成。

## 质量与隐私

- 保留主体、姿态、身份与关键道具，尺寸适配不拉伸，必要裁剪应先保护主体。
- 默认至少 2K 长边；常规放大不等于恢复原生细节。
- 交付前检查实际图像；手指、文字和人物一致性仍需人工验收。
- 当前已做结构、引用与资源校验，未做六风格实图 A/B 测试，不承诺每次生成都更好。
- 本仓库和下载包不含整理者的私人照片或凭据；附带图片为保留授权的上游参考资源。
- 本地安装不等于离线模型运行。实际照片处理与数据政策取决于你使用的客户端和图像服务。

## 授权

第 1、3、4 种遵守 Zeejay0 原个人非商业许可证；第 2 种遵守 LiamGvchi 原 MIT 许可证；
第 5、6 种、PS 大师和本仓库新增文档遵守 [LICENSE](LICENSE)。
免费公开不等于允许销售、付费代做或商业服务。请逐组件阅读许可和 [来源声明](NOTICE.md)。
