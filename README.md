# Rust_project_description

## d7018e - special studies in embedded systems

##### Name : Viktor Fällman
##### Mail : vikfll-0@student.ltu.se
##### Personal number: XXXXXX
##### CAN bus API and Wheel Sensor implementation

## Grading

3. Experiment with the STM32F042K6 controller and build a demo which includes:
* A node (STM32F042K6)
* A can bus (Build using a breadboard)
* A host (either STM32F042K6 or CAN analyzer connected to a computer)

Where messages can be transmitted and recieved by the node. Focus is on experimentation and getting CAN communication running on a hardware level.

4. Design and discuss a proper implementation of a API that would allow for others to build application on top of this communication API. Focus lies on scalability and modifiability. Where the design of the API should be implemented in such a way that it allows for other contributors to add functionality and perhaps move the API to a new processor without much work.

5. Implement the API with proper documentation, testing and examples so to allow others to understand how to use it, show its proof of correctness towards the design made for grade 4 and further allow for others to work with the API during further development.
