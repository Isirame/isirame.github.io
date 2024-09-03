---
title: Research
permalink: /research/
toc: true
toc_sticky: true
layout: single

feature_row:
  - image_path: /assets/images/RobUST_Transforms.png
    title: "RobUST transforms SCI rehabilitation"

feature_row2:
  - image_path: /assets/images/Motor_Assembly.png
    title: "Motor Assembly"
  
feature_row3:
  - image_path: /assets/images/Rotating_Bearing_Assembly.jpg
    title: "Rotating Pulley Assembly"


---

## Robotic Exoskeleton for Postural Control Training of Spinal Cord Injury Patients

The Robotic Stand Trainer (RObUST) is a cable-driven robotic exoskeleton for postural control training of spinal cord injury (SCI) patients. It is a fourteen motor, four actuator system that can provide planar control on a subject's trunk, 6 degree-of-freedom control on their pelvis, and pull forces on each knee that transforms postural control training of SCI patients.


{% include feature_row id="feature_row" type="full"%}
<!--![CAD model of Stand Trainer](/assets/images/RobUST_Transforms.png)-->

With a group of colleagues at the ROAR Lab, I designed, and built this device along with its software control system. 

<div class="video-container">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/LRBBPVcUZ24?si=jjPkFBORT1jL9vf_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

RobUST is programmed using a LabVIEW real-time controller that operates on both a host computer and a PXI (Peripheral Component Interconnect eXtensions for Instrumentation) remote controller, creating a robust dual-controller setup.

![RobUST Architecture](/assets/images/RobUST_Architecture.png)

- **PXI Remote Controller**: This controller handles critical real-time tasks:

  - **Low-Level Current Control**: Precisely regulates the current supplied to the motors to ensure accurate torque and movement.
  - **High-Level Force Control and Cable Tension Planning**: Manages overall force application and plans the tension in the cables, ensuring smooth operation and safety.
  - **Load Cell Sensor Integration**: Incorporates data from load cells to monitor forces or weights, which is essential for maintaining system stability and performance.
  
- **Host Computer**: Manages user interface and control functions, enabling direct user interaction and communication in addition to interfacing with the positioning system. This includes graphical user interfaces (GUIs) for real-time monitoring and command inputs.

This configuration leverages the strengths of both controllers: the PXI system handles real-time, computation-intensive control tasks, while the host computer focuses on user interaction and overall system coordination, maximizing both responsiveness and reliability.

![Architecture of RobUST Controller](/assets/images/Controller_Design.png)

I was a critical part of the construction team and in designing elements of the device:

![Construction of RobUST](/assets/images/Stand_Trainer_Build.jpg)

Some parts that I designed and fabricated:

{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="right" %}

---
<br><br>

## Transcutaneous Spinal Cord Stimulation
Transcutaneous spinal cord stimulation is a non-invasive analog to epidural stimulation which has the potential to activate neuronal circuitry below a spinal cord injury lesion, circuits which remain intact but can no longer efficiently receive supraspinal input. I led the investigation of the use of TSCS at the ROAR Lab, concluding in [studies](https://www.cambridge.org/core/journals/wearable-technologies/article/effect-of-transcutaneous-spinal-cord-stimulation-on-the-balance-and-neurophysiological-characteristics-of-young-healthy-adults/23F07B0A79BF95F29F0A030FC8B489AC) that showed that electrical stimulation increases muscle activation during functional tasks in healthy subjects.

We measured H-Reflexs:
![H-Reflex Measurements](/assets/images/H-Reflex.png)

And post activation depression:
![H-Reflex Measurements](/assets/images/Post activation depression curves.png)


<!-- ### Exploring the effects of TSCS applied alone 

### Exploring the effects of TSCS applied with activity training -->


## Motion Tracking with IMUs (Xsens)



## TPAD

![Schema for TPAD Experiment](/assets/images/Stroke Study Schema.png)

![Stroke Study Subject](/assets/images/Fully Instrumented Participant Stroke Study.png)


