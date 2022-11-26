[Rome VS Code Extension](https://marketplace.visualstudio.com/items?itemName=rome.rome) crashes by inputting Japanese.

![VS Code after crash](https://i.gyazo.com/b15f4ebb6e43a7d9bee519a97a5971b3.png)

To reproduce the problem, follow the procedures below.

1. Clone this repository and open it with VS Code
2. Install [Rome VS Code Extension](https://marketplace.visualstudio.com/items?itemName=rome.rome)
3. Reload the window
4. Open "index.js"
5. Delete Japanese characters in "index.js" one by one
6. The Rome server crashes
