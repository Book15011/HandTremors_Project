# Development of Active Ball Joint Mimicking Shoulder Motion for Assisting Patients with Tremor in Hands

## Project Overview
This project aims to develop an active ball joint that mimics the natural movement of the human shoulder to assist patients with hand tremors. The goal is to create a robotic arm that can filter out tremor-induced movements, providing smoother and more controlled motion for daily activities.

## Motivation
Hand tremors, often caused by conditions like Parkinson's disease or essential tremors, significantly impact the quality of life for patients. Traditional treatments, such as medication and surgery, come with side effects and high costs. This project explores an alternative approach by developing a robotic arm that can compensate for tremors, making daily tasks easier and more manageable.

## Objectives
- Design and develop an active ball joint that can mimic the natural movement of the human shoulder.
- Integrate sensors to detect and filter out tremor-induced movements.
- Create a prototype using 3D printing and microcontrollers.
- Test and validate the system to ensure it can effectively assist patients with hand tremors.

## Design and Development

### Hardware Components
- **Active Ball Joint**: Designed using Fusion 360 and 3D printed to mimic the natural movement of the shoulder.
- **Sensors**:
  - Accelerometer to detect motion.
  - Flex sensor to measure joint angles.
- **Microcontroller**: Arduino Uno for processing sensor data and controlling the joint movement.
- **Actuators**: Stepping motors to drive the joint movement.

### Software Components
- **Arduino IDE**: Used for programming the microcontroller.
- **Sensor Integration**: Data from the accelerometer and flex sensor is processed to filter out tremor-induced movements.
- **Control Algorithms**: Custom algorithms to control the joint movement based on sensor input.

## Results
The prototype successfully mimics the natural movement of the shoulder and can filter out tremor-induced movements. This demonstrates the potential for developing a robotic arm that can significantly assist patients with hand tremors.

## Future Work
- Enhance the stability and precision of the system.
- Integrate additional sensors and actuators to improve functionality.
- Conduct extensive testing with patients to gather feedback and make necessary improvements.
- Explore the possibility of scaling up the prototype for commercial use.

## References
- Abe, K., Tadakuma, K., & Tadakuma, R. (Year). ABENICS: Active Ball Joint Mechanism With Three-DoF Based on Spherical Gear Meshings. *IEEE Transactions on Robotics, 1*(1), Page Numbers. [Link]
- Ali, S. H., Akhtar, A., Khan, M. A., & Bilal, M. (2021). Detection of Parkinson's Tremor in Real Time Using Accelerometers. In *2021 IEEE 7th International Conference on Smart Instrumentation, Measurement and Applications (ICSIMA)*. [Link]
- Bakri, A. B., Adnan, R., & Ruslan, F. A. (2019). Wireless Hand Gesture Controlled Robotic Arm Via NRF24L01 Transceiver. In *2019 IEEE 9th Symposium on Computer Applications & Industrial Electronics (ISCAIE)*. [Link]

## Keywords
- Tremor
- Gesture robot
- Hand gesture
- Robotic arm
- Spherical gear
- Development and Prototyping

- Work by Tyler Porter
