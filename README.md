Summary**
**The objective of this project was to design a smart thermostat prototype on a Raspberry Pi that can sense room temperature, switch heating and cooling indicators (LEDs), refresh a user display, and send temperature data via UART communication. The project addressed the issue of simulating an actual embedded thermostat system that can communicate with many hardware units through software control and state machine logic.

**What Did I Do Particularly Well?**
I integrated all the system components, sensor input (I2C), button-driven state management (GPIO interrupts), LCD output, LED feedback, and UART serial communication into a working, fully synchronized system. I’m especially proud of how cleanly the state machine handled transitions, ensuring the thermostat remained responsive and accurate throughout testing.

**Where Could I Improve?**
One place I can improve is in initial planning. I spent more time debugging button and wiring behavior because I didn't fully plan out hardware connections initially. In future projects, I would create a wiring diagram and modularize my code earlier to make development and debugging easier.

**What Tools and/or Resources Did I Add to My Support Network?**
  I expanded my support resources by using:
    •	Official GPIOZero and Raspberry Pi documentation
    •	Online forums like Stack Overflow
    •	Peer discussions and guided project walkthroughs

**What Skills from This Project Will Be Transferable?**
  Several skills from this project will transfer well into future work:
    •	Writing clean, event-driven code with hardware peripherals
    •	Building modular state machine architectures
    •	Managing real-time input/output updates
    •	Debugging embedded systems without dedicated hardware debuggers
    •	Documenting hardware-software interactions clearly for future team members

**How Did I Make This Project Maintainable, Readable, and Adaptable?**
  I employed descriptive function names, compartmentalized the code structure, and included debug print statements along the way. The code was constructed in reasonable sections (handling sensors, LED control, button interrupts, UART communication) so that future maintenance would be a breeze. The state machine pattern guarantees that implementing new states or outputs would be minimal restructuring.
