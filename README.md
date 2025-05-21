# What is FIR? Who is it for?

FIR (Fast Incident Response) is an cybersecurity incident management platform designed with agility and speed in mind. It allows for easy creation, tracking, and reporting of cybersecurity incidents.

FIR is for anyone needing to track cybersecurity incidents (CSIRTs, CERTs, SOCs, etc.). It was tailored to suit our needs and our team's habits, but we put a great deal of effort into making it as generic as possible before releasing it so that other teams around the world may also use it and customize it as they see fit.

![dashboard](https://github.com/user-attachments/assets/1f25b257-383c-45ef-870b-d32a12f52aed)

![incident details](https://github.com/user-attachments/assets/00d31c9d-d326-4087-8d8d-b61018369b89)

See the wiki for the [user manual](https://github.com/certsocietegenerale/FIR/wiki) and more screenshots !

# Installation

There are two ways to install FIR. If you want to take it for a test-drive, you can run FIR [using docker](https://github.com/certsocietegenerale/FIR/tree/master/docker)

If you like it and want to set it up for production, [here's how to do it](https://github.com/certsocietegenerale/FIR/wiki/Installation-on-a-production-environment).

# Technical specs

FIR is written in Python (but you probably already knew that), using Django. It uses Bootstrap and some Ajax to make it pretty. We use it with a MySQL back-end, but feel free to use any other DB adaptor you might want - as long as it's compatible with Django, you shouldn't run into any major issues.

FIR is not greedy performance-wise. It will run smoothly on an Ubuntu virtual machine with 1 core, a 40 GB disk and 1 GB RAM.
