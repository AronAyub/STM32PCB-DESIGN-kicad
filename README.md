# STM32PCB DESIGN kicad
 Design BluePill using Kicad
 - This is just summary approach, this course is availlable at a cheap price for your learning.


Steps:
1. Download lattest [Kicad v.6](https://www.kicad.org/download/)
- We shall refer to [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)

2. Load the component and start by configuring the power section.

## Power Section Design
- This involves Filtering VCC power
- Separating Analog and Digital power.
- The correct grounding


![power](https://user-images.githubusercontent.com/55284959/227529885-225649b5-639e-46bf-8c0d-83da0afab5b8.png)

## Booting Circuit
- This involves right configurations to the BOOT pin.
![bootig circit](https://user-images.githubusercontent.com/55284959/227792287-02d3711d-ed99-4179-b94b-123ae421c8e9.png)

## STM32 PiN Assignment'
- In this section you learn how to use STM32BubeIDE and how to configure pins in it
- This is the interface of STM32VubeIDE
![st32 pin assignment](https://user-images.githubusercontent.com/55284959/227793444-6ea098fb-3da8-4fce-8195-56b7fb9d963a.png)
- In STM32CubeIDE  we are configuring all pins assignments.\

## Complete Pin Integration.
- To understand step-wise why these values have been selected, this is well explained.

![Interface connected](https://user-images.githubusercontent.com/55284959/227796923-d08df17c-bed7-4a31-8114-57530d352165.png)

![final pin mapp](https://user-images.githubusercontent.com/55284959/227798626-590bab36-c62a-4009-a739-b1afdccc5ad8.png)

## Power Circuit Integration
- to understand how this is done, it is explained as well
![WITH PWRCT](https://user-images.githubusercontent.com/55284959/227797394-b4c5fcc8-6f3d-4862-88ce-3a9eb8ea48a8.png)

## Adding more periferals and pin extensions
![interface config](https://user-images.githubusercontent.com/55284959/227797578-0ceeebe0-02f7-40e9-9dea-04f5be188818.png)


## Annotate your schematic to assign each component a number
- can manually alocate or use Kicad tool to do it
## Check for Electrical Rules
- Power flag - is associated with defining power source, solve by using a power flag -let kicad know it is a power source.
![check e rules](https://user-images.githubusercontent.com/55284959/227940048-6da257ca-e85f-4477-a1a9-3c6b57ebda1d.png)

## Assign footprint
- Each componet have to be associated with a footprint
- Can choose to create your onw
- can opt to use default footprints
- If no 3D models for the footprint, there is a wasy to create them.

## Organize and arrange components in PCB Layout
-  This depends on Signal integrity 

## Route your PCB
- this requires some keen techniques. 
<img width="951" alt="routing " src="https://user-images.githubusercontent.com/55284959/228350000-63c5604f-59ad-4927-9a5f-8268cad67c31.png">


## Final View
- 3D view can help in this 
<img width="923" alt="3D" src="https://user-images.githubusercontent.com/55284959/228350573-650d0386-40f5-415a-99c7-f0faad13c7f7.png">

## Generate Output for Fabrication 
- final stage to fabricate your PCB design
- generate gerber files 
- Suggested manufacturers .

**To learn this step_Wise How to Design your IoT PCB boards, from basics, to intermediate and advanced contanct me**
