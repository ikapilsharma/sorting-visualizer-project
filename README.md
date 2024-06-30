# Sorting Visualizer

Sorting Visualizer is a C++ project that visually demonstrates the working of various sorting algorithms using the SDL2 library. This tool helps in understanding how different sorting algorithms sort a list of elements in ascending order.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Algorithms Visualized](#algorithms-visualized)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Controls](#controls)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sorting Visualizer is a visualization tool for understanding different sorting algorithms. It visually represents how elements in a list are sorted step by step, making it easier to comprehend the sorting process. The tool includes several common sorting algorithms and allows users to randomize the list and select the algorithm to be visualized.

## Features

- Visualize different sorting algorithms in action.
- Randomize the list of elements to sort.
- Easy-to-use controls for selecting and executing different sorting algorithms.
- Educational tool for understanding sorting algorithms.

## Algorithms Visualized

- **Selection Sort**
- **Insertion Sort**
- **Bubble Sort**
- **Merge Sort**
- **Quick Sort**
- **Heap Sort**

## Prerequisites

- **C++ Compiler**: Ensure you have a C++ compiler installed on your machine.
- **SDL2 Library**: You need to have SDL2 installed. You can download it from [SDL2 Download](https://www.libsdl.org/download-2.0.php).

## Setup

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/ikapilsharma/sorting-visualizer-project.git
    cd sorting-visualizer-project
    ```

2. **Install SDL2**:
    Follow the instructions on the [SDL2 Installation Page](https://wiki.libsdl.org/Installation) to install SDL2 on your system.

3. **Build the Project**:
    Compile the source code using your preferred C++ compiler. For example:
    ```sh
    g++ SortingVisualizer.cpp -o SortingVisualizer -lSDL2
    ```

## Usage

1. **Run the Application**:
    ```sh
    ./SortingVisualizer
    ```

2. **Follow the On-Screen Instructions**:
    The application will guide you through the available controls and options for visualizing different sorting algorithms.

## Controls

- **0**: Generate a new randomized list.
- **1**: Start Selection Sort.
- **2**: Start Insertion Sort.
- **3**: Start Bubble Sort.
- **4**: Start Merge Sort.
- **5**: Start Quick Sort.
- **6**: Start Heap Sort.
- **q**: Exit the Sorting Visualizer.

**Note**: Please wait for the current sorting algorithm to complete before issuing a new command to avoid unexpected behavior.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Happy Sorting!
