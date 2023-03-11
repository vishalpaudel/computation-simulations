# Cellular Automata

This is a simple implementation of a cellular automata in Python using Pygame. The current implementation is a one-dimensional automata which uses a pre-defined rule to determine the state of each cell at each iteration.

## Requirements

- Python 3.x
- Pygame library

## Usage

To use this implementation, clone this repository and run the following command in the project directory:

```
python3 main.py
```


The automata will start running, and a Pygame window will open displaying the evolving states of the automata.

## Configuration

The automata can be configured by changing the parameters in the `config.json` file. The following parameters can be configured:

- `num_iter`: The number of iterations to run the automata for
- `mov_iter`: The number of iterations to show in the Pygame window at any given time
- `rule`: The rule for the automata, in the form of a list of tuples. Each tuple should contain two elements: a tuple representing the frame to match, and an integer representing the state to set for the cell in the center of the frame. For example, the following is a rule that sets the center cell to 1 if the left and right cells are both 1, and 0 otherwise:
```
"rule": [
[
[(1, 1, 0), 1],
[(1, 0, 1), 1],
[(1, 0, 0), 0],
[(0, 1, 1), 1],
[(0, 1, 0), 0],
[(0, 0, 1), 0],
[(0, 0, 0), 0]
]
]
```
- `init_state`: The initial state of the automata, in the form of a list of 0s and 1s.


## Introduction:

The purpose of this project is to provide a comprehensive tool to experiment with cellular and mobile automata.

## Examples images and videos

![main-2-rule-2409](https://user-images.githubusercontent.com/95016059/224503561-bd821660-4b69-4b32-8c89-072dae1143e3.jpg)

![main-1-rule-90](https://user-images.githubusercontent.com/95016059/224503557-4e00dec4-dc40-411a-ba3d-3dddde352571.jpg)

https://user-images.githubusercontent.com/95016059/224503537-8b4bc288-1ca1-4ed6-ad17-b034696eba6c.mov

https://user-images.githubusercontent.com/95016059/224503543-693709ce-f2c1-4ef1-9ae3-fde112752639.mov

https://user-images.githubusercontent.com/95016059/224503546-58214c20-5693-481d-a5d4-7faa013e6d6d.mov

https://user-images.githubusercontent.com/95016059/224503548-b7c5b6bf-83ad-4ea4-8d8e-0912c13fe8c3.mov


## Goals:

The primary goal of this project is to create a user-friendly and robust software solution that can be used by individuals and organizations for various purposes. The software solution aims to provide users with the ability to accomplish complex tasks with ease and efficiency. Additionally, the project aims to promote collaboration and community engagement by encouraging contributions from individuals and organizations.

## Features:

The project includes several features that are designed to enhance its usability and functionality. These features include:

- **User-friendly interface**: The project includes a user-friendly interface that is easy to navigate and understand.

- **Customizable settings**: The project includes customizable settings that allow users to tailor the tool to their specific needs.


## Contribution Guidelines:

To contribute to the project, users should follow these guidelines:

- Fork the project repository.
- Make the desired changes.
- Submit a pull request.
- Wait for feedback and approval from the project maintainers.

## Conclusion:

In conclusion, this project is a comprehensive software solution that is designed to provide users with the ability to accomplish complex tasks with ease and efficiency. The project includes several features that enhance its usability and functionality. Additionally, the project promotes collaboration and community engagement by encouraging contributions from individuals and organizations.

## License

This project is licensed under the terms of the MIT license.

