---
content_type: page
description: This section provides students work on two projects (De-mining Robot
  and Rescue Robot) during the term.
learning_resource_types:
- Projects
ocw_type: CourseSection
title: Projects
uid: 390862f9-b884-e6ea-7fb9-b4b16328d97c
---

Lab sessions are devoted to two projects. The first project, spanning Labs 1 through 4, is to build a de-mining robot. The second project, covering Labs 5 through 10, is to build a robot that finds and rescues disaster victims.

First Project: De-Mining Robot
------------------------------

The goal of this project to produce a robot capable of searching for hidden metal disks ("mines") in a open space. Students design and implement a search algorithm that lets the robot hunt autonomously, and when a mine is found to pause on top of it.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LABS
{{< thclose >}}
{{< thopen >}}
TOPICS
{{< thclose >}}
{{< thopen >}}
SUPPORTING FILES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 1 ({{% resource_link 4678d8ef-2d73-3e5c-6421-10c85bbaa7de "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Embedded Robot Controller, I/O Interface, and PWM Amplifiers
{{< tdclose >}}
{{< tdopen >}}
Lab Report Form ({{% resource_link d30774f2-5bdd-cc96-34b1-ee8180d84293 "PDF" %}})
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 2 ({{% resource_link ee37130b-ab52-ce2b-fafe-6c33543f002c "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Controller Software and Sensor Inputs
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 3 ({{% resource_link 65ee47d5-947f-135b-84ba-02cc61806bd7 "PDF" %}})
{{< tdclose >}}
{{< tdopen >}}
Implement Basic Sensor-Based Controls; Plan Strategy for De-mining Task
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab 4
{{< tdclose >}}
{{< tdopen >}}
Refine and Test De-mining Operations
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

_From the Fall 2004 Class - Videos of Final Demonstrations_

These short video clips of the De-mining Robot demonstrations illustrate variations in search patterns and in the ability to accurately detect a mine that's within range of the search.

The robot has a set of "whiskers" at its corners to detect walls and obstructions. The mine sensor itself has a fairly small radius of detection, about 2 inches, so the sensor must pass nearly over the top of the mine for it to be detected.

The robot has a failsafe control link that causes the robot to shut down if it loses contact with the student controller. While this was supposed to be a wireless connection, mysterious interference during the demonstration led most students to fall back on a wired control link.

*   Robot loses RF control link and stops ({{% resource_link "80791c4c-720a-4912-b3f7-5bb7403cb602" "MP4" %}})
*   Robot gets stuck in a control loop ({{% resource_link "d121919a-c734-4761-a652-bbe72ef39110" "MP4" %}})
*   Working RF control link; robot finds a mine ({{% resource_link "b165df6c-4554-4042-b2dc-8227d0110cb5" "MP4" %}})
*   Robot searches without success ({{% resource_link "0233c1cf-70f8-447d-8c11-e3ec02806739" "MP4" %}})
*   Robot finds a mine ({{% resource_link "59763d45-b67b-4091-9906-c6ce1f683374" "MP4" %}})
*   Robot finds two mines ({{% resource_link "6e20d099-31e3-44d8-a60c-c6f742262329" "MP4" %}})
*   Students try to keep the robot's RF link alive ({{% resource_link "2ddd32b4-0e46-4022-820f-82c7d0727528" "MP4" %}})
*   Robot with a novel search pattern ({{% resource_link "d07be948-ca6a-44b5-8867-ca84e2601697" "MP4" %}})
*   Robot misses a mine, then finds one ({{% resource_link "8bf6051e-a058-4b28-99a5-faf490c8872f" "MP4" %}})
*   Robot searches without success ({{% resource_link "76d066b4-70f0-40ab-b95d-d5a9f42a634e" "MP4" %}})
*   One of the "better functioning" designs, in terms of speed and search technique ({{% resource_link "3768114b-2304-4070-8036-e3ade43c1a5f" "MP4" %}})
*   Robot searches in a spiral out from center ({{% resource_link "9df688e9-891e-441c-aa01-80abe972b939" "MP4" %}})
*   Robot finds a mine; very quick reverse after pause ({{% resource_link "190cf5b4-e680-43cb-b3d1-f1fec06b538d" "MP4" %}})

Second Project: Rescue Robot
----------------------------

This past year will be remembered for its many severe natural disasters, both overseas and here in the United States. One of the most compelling applications for robotics technology is to develop rescue robots that might be able to save lives after such catastrophic events. Students will be given the challenge of developing autonomous mobile robots that can perform navigation and manipulation for a disaster response rescue mission. Each robot has a manipulator arm mounted on a moving platform guided by an on-board Linux computer and various sensors, including a laser range scanner for detecting obstacles and "houses" where victims (dolls) may be located. Once located, the robot should retrieve the victim and take it a hospital treatment center.

Description of the Rescue Robot Project ({{% resource_link a006e63b-1be4-bb72-5b78-adb71bac5830 "PDF" %}})

Video of Final Demonstrations ([MOV - 13.3 MB](/ans7870/2/2.12/f05/projects/rescue_robot.mov)) (Courtesy of Phil Shaltis. Used with permission.)