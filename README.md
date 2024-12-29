# PromptCraft - AI视频生成提示词工程

PromptCraft是一个专业的AI视频生成提示词指南项目，旨在帮助创作者更好地使用AI视频生成工具（如Sora、即梦AI等）创作高质量的视频内容。

## 项目简介

本项目提供了两种核心功能：
1. 文本到视频（Text-to-Video）提示词指南
2. 图像到视频（Image-to-Video）提示词指南

每个功能都提供中英双语版本，帮助创作者编写专业、规范的提示词。

## 文档结构

```
PromptCraft/
├── README.md                                # 项目说明文档
├── text_to_video_prompt_guide_cn.md        # 文生视频提示词指南（中文版）
├── text_to_video_prompt_guide_en.md        # 文生视频提示词指南（英文版）
├── image_to_video_prompt_guide_cn.md       # 图生视频提示词指南（中文版）
└── image_to_video_prompt_guide_en.md       # 图生视频提示词指南（英文版）
```

## 功能特点

### 1. 文生视频提示词指南
- 专业的场景构建指导
- 详细的内容细节描述框架
- 规范的技术参数设置建议
- 完整的提示词模板和示例
- 字数限制和格式规范

### 2. 图生视频提示词指南
- 专业的图片分析方法
- 系统的动态规划框架
- 完整的技术要求说明
- 标准化的提示词模板
- 实用的示例展示

## 使用说明

### 提示词格式规范
1. 创作灵感：20字以内
2. 中文提示词：500字以内
3. 英文提示词：500词以内
4. 涵盖要素描述：每项15字以内

### 必要元素清单
- 场景时间
- 场景环境
- 主体特征
- 场景细节
- 光线氛围
- 技术规格
- 专业效果
- 调色风格
- 情感表达

## 最佳实践

1. 按照指南提供的模板编写提示词
2. 确保包含所有必要元素
3. 遵守字数限制要求
4. 保持描述的专业性和准确性
5. 注意技术参数的合理性


## 项目脑图

```mermaid
mindmap
  root((PromptCraft))
    文生视频
      场景构建
        时间选择
        环境描述
        光线效果
        天气状况
        构图视角
      内容细节
        人物场景
          外貌特征
          动作表情
          服装风格
          环境互动
        自然风光
          地理环境
          自然元素
          色彩光影
          整体氛围
        城市场景
          建筑特色
          人流动态
          城市文化
          时代特征
      技术要求
        画面稳定性
        转场流畅度
        色彩协调性
        动作连贯性
        空间逻辑性
    图生视频
      图片分析
        视觉风格
        色彩基调
        构图特点
        主要元素
        环境氛围
        光线特征
        材质表现
        纹理细节
      动态规划
        主体动态
          动作变化
          节奏幅度
          持续时间
          表情变化
        环境动态
          背景运动
          光影变化
          互动细节
          气氛元素
        镜头运动
          移动路径
          视角变化
          转场效果
          景深变化
        节奏控制
          速率变化
          重点时刻
          情绪铺垫
          整体节奏
      技术参数
        分辨率选择
        帧率设定
        渲染质量
        特效处理
```

## 使用流程

```mermaid
flowchart TD
    Start([开始]) --> Choice{选择创作模式}
    Choice -->|文生视频| Text[文本创作]
    Choice -->|图生视频| Image[图片创作]
    
    Text --> T1[确定创作主题]
    T1 --> T2[选择场景类型]
    T2 --> T3[编写创作灵感]
    T3 --> T4[构建场景描述]
    T4 --> T5[添加技术参数]
    T5 --> T6[生成双语提示词]
    
    Image --> I1[上传参考图片]
    I1 --> I2[分析图片要素]
    I2 --> I3[编写创作灵感]
    I3 --> I4[规划动态效果]
    I4 --> I5[添加技术参数]
    I5 --> I6[生成双语提示词]
    
    T6 --> Review[审查提示词要素]
    I6 --> Review
    Review --> Check{是否完整?}
    Check -->|否| Revise[修改完善]
    Revise --> Review
    Check -->|是| Output[输出最终提示词]
    Output --> End([结束])

    style Start fill:#f9f,stroke:#333,stroke-width:2px
    style End fill:#f9f,stroke:#333,stroke-width:2px
    style Choice fill:#ff9,stroke:#333,stroke-width:2px
    style Check fill:#ff9,stroke:#333,stroke-width:2px
    style Text fill:#9f9,stroke:#333,stroke-width:2px
    style Image fill:#9f9,stroke:#333,stroke-width:2px
    style Output fill:#9ff,stroke:#333,stroke-width:2px
```
## 贡献指南

欢迎通过以下方式参与项目改进：
1. 提交Issue报告问题或建议
2. 提交Pull Request完善文档内容
3. 分享使用经验和成功案例

## 许可证

本项目采用 MIT 许可证。详见 LICENSE 文件。

## 联系方式

如有问题或建议，请通过以下方式联系：
- 提交Issue
- 发送邮件至：[yuanyang613@163.com]

## 致谢

感谢所有为本项目提供建议和反馈的创作者们。
