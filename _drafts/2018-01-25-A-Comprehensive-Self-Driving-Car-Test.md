---
layout: post
title: A Comprehensive Self-Driving Car Test
external-link: https://m.cacm.acm.org/magazines/2018/2/224621-a-comprehensive-self-driving-car-test/fulltext
image: https://cacm.acm.org/system/assets/0001/6357/092012_Vinton-Cerf1.large.jpg?1476779472&1403809775
description: Communications of the ACM, Vol. 61 No. 2, Page 7 
--- 
Communications of the ACM, Vol. 61 No. 2, Page 7 10.1145/3177753 Comments
￼
Vinton G. Cerf
Every few years, I have to pass a test from the Department of Motor Vehicles to drive my car in Virginia (and the rest of the U.S.). Shouldn't a self-driving car be required to do the same thing? Actually, the Waymo self-driving car passes a more comprehensive set of tests than humans do, as I found out after asking about its safety report.a Disclaimer: I work for Google, which is an Alphabetb company and Waymo is a sister company.
What struck me as interesting about Waymo's approach to safety is the scope of the design and testing regime that informs the company's assessment of the vehicle's safety. For such vehicles to work at all, a raft of sensors is needed to provide the vehicle's software with situation awareness at all times. Unlike human drivers, the self-driving car can continuously sense its 360-degree surroundings using multiple sensors: color-aware visible light cameras, radar transceivers, three lidarc transceivers (short, medium, and long range), audio detectors, and GPS receivers. Moreover, a great deal of redundancy is built into the system to provide back-up capacity in the event of various failure scenarios. The list is long: back-up braking, computing, steering power, collision detection and avoidance systems, and redundant inertial measurement systems.
The Waymo vehicles have accumulated four million miles of driving on city streets in California, Washington state, Arizona, and Texas. Each day, as many as 25,000 virtual Waymo self-driving vehicles drive up to eight million miles in simulation for an accumulated total of 2.5 billion simulated miles during the course of self-driving car development.
From the safety report: "Waymo has set up a private, 91-acre, closed-course testing facility in California specially designed and built for our own unique testing needs. This private facility, nicknamed "Castle," is set up like a mock city, including everything from high-speed roads to suburban driveways to a railroad crossing. Our team uses this and other closed-course facilities to validate new software before it's released to our fleet of vehicles on the road, and also to stage challenging or rare scenarios so our vehicles gain experience with unusual situations. On our closed course, we're able to conduct thousands of "structured tests" that recreate specific scenarios for learning and testing. To power our simulator, we've developed more than 20,000 simulation scenarios at Castle. Each recreates a driving situation we want to practice—an aggressive driver barreling out of a driveway, or a pedestrian suddenly emerging from a parked car—that might take hundreds of thousands of driving miles to encounter on public roads. We've staged people jumping out of canvas bags or portable toilets on the side of the road, skateboarders lying on their boards, and thrown stacks of paper in front of our sensors. This "structured testing" is key to accelerating the progress of our technology and ensuring safety of our vehicles in both everyday and challenging driving situations."
The simulation capability is particularly important since it allows Waymo to test any new software or hardware releases with large numbers of scenario variations in parallel that would take far too long to test in the real world. The real-world tests provide detailed sensor data, which can be recorded, played back in simulation, and artificially varied to create comprehensive situational testing.
While the U.S. Department of Transportation has recommended that self-driving vehicles should be able to demonstrate at least 28 core competencies adapted from research by California Partners for Advanced Transportation Technology (PATH) at the Institute of Transportation Studies at University of California, Berkeley, Waymo has identified a total of 47 core competencies and endless variations within them for validating safety. The cars can continuously test the condition of all onboard systems and have been designed to assume a minimal risk condition (NASA calls this "safe mode") if a hazardous situation develops.
Care has been given to assure the vehicles can detect and react properly to the presence of emergency vehicles and provision has been made to allow the cars to interact with law enforcement and other emergency response personnel as well as communicating with the passengers on board the self-driving cars. I don't know about you, but I am really impressed by Waymo's comprehensive focus on safety and the implications for reducing the hazards of human-driven cars!
Author
Vinton G. Cerf is vice president and Chief Internet Evangelist at Google. He served as ACM president from 2012–2014.
Footnotes
a. https://waymo.com/safetyreport/
b. https://abc.xyz/
c. "light radar"
Editor's Note: See another side of the sensor story on p. 20.
The Digital Library is published by the Association for Computing Machinery. Copyright © 2018 ACM, Inc.
No entries found

