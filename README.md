# Whisk Parser ![GitHub issues](https://img.shields.io/github/issues/Neuri-ai/whisk-parser) ![GitHub forks](https://img.shields.io/github/forks/Neuri-ai/whisk-parser) ![GitHub stars](https://img.shields.io/github/stars/Neuri-ai/whisk-parser) ![GitHub licence](https://img.shields.io/github/license/Neuri-ai/whisk-parser)

Parse emails from Vosk API and Whisper.

## Installation

Please ensure that you have **updated pip** to the latest version before installing word2number_es.

You can install the module using Python Package Index using the below command.

    pip install whisk_parser

Make sure you install all requirements given in requirements.txt
```
pip install -r requirements.txt
```
## Usage

First you have to import the module using the below code.

    from whisk_parser import wp

Then you can use the **parse_email** method to convert a number-word to numeric digits, as shown below.

```
print(
    wp.parse_email('my email is john at gmail.com')
)
my email is john@gmail.com
```

```
print(
    wp.parse_email('my email is john underscore doe at gmail.com')
)
my email is john_doe@gmail.com
```

```
print(
    wp.parse_email('The aggregate and underlying individual governance indicators are available at www.govindicators.org.')
)
The aggregate and underlying individual governance indicators are available at www.govindicators.org.
```




## Contributors
- Luis Alfredo Reyes [runesc](https://github.com/runesc)