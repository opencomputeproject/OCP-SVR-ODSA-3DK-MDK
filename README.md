# Material Design Kits (MDK) #
The materials and associated material properties used in the manufacturing ot the package interposer, substrates and associated connectivity components as well as the mechanical package, lid/stiffener and thermal dissipation structures (TIM, heat plate, heat sink and thermal cooling systems) needs to be carefully specified and us uses throughout the analysis, reliability and mechanical workflows is also required to ensure the design is manufacturable, reliable and meets the required performance requirements. 

Material Design Kits (MDK) is a novel approach to consolidate these material properties in a set of centralized design kit defined in a reusable, machine-readable format that can be consumed by the respective EDA workflows. The MDK library includes MDKs for the PCB, Package and Mechanical designs. The material properties in these MDKs are used for PCB and Package level Signal Integrity (SI) analysis, Power Integrity (PI) analysis workflows as well as the Mechanical design workflows. Historically, the design leads responsible for these workflows have worked directly with the material vendors using information often defined in PDF documents and entered these materials directly into their workflow scripts in an ad hoc manner.

Typical material properties include parameters such as:
* DK, DF, Dielectric, Surface Roughness
* Thermal conductivity
* Thermal expansion coefficients, ....

The analysis and reliability workflows also required detailed physical dimensions, shapes and manufacturing tolerances for the package substrate, interposer connectivity components which are defined in the JEDEC JEP30-P101 standard include in the CDX.

The design leads for the 3D IC Analysis, Reliability Analysis and Mechanical Design/Signoff analysis design tasks will work the chiplet, Interposer and AFB substrate vendors and the package assembly vendor(s) to define the material property requirements and capture the salient material properties required for the respective workflows. These models will be defined in a format that can be machine readable by the required workflows. To date, there is no industry format to define these material properties. The OCP/CDX working group is considering standardizing a common format. This MDK prototype can be used as an example to drive the development of a new, standardized MDK format.
