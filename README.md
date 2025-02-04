# **C# Code Snippets Repository**

This repository contains a collection of **useful C# code snippets** to help you speed up your development workflow. These snippets are designed for use in **Visual Studio** and cover a variety of common scenarios, including **CQRS**, **Dependency Injection**, **Entity Framework**, **Logging**, and more.

---

## **Table of Contents**
1. [Getting Started](#getting-started)
2. [Snippets List](#snippets-list)
   - [CQRS](#cqrs)
   - [Dependency Injection](#dependency-injection)
   - [Entity Framework](#entity-framework)
   - [Enums](#enums)
   - [Logging](#logging)
   - [Middleware](#middleware)
   - [Utility](#utility)
3. [How to Use Snippets](#how-to-use-snippets)
4. [Contributing](#contributing)
5. [License](#license)

---

## **Getting Started**

### Prerequisites
- **Visual Studio** (2017 or later recommended).
- Basic knowledge of **C#** and **.NET**.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/ralphtashinganyoni/snippets.git
   ```
2. Open Visual Studio.
3. Import the snippets into Visual Studio:
   - Go to `Tools` > `Code Snippet Manager`.
   - Click `Import` and select the `.snippet` files from this repository.
   - Choose a location to save the snippets (e.g., `My Code Snippets`).

---

## **Snippets List**

### **CQRS**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| CQRS Command          | `command` | Creates a CQRS command handler implementation.                                   |

---

### **Dependency Injection**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| DI Service            | `diservice`   | Creates a service class with dependency injection.                           |

---

### **Entity Framework**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| EF DbContext          | `efdbcontext` | Creates an Entity Framework `DbContext` class.                               |
| EF Repository         | `efrepo`      | Creates a generic repository pattern for Entity Framework.                   |

---

### **Enums**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| Enum with Description | `enumdesc`     | Creates an `enum` with `Description` attributes.                            |

---

### **Logging**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| Logging Middleware    | `loggingmiddleware` | Creates a logging middleware for ASP.NET Core.                         |
| Try-Log Pattern       | `trylog`       | Wraps code in a `try-catch` block with logging.                             |

---

### **Middleware**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| Middleware Setup      | `middlewaresetup` | Creates a basic middleware setup for ASP.NET Core.                       |

---

### **Utility**
| Snippet Name          | Shortcut       | Description                                                                 |
|-----------------------|----------------|-----------------------------------------------------------------------------|
| AAA Pattern           | `aaa`          | Creates a test method using the **Arrange-Act-Assert** pattern.             |

---

## **How to Use Snippets**

1. Open a C# file in Visual Studio.
2. Type the **shortcut** for the snippet (e.g., `command`).
3. Press `Tab` twice to expand the snippet.
4. Fill in the placeholders (e.g., class names, method names) as needed.

---

## **Contributing**

We welcome contributions to this repository! If you have a useful snippet you'd like to share, follow these steps:

1. Fork this repository.
2. Create a new branch for your snippet:
   ```bash
   git checkout -b feature/your-snippet-name
   ```
3. Add your snippet file (`.snippet`) to the repository.
4. Update the **Snippets List** in this `README.md` file.
5. Commit your changes:
   ```bash
   git commit -m "Added snippet: Your Snippet Name"
   ```
6. Push your branch:
   ```bash
   git push origin feature/your-snippet-name
   ```
7. Open a **Pull Request** and describe your changes.

---

## **License**

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

- Thanks to the **Visual Studio** team for making code snippets so easy to use!
- Inspired by the needs of developers everywhere to write cleaner, faster, and more efficient code.

---

Happy coding! 🚀

---
