## 🧬 Genetic Text Evolution: Evolving "HELLO WORLD" with Python
- Welcome to Genetic Text Evolution, an interactive and visual demonstration of how a Genetic Algorithm (GA) can learn to evolve a random set of characters into a target phrase — in this case, the classic "HELLO WORLD".

- Built with tkinter and matplotlib, this project makes evolutionary computation fun, visual, and beginner-friendly.

## 📌 Features
- 🎯 Target Phrase Matching: Evolve random characters into any desired string.

- 🧠 Genetic Algorithm Logic: Includes selection, crossover, mutation, and fitness evaluation.

- 📊 Live Visualization: Track the best fitness score over generations using matplotlib.

- 🖱️ Interactive GUI: Modify parameters like population size and mutation rate via a user-friendly interface.

## 🖼️ Screenshot
![image](https://github.com/user-attachments/assets/f3efac14-6fc4-42f3-9375-10e58b3d1ee5)


## 🚀 How It Works
```mermaid
graph TD
    A[Start Program] --> B[Initialize Parameters]
    B --> C[Generate Initial Population]
    C --> D[Calculate Fitness]
    D --> E{Target Found or Max Gen?}
    E -- Yes --> F[Show Final Result]
    E -- No --> G[Select Parents]
    G --> H[Crossover]
    H --> I[Mutation]
    I --> J[New Generation]
    J --> D

```

## ⚙️ Requirements
- Python 3.7+

- tkinter

- matplotlib


## 📘 Theory Reference
- Genetic Algorithms are inspired by Darwin’s theory of natural selection.

- This implementation is based on fitness-based evolution using crossover and mutation.
