# Heart Animation using Turtle

This project creates a heart shape animation using the `turtle` module in Python. The script draws a red heart and fills it with color.

## Requirements

- Python 3.x
- Turtle module (included in Python standard library)

## Installation

1. Ensure you have Python 3.x installed. You can download it from [Python.org](https://www.python.org/).
2. The `turtle` module is included in the Python standard library, so no additional installations are necessary.

## Usage

1. Clone this repository or download the `heart_animation.py` file.
2. Run the script:

   ```sh
   python heart_animation.py
   ```
## Code Explanation
The main script heart_animation.py includes:
```python
from turtle import *

# Main Function
begin_fill()
color('red')
left(50)
forward(100)
circle(40, 180)
left(260)
circle(40, 180)
forward(100)
end_fill()
done()
```

## Contributing
Feel free to fork this repository and contribute by submitting a pull request. Any improvements or new features are welcome!

## License
This project is licensed under the MIT License.

