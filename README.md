<!-- omit in toc -->
# ARM Architecture
<!-- omit in toc -->
## Table of Contents
1. [ARM Overview](#arm-overview)
2. [AMBA Overview](#amba-overview)
3. [Why Do We Need On-Die Interconnect?](#why-on-die-interconnect)

<br/>

<!-- omit in toc -->
## <a name="arm-overview"></a> ARM Overview
ARM architecture is a widely used and highly popular architecture for designing efficient and power-effective processors. It offers a range of processors suitable for various applications, from small embedded devices to high-performance computing systems. At a high level, ARM processors are based on a load-store architecture, where data processing occurs between registers and memory. They employ a pipeline structure that enables concurrent execution of multiple instructions, resulting in improved performance.

ARM architecture is characterized by its emphasis on low power consumption, scalability, and versatility. It provides a wide range of processor cores, such as ARM Cortex-A, Cortex-R, and Cortex-M, each optimized for specific application domains. The architecture supports various features, including instruction sets, memory management units, and co-processor interfaces, to cater to different requirements. ARM processors also leverage advanced techniques like branch prediction, caching, and out-of-order execution to enhance performance. Additionally, ARM's architectural licensing model allows for customization and integration of ARM processors into diverse system-on-chip (SoC) designs, enabling efficient and tailored solutions for specific applications.

Overall, the ARM architecture stands as a dominant force in the semiconductor industry, powering a vast array of devices and systems. Its blend of performance, power efficiency, scalability, and flexibility has made it a go-to choice for designers seeking high-performance computing solutions with low power consumption and adaptable architecture.

<p align="center">
  <img src="./images/arm_architecture_high_level.png" alt="ARM Architecture">
  <br>
    <a href="https://en.wikipedia.org/wiki/ARM_architecture_family">ARM Architecture Family Wikipedia</a>
</p>


<br/>
<br/>


<!-- omit in toc -->
## <a name="amba-overview"></a> AMBA Overview
Advanced Microcontroller Bus Architecture (AMBA) is a SoC bus architecture for 
<br/>
<br/>

<!-- omit in toc -->
## <a name="why-on-die-interconnect"></a> Why Do We Need On-Die Interconnect?
The on-die interconnect is a vital component of microprocessors and System-on-Chip (SoC) designs. It serves as the communication infrastructure that connects various components, such as the CPU, memory, cache, and peripherals, within the chip.

By having the interconnect on the same chip (on-die), the communication between different components becomes more efficient. It eliminates the need for off-chip communication, which can introduce significant latency and bandwidth limitations. With on-die interconnect, the data can be transferred quickly and directly between components, minimizing delays and improving overall system performance.

Furthermore, the on-die interconnect enables better energy efficiency. By reducing the need for off-chip communication, it helps minimize power consumption associated with data transfers. This is especially important in mobile and battery-powered devices where energy efficiency is crucial.

Another advantage of the on-die interconnect is its scalability. As the number of components and the complexity of designs increase, the interconnect allows for seamless integration and communication between them. It provides a flexible and scalable infrastructure that can accommodate future enhancements and changes to the chip architecture.

Overall, the on-die interconnect plays a critical role in optimizing performance, reducing latency, improving energy efficiency, and enabling the seamless integration of components within a microprocessor or SoC design.
<!-- omit in toc -->
<br/>
<br/>

## Verilog Training
1. [HDLbits](https://hdlbits.01xz.net) 
2. [chipdev.io](https://chipdev.io/)

<br/>
<br/>

## References
1. [SoC Achitecture: ARM/ AMBA by Tae Hee Han, Sungyunkwan University](./resources/soc_archirecture_arm_and_amba.pdf),  Original URL: http://contents.kocw.net/KOCW/document/2014/sungkyunkwan/hantaehee/4.pdf
2. [Understanding AMBA Bus Architechture and Protocols](https://anysilicon.com/understanding-amba-bus-architecture-protocols/)
3. [AMBA - Advanced Microcontroller Bus Architecture](https://www.youtube.com/watch?v=CbdjCKdVsG0)