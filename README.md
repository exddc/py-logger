# py-logger

Basic logger module for console and file logs in Python. The logger module is based on the Python logging module. The logger module provides a basic configuration for logging messages to the console and a file.

The log messages are formatted with file name and line number where the log message was generated.

## Usage

Copy the logger.py file to your project and import it in your code.

```python
from logger import Logger
```

Create a logger object and use it to log messages.

```python
logger = logger.get_module_logger(__name__)
logger.debug('This is a debug message')
logger.info('This is an info message')
logger.warning('This is a warning message')
logger.error('This is an error message')
logger.critical('This is a critical message')
```
