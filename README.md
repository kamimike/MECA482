# Furuta Pendulum
#### Claire Christensen, Andrea Cortez, Keith Gramcko, Miguel Gonzalez, Yardley Ordonez, Spring 2020, California State University, Chico
-----------------------------------------------------------------------------------------
#### Table of Contents
- [1 Introduction](#1-Introduction)
- [2 Modeling](#2-Modeling)
  - 2.1 Sketch
  - 2.2 Nomenclature
  - 2.3 Equations of Motion
  - 2.4 Linear Space-State Model
- [3 Simulation](#3-Simulation)
  - [3.1 Script](#3.1-Script)
- [4 Implementation](#4-Implementation)
  
-----------------------------------------------------------------------------------------
## 1. Introduction
For Control system models dealing with inverted pendulums, one of the most utilized and studied profoundly has been The Furuta Pendulum. This model has been used for experimental analysis for the use of control theory. The Furuta Pendulum was introduced by Katsuhisa Furuta et. al. at Tokyo Institute of Technology. 

The pendulum consists of a rigid horizontal arm connected at one end to a motor. At its distal end is attached an encoder and a freely swinging arm in the vertical plane. The object of the control system is to cause the arm to remain standing. As mentioned before, The Furuta pendulum is of interest in the study of control theory because although it only has two degrees of freedom the related velocity vectors are quadratic due to the rotational nature of the system. This significantly complicates the related control theory.

### This document summarizes the theory, methodology, and calculations required to bring rise to the equations of motion, state-space representation, and subsequently control code via MATLAB and Simulink.
-----------------------------------------------------------------------------------------
## 2. Modeling
In order to model the Furuta Pendulum the team followed the provided Rotary Pendulum (ROTPEN) Workbook from Quanser. The following figures and equations are taken directly from the workbook. Necessary derivations are provided as prompted by the workbook in order to bring rise to the linear state-space representation.

 ### 2.1 Sketch
  <p align = "center">
   <img src = "doc/Pendulum.png" height = "360px" style="margin:10px 10px">
  </p>
  
  <p align="center">Figure 1: Furuta Pendulum Schematic Model</p>

In reference to Figure 1 the typical Furuta Pendulum is presented as such and the two angles show show the degree of freedom for the pendulum to maintain equilibrium. Analyzing the Pendulum model above, The Rotary's respective angle increases positively when it rotates counter-clockwise. The motor attached to the arm helps the arm achieve the assigned sign convention when voltage is positive. The pendulum link's respective angle also increases positively when rotated counter-clockwise. 

 ### 2.2 Nomenclature
  
  ![Equation](http://www.sciweavers.org/upload/Tex2Img_1588889804/eqn.png)

 ### 2.3 Equations of Motion
    
   First linear equation of motion with respect to the generalized forces acting on the   rotary arm:
    
  ![equation](http://www.sciweavers.org/upload/Tex2Img_1588889911/eqn.png)
        
   Second linear equation of motion with respect to the  generalized force acting on the pendulum:
    
   ![equation](http://www.sciweavers.org/upload/Tex2Img_1588889984/eqn.png)   
    
   Determinant for the equations of motion:
    
  ![equation](http://www.sciweavers.org/upload/Tex2Img_1588890088/eqn.png)
    
   Acceleration terms for the equations of motion:
    
  ![equation](http://www.sciweavers.org/upload/Tex2Img_1588890170/eqn.png)  
    
  ![equation](http://www.sciweavers.org/upload/Tex2Img_1588890250/eqn.png)  
    
 ### 2.4 Linear Space-State Model
    asdfasdfasdf
  
-----------------------------------------------------------------------------------------
## 3. Simulation

  asdflkjasdf;iasjd

3.1 Script

  as;dlkfjhasd;lkfjh

-----------------------------------------------------------------------------------------
## 4. Implementation

  a;ksldhjfasdkjfhaklsjd

