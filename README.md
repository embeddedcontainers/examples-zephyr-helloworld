# Zephyr Hello World example

Based on the `hello_world` from Zephyr. Currently demonstrates:

* Using Dev Containers (tested in VS Code and on Codespaces)
* VS Code build tasks
* GitHub Actions to build and create Releases

## Dev Container

Uses the `arm` image and STM32 for this example. Once the Dev Container is loaded, open a terminal and run `west build -b nucleo_c031c6 app`.
