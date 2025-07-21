# 🧮 Python Calculator

A lightweight command-line calculator for basic arithmetic operations.

![Calculator Demo](demo.gif) *(Optional: Add an animated GIF showing usage)*

## Features ✨
- **Basic Operations**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Memory Functions**: Store/recall values (MC, MR, M+, M-)
- **Error Handling**: Division by zero protection
- **History**: View last 5 calculations
- **Unit Conversion**: Temperature (C° ↔ F°), Length (cm ↔ in)

## Requirements 📋
- Python 3.8+
- No external dependencies

## Installation ⚙️
```bash
# Clone repository
git clone https://github.com/yourusername/python-calculator.git

# Navigate to project
cd python-calculator

# Run directly
python calculator.py
```

## Usage 🚀
```bash
python calculator.py
```
1. Select operation from menu:
   ```
   1. Add      4. Divide
   2. Subtract 5. Memory
   3. Multiply 6. History
   ```
2. Follow on-screen prompts
3. Press `q` to quit

## Code Structure 🧩
```
calculator/
├── main.py            # Entry point
├── calculator.py      # Core logic
├── history_manager.py # Calculation history
├── unit_converter.py  # Conversion functions
└── tests/             # Unit tests
```

## Contributing 🤝
1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/new-function
   ```
3. Commit changes:
   ```bash
   git commit -m 'Add percentage function'
   ```
4. Push to branch:
   ```bash
   git push origin feature/new-function
   ```
5. Open a pull request

## License 📄
This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---
> 💡 **Tip**: Run with `-h` flag for help:  
> `python calculator.py -h`
