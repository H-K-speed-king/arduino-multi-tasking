# arduino-multi-tasking
This is a simple example to implement the multitasking on arduino uno

Aim of this project is give a quick demo of multitasking on arduino
without using protothreading or TimedAction. The biggest issue with 
arduino is it's linear code execution. Because of this its hard to 
perform multiple tasks at a same time. If we use a delay function in 
any part of the code it will delay the all the codes after it. To
Avoid this I'm using a smart logic to handle the delay functions. this
kind of delay implementation never block the code execution. So we can 
perform multiple tasks at a same time.
