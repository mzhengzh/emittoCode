# emittoCode
A Visual Studio workspace and project holder to Emitto firmware code

# Purpose
(1) Particle IoT platform doesn't provide a straightforward way for local compiling and building.   
(2) Visual Studio Code does provide a way to do local compiling and editing. However VS Code doesn't provide a simple way to manage code project. It basically supports "folder" rather "project".  
(3) The initial Emitto code was created to support 4 different MCUs, some of files/functions are shared among 4 products.   

Adding all above together, it's very challenge to put together a concise thing to manage the source code. So I borrowed Visual Studio to manage the code editing.   

# Usage
(1) Open emittoCode.sln to use this tool.  
(2) The compile and build needs use Particle cloud CLI.   
       1) WSL ubuntu 14. Because the Particle CLI needs python 2.7  
       2) With above setup, run "compileEmitto.sh" to build code on Particle cloud.   
       3) Run "flashEmitto.sh" to load firmware on device via Particle cloud.   
       
 
 
 
