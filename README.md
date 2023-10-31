# **Webots Template Project**

## **Introduction**

- Project to simulate Robot with C++ edited in Vscode. 
- If you are interseted in this project and need more information, please contact Clang(clangwu@163.com) to get an access.  

## **How to run this program**?

- **Start your Simulation:**
  1. Add the variable`WEBOTS_HOME`in the system with the path `${webots_installed_place}`.
     - `${webots_installed_place}` is the place where webots is installed, for example `D:\webots`.
  2. Open the directory `./controllers/my_controller/` with Vscode.
  3. Compile the program(2 ways)
     - use CMake tools.
     - use command line: `mkdir build && cd build ` and ` cmake .. && make`.
  4. Open scence file `./worlds/car.wbt` with Webots.
  5. Start simulation using the start button in Webots.

## **Dependencies**

### **Running Enviroment :**

**Platform: refer to the Webots version**

- CMake (version 3.12.0 +) 


### **Simulation Enviroment :**

- Webots (Recommended newer than(also include) version: R2020b)

