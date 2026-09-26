# PillVision

## Team Members

| Name | Major | Email |
|---|---|---|
| Daniil Goncharuk | Computer Science | gonchadl@mail.uc.edu |
| Nekruz Ashrapov | Computer Science | ashrapnz@mail.uc.edu |
| Max Sharipo | Computer Science | tsvyetmx@mail.uc.edu |

## Advisor

**Name:** Dr. Hrishikesh Vinayak Bhide  
**Department:** Department of Computer Science  
**Email:** bhidehk@ucmail.uc.edu  

---

## Project Description

PillVision is a computer vision-based system designed to count pills more accurately in realistic situations. One of the main challenges we want to focus on is when pills are touching, partially overlapping, or grouped closely together, since this can make counting them with a camera more difficult.

Our idea is to use computer vision to detect and count the pills, while also using a small amount of controlled vibration when needed to help separate larger clusters. We do not want the system to depend on fully separating every pill before it can count them, so part of the project will be figuring out how well the vision system can handle pills that are still touching or overlapping.

We are also keeping the camera setup flexible for now. We may start with one camera and later test whether using more than one camera improves the results enough to be useful.

Another feature we may explore is checking whether any pill looks different from the rest, such as a wrong, broken, or damaged pill.

---

## Topic Statement

### Context

The intended application area for PillVision is pill counting in pharmacy-related environments, where multiple pills may need to be counted accurately and efficiently.

### Problem Statement

Pills may be positioned close together, touching, partially overlapping, or clustered, which can make computer vision-based counting more challenging. A system that depends on complete mechanical separation of every pill may also require additional hardware and complexity.

### Proposed Direction

The team proposes developing a computer vision-based system that detects and counts pills from camera images. Controlled minimal vibration may be used to reduce severe clustering, while vision algorithms will be used to handle remaining touching and partially overlapping pills. The team may also investigate visual verification features for identifying pills that differ from the expected group.
