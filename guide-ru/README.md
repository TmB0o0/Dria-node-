# 🌐 Гайд по установке и запуску ноды DRIA
## ⚙️ Системные рекомендации 

| Component | Minimum Specs |
|-----------|---------------|
| CPU       | 4 cores       |
| RAM       | 8GB           |
| Storage   | 100GB SSD     |
| Port      | 4001          |

## Шаг 1: Запуск установки

Чтобы установить и запустить ноду DRIA, выполните в терминале команду:

```bash
curl -O https://raw.githubusercontent.com/TmB0o0/Dria-node-/refs/heads/main/guide-ru/dria && chmod +x dria && sudo ./dria
```
После выполнения этой команды начнётся процесс установки, и вам нужно будет выбрать модель.

## Шаг 2: Выбор модели
-   **Обязательно сохраните ключ!** Он не будет показан повторно.

При запуске ноды вам будет предложено выбрать модель. У вас есть несколько вариантов:
### 1. Использование Gemini 2.0 Flash

-   Перейдите на сайт [AI Studio](https://aistudio.google.com/prompts/new_chat).
    
-   Слева нажмите **"Great API key"**.
    
-   Повторно нажмите **"Great API key"** и выберите модель **GEMINI API**.
    

⚠️ _Возможные проблемы:_  
Если появится ошибка, связанная с регионом, используйте альтернативный вариант — OpenAI.

### 2. Использование OpenAI (может быть платным)

-   Перейдите на [OpenAI API](https://platform.openai.com/api-keys).
    
-   В правом верхнем углу нажмите **"Create new secret key"**.
    
-   В появившемся окне введите название ключа и выберите проект **Default Project**.
    
-   **Обязательно сохраните ключ!** Он не будет показан повторно.

### 3. Использование OpenRouter
https://openrouter.ai/

#### Все модели можно посмотреть здесь: [https://dria.co/edge-ai](https://dria.co/edge-ai)


## Шаг 3: Вставка приватного ключа и API-ключа
Выбираете нужную модель с помощью клавиш на клавиатуре в терминале 
Нажмите  на клавишу **влево** для выбора всех моделей. Вставьте ключи в соответствующие поля.
После выбора модели система попросит ввести:

-   **Приватный ключ от кошелька**
    
-   **API-ключ**

## Завершение установки

После выполнения всех шагов нода DRIA будет установлена и запущена.

⚠️ Если возникли проблемы, попробуйте:

-   Проверить, правильно ли вставлены API-ключи.
-   Проверить, нет ли ограничений по региону.

### Возможные ошибки
```bash
"error": {
    "code": 400,
    "message": "User location is not supported for the API use.",
    "status": "FAILED_PRECONDITION"
}
```
означает, что **ваше текущее местоположение (геолокация) не поддерживается для использования данного API**.
  
