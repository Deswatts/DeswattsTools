## 简介

- DeswattsTools 是一个为开发者提供工具的包, 目前仅有日志工具, 之后会更新更多的工具

## 示例

```python
# A simply example for logutil
from src import setup_logger  # Import setup logger tool

logger = setup_logger(__name__)  # Setup logger

if __name__ == '__main__':  # Program start on here
    logger.info("This is a Example")  # Output log to console and file
```