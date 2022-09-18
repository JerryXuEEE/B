---
title: Cirriculum
author: JerryXu
date: '2022-09-17'
slug: 
categories: []
tags: []
---

<h1 style = "color : gray; font-size: 50%;">This page is about my grades and curriculur acheivements</h1>

<h2>Page Navigation Menu</h2>
    <ul>
        <li><a href="/Cirriculum/#Grades/">Grades</a></li>
        <li><a href="/Cirriculum/#Faculty/">Faculty</a></li>
        <li><a href="/Cirriculum/#TDPS">Team Desin Project Skills(TDPS)</a></li>
    </ul>

<h2 id="Grades">Grades</h2> 
<h3>     GPA:3.78</h3>
<p> 
    Basic Cirriculum:
    <ul>
        <li>Calculus : 90 </li>
        <li>Probability Theory and Mathematical Statistics : 94 </li>
        <li>Programming : 86 </li>
        <li>Engineering English : 85 </li>
    </ul>
    <hr>
    Core Cirriculum: 
    <ul>
        <li>Digital Signal Processing : 89 </li>
        <li>Signals and Systems : 88 </li>
        <li>Circuit Anlysis and Design : 95 </li>
        <li><span href="/Cirriculum/#TDPS/">Team Design Project Skills(TDPS)</span> : 89 </li>
    </ul>
    <hr>
    Elective Cirriculum:
    <ul>
        <li>An Introduction to Cognitive Neuroscience : 89 </li>
        <li>The Anatomical Basis of Brain-Intellignece Congnition  : 90 </li>
        <li>Advanced Brain Magnetic Resonance Imaging and Analysis : 86 </li>
    </ul> 
    <hr>
<h3>Brief Introduction of Related Courses</h3>
<p>
    Above courses and grades shown are all directly related to the scientific research field. The results of other courses such as 
    Power Engineering(95), Embeded Processors(95) can be referred to <a href="#">the Official Transcript of UESTC</a> <!--此处需要成绩链接-->.
</p>
    <dl>
        <dt>Engineering English</dt>
        <dd>
              This course is aimed at presenting essential accedmic English skills, including presentation, reading, and writing.
            During this course, I was the TA and favoured by both the foreing teachers and UESTC teachers.
            In this course, we had a lot of report to write to simulate acedmic paper writing, and a lot of presentations to give to simulate conference report.
        </dd>
        <dt>Team Design Project Skills(TDPS)</dt>
        <dd>
              This is a challenged and fun course which will be specifically introduced in <span href="/Cirriculum/#TDPS/">the following article</span>. 
            Generally, we (a team of 10 Students) were required to design a <strong>robotic rover</strong> to complete a series of tasks, including line tracking, shape recognization, and placing a tennis ball. 
            In this process, I'm mainly responsible for the shape recognition module and machine vision, developed by Micro Python for OpenMV. 
        </dd>
        <dt>Overall Introduction of Elective Cirriculum </dt>    
        <dd>
            During year two and three, I have attended the a series of courses about neuroscience (8 in total). 
        These courses consist  anatomical and cognitive theories, EEG MRI and data analysis. I'm currently studying computational neuroscience.
        In these courses, we also have to complete a series of experiment in the labotory such as EEG Gonogo, MRI static data acquisation, and invasive electrode on mice.
        The teachers come from different fields, including EEG, MRI, cell, and have diverse backgrounds like cs, physics or psychology.
        Generally, these course combine scientific reseach and bsic theory to construct a basic understanding of neuroscience. 
        </dd> 
    </dl>


<h2 id="Faculty">Faculty</h2>

<h3>Essential Skills</h3>
<ul>
    <li>Programming Language: C,<span style="color:red ;"> Matlab</span>, Python, R, HTML</li>
    <li>Software: EEGLab, Brainstorm, E-prime, Github, Rstudio, Endnote & Latex</li>
    <li>Other Ability: Circuit Design and Built Up (Amp Circuit,Differential Circuit), Acquisation of Fundamental Semiconductor Devices (Diode, Transistor) </li>
</ul>
<h3>Scientific Research Skills</h3>
<p>
    Three years of research experience in the <em>Key Laboratory for Neuroinformation of Medical Education</em> 
    have equipped me with rigorous experimental thinking, research reviewing skills, and cooperative interdiscipline mind.
    I'm fully aware of the process and hardship of scientific research, more specifically, of publishing a journal article. 
    Still, I constantly find myself immersed in the process of learning new things, the amazement at novel discovery, and 
    the sense of achievement of making progress in scientific research.
</p>
    

<h2 id="TDPS">Team Design Project Skills(TDPS)</h2> 
<p>
    This course is aboout building an intelligent robotic rover by a team of ten students. This rover needs to complete couple of tasks in two patios. 
    In patio one, it has to follow the line, cross a bridge and stop exactly at the end point.
    In patio two, it has to recognize the shape from traingle, square, and circle, follow the route according to this shape, place a tennis ball in a basket, 
    and transmit a signal to the computer in the end.   
</p>
<!--此处需要插入一个视频-->    
<p>
    The video below shows the final demonstration of our rover.
</p>
<!--此处需要插入一个图片-->
<P>
    The image below shows the appearance of our rover during the shape recognition process.
</P>
<p>
    In this course, I'm mainly in charge of the shape recognition and machine vision. 
    In our rover, we decided to apply the OpenMv due to convenience and prtability. 
    The camera, OpenMV, was connected to the main board. As long as it detects the target and successfully recognizes its shape, 
    it return a value representign its shape to the main board through UART.
    This recognition module was developed by MicroPython and contains mainly four parts: preprocessing, filtering, detection and recognition, and average and communication.
    This module was developed and tested all by myself, in which I'd encountered with a lot of obstocles such as overflow, interferrence, connection issues.
    Overall, I was so delighed that this module successfully worked in the final demo.

</p>




