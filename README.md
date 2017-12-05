# Rust_project_description

## d7018e - special studies in embedded systems

##### Name : Viktor Fällman
##### Mail : vikfll-0@student.ltu.se
##### Personal number: XXXXXX
##### CAN bus API

## Grading

3. Experiment with the STM32F042K6 controller and build a demo which includes:
* A node (STM32F042K6)
* A can bus (Build using a breadboard)
* A host (either STM32F042K6 or CAN analyzer connected to a computer)

Where messages can be transmitted and recieved by the node. Focus is on experimentation and getting CAN communication running on a hardware level.

4. Design and discuss a proper implementation of a API that would allow for others to build application on top of this communication API. Focus lies on scalability and modifiability. Where the design of the API should be implemented in such a way that it allows for other contributors to add functionality and perhaps move the API to a new processor without much work.

5. Implement the API with proper documentation, testing and examples so to allow others to understand how to use it, show its proof of correctness towards the design made for grade 4 and further allow for others to work with the API during further development. Demo of the completed project should include a sensor that allows for the node to gather information and send it on the CAN bus. 


## References:

`STM32F042K6 datasheet`
http://www.st.com/content/ccc/resource/technical/document/datasheet/52/ad/d0/80/e6/be/40/ad/DM00105814.pdf/files/DM00105814.pdf/jcr:content/translations/en.DM00105814.pdf

`STM32F042K6 reference manual`
http://www.st.com/content/ccc/resource/technical/document/reference_manual/c2/f8/8a/f2/18/e6/43/96/DM00031936.pdf/files/DM00031936.pdf/jcr:content/translations/en.DM00031936.pdf

`CAN bus wiki`
https://en.wikipedia.org/wiki/CAN_bus

`CAN bus protocol`
https://www.kvaser.com/about-can/the-can-protocol/
