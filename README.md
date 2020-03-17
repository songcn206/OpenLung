# Low resource Ambu-Bag ventilator

This project was jumpstarted by the COVID-19 global pandemic as a result of community discussion on a facebook group called Open Source COVID19 I created this GitLab project. More specifically in a discussion surrounding low cost AmbuBag based emergency respirators wherein prior solutions had been developed. The first from an MIT research group comprising of the following persons (Abdul Mohsen Al Husseini1, Heon Ju Lee1, Justin Negrete, Stephen Powelson, Amelia Servi, Alexander Slocum and Jussi Saukkonen). The second device from a Rice University Mechanical Engineering student group comprising of the following persons (Madison Nasteff, Carolina De Santiago, Aravind Sundaramraj, Natalie Dickman, Tim Nonet and Karen Vasquez Ruiz. Photo by Jeff Fitlow). This project seeks to combine and improve the efforts of these two projects into a more simple and reliable device that consists mostly of 3D printed parts.

# Reasons for using an Ambu-Bag

- Mass Produced
- Certified components
- Small and Simple mechanical requirements
- Previous research and testing in this area
- Adaptable to both invasive tubing and masks

# Project Requirements
- Project Requirements are listed [here](requirements.md)

# Project Progress (SCRUM)

![Current Mechanical Concept](images/CONCEPT_4_MECH.png)
### Current Design concept with known issues, Version 5 is currently in the works.

# TO-DO

- Design a more integral 3D printed actuation mechanism
- Spec a good low amperage, high torque DC motor
- Design or find and H Bridge rectifier circuit
- Spec an interface (LCD and Buttons)
- Spec feedback sensors for PEEP, low voltage, high and low pressure events. Hi guys. I'm a physician and create new medical devices like robotics/prosthetic limbs. I was asked to share some thoughts on this project. It's great to see such an interest in helping!
- Outline interface visually

## IN PROGRESS (Today, March 17, 2020)

- Organization of Repository structure
- Updated Ambu-Bag CAD model
- Interactivity outline
- Building communication bridge to the open source ventilator project Ireland
- Assessing current communication and deligation methods

## COMPLETED

-

## Next iterative improvements

- Perpendicular Motor/Drive shaft connection due to axial load issues
- Simplify transmission struction
- Further compacting of overall build

("I recommend adding a sensor between the bag and the tube leading to the patient that can measure the volume of air passing with each breath and the pressure left inside the bag. That way you can control Tidal volume and PEEP.
Unlike the Rice teams version it should not have the "adult, child, fast slow, etc" settings. As physicians we need very accurate control of these settings." -Jeff Ebin)
(Jeff- the Ambu Bags all have a sensor port for monitoring airway pressure. Either an analog gauge can be used or an electronic sensor installed. Does this produce the desired data?)

Suitable flow sensors: Sensirion SFM3000 200C, or the TSI 840523 - both are digital, and have simply o-ring coupled ports.

Here are links to information found:

* http://news.mit.edu/2010/itw-ventilator-0715
* https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf
* https://news.rice.edu/2019/05/01/student-invention-gives-patients-the-breath-of-life-2/
* http://oedk.rice.edu/Sys/PublicProfile/47585242/1063096
* https://www.instructables.com/id/The-Pandemic-Ventilator/?fbclid=IwAR2E_dr2P2oa6zYFJRhp58rctGrRDLG9AprXnsoJ2JTREiX16TMiPbK_LNs

