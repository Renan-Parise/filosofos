# Dining Philosophers Problem

This repository contains a Python implementation of the Dining Philosophers Problem using threading and semaphores.

## Overview

The Dining Philosophers Problem is a classic synchronization and concurrency problem that illustrates the challenges of resource sharing and deadlock avoidance. In this implementation, a specified number of philosophers sit around a dining table. Each philosopher alternates between thinking and eating. To eat, a philosopher must acquire two forks (representing shared resources) on either side of them.

## Implementation Details

The solution uses Python threading and semaphores. Each philosopher is represented by a separate thread, and semaphores are used to control access to the shared resources (forks).

## Contribute
If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## How to Run

1. Make sure you have Python installed on your system.
2. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/Renan-Parise/filosofos.git
    ```

3. Navigate to the project directory.

    ```bash
    cd filosofos
    ```

4. Run the Python script.

    ```bash
    python app.py
    ```

## Configuration

You can adjust the number of philosophers by modifying the `NUM_FILOSOFOS` variable in the `dining_philosophers.py` script.

```bash
NUM_FILOSOFOS = 3  # Change this value to the desired number of philosophers