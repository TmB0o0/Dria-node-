# 🌐 DRIA节点安装和设置指南

## ⚙️ 系统要求

| 组件       | 最低规格   |
|------------|------------|
| CPU        | 4核       |
| RAM        | 8GB       |
| 存储       | 100GB SSD |
| 端口       | 4001      |

## 第一步：开始安装

要安装和运行DRIA节点，请在终端中执行以下命令：

```bash
curl -O https://raw.githubusercontent.com/TmB0o0/Dria-node-/refs/heads/main/guide-zh/dria && chmod +x dria && sudo ./dria
```
运行此命令后，安装过程将开始，您需要选择一个模型。

## 第二步：选择模型

-   **确保保存您的密钥！** 之后将不会再次显示。
    

启动节点时，您将被提示选择一个模型。您有几个选项：

### 1. 使用Gemini 2.0 Flash

-   访问 [AI Studio](https://aistudio.google.com/prompts/new_chat) 网站。
    
-   在左侧，点击 **"创建API密钥"**。
    
-   再次点击 **"创建API密钥"** 并选择 **GEMINI API** 模型。
    

⚠️ _可能出现的问题:_  
如果出现与区域相关的错误，使用替代选项 — OpenAI。

### 2. 使用OpenAI（可能需要付费）

-   访问 [OpenAI API](https://platform.openai.com/api-keys)。
    
-   在右上角，点击 **"创建新密钥"**。
    
-   在出现的窗口中，输入密钥的名称并选择 **默认项目**。
    
-   **确保保存您的密钥！** 之后将不会再次显示。
    

### 3. 使用OpenRouter

[https://openrouter.ai/](https://openrouter.ai/)

#### 您可以在此查看所有模型：[https://dria.co/edge-ai](https://dria.co/edge-ai)

## 第三步：输入私钥和API密钥

使用键盘上的箭头键在终端中选择所需的模型。  
按 **左箭头** 键选择所有模型，并在相应字段中粘贴密钥。  
选择模型后，系统将要求输入以下内容：

-   **私钥**
    
-   **API密钥**
    

## 完成安装

完成所有步骤后，DRIA节点将安装并运行。

⚠️ 如果遇到任何问题，请尝试以下解决方案：

-   检查API密钥是否正确输入。
    
-   验证是否存在地区限制。
    

### 可能的错误
```bash
"error": {
    "code": 400,
    "message": "用户位置不支持使用此API。",
    "status": "FAILED_PRECONDITION"
}
```
这意味着 **您当前的地理位置不支持使用此API**。
