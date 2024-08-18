# Auto-Colorize

`Auto-Colorize` is a bash script that colorizes the output of a command with random colors. Use it in a pipeline to apply dynamic and varied color to your text output.

## Features

- Applies random colors to the text.
- Works with any command output when used in a pipe.
- No additional dependencies required beyond typical Unix utilities.

## Installation

1. **Download the Script**:

   It can be installed with the command down below

   ```bash
   git clone https://github.com/Zmp0/Auto-Colorize.git && cd Auto-Colorize && sudo cp color /usr/local/bin && sudo chmod +x /usr/local/bin/color
    ```

### After installing the script, all the output of the first command, is gonna be colorized

For Example:


```bash
ls | color 
```

```bash
cat somefile.txt | color
```

```bash
echo Hello World | color
```
