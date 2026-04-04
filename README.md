# 数字孪生猫砂盆
通过数字孪生技术，实现虚拟猫笼与现实猫笼之间的联动。本项目主要是数字暖生猫砂盆的前端，通过vue+three.js实现三维模型的展示、联动、操作。操控端是以esp32为控制芯片的嵌入式系统，实现了提供websocket接口的web服务器和输入输出设备的操控。通过队列，实现IO设备的操控线程和web服务器线程之间的信息传递。web服务器通过websocket接口来支撑其与前端的信息传递，以实现三维模型与IO设备的联动。
## 具体实现
(gif图片较大，加载较慢)
![gif图片较大，加载较慢](https://github.com/user-attachments/assets/dff76659-371f-4571-bae1-57fb44b303b2)



<img width="1834" height="964" alt="Image" src="https://github.com/user-attachments/assets/b99a9bce-f498-446a-8efa-7f38bf81982c" />
