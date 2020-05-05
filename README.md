# Data Incubator Fellowship Capstone Project Pitch

## Introduction
Education is changing rapidly all around the world and have never had the magnifying glass on it quite like in the midst of the COVID-19 pandemic.  This Fall, for example, what will students, parents, faculty, and university administration demand of their employees and customers?  Will classes be held on site or remote?  This is a great opportunity for Massive Open Online Courses (MOOCs) to reach a broader audience.  For this to happen, though, we need the right tools to allow the average American to take a good hard look at these alternative forms of education. 

My project will serve as the seed to a grander medium to long term vision to change how we think about education.  While I will begin by looking directly at university-level education and post-graduation job searching via Coursera and LinkedIn, as a start, the same approach could potentially be applied to the K-12 level (e.g., to help places like [Acton Academy](https://www.actonacademy.org/), the tech-school/community college level (e.g., to help initiatives like the [New Collar Workforce Network](https://newcollarnetwork.com/), not to mention to many other MOOC platforms and bootcamp programs (like the [Data Incubator](www.thedataincubator.com)!). 

The idea is this: create a google for MOOCs + career alignment; think “moocle,” but with a personalized twist that sites like [MOOC List](https://www.mooc-list.com/) do not have.  Parents, students, and educators alike need a place where they can go to figure out the best path forward. 

## Research Question
The research question that I want to answer is:  

> Is there a clear path of least resistance and lowest cost/highest effectiveness (cost and effectiveness metrics TBD) that will allow for a customized academic program of study, *aimed at a specific job title and locale*, capable of adapting to the rapidly expanding and changing job and  ed-tech marketplaces and, that leverages remote learning, and can be used by students, parents, educators, and employers alike to choose a locale, an industry, and a job title?

Imagine if we could create custom process flow diagrams like [this one](https://mechanical.mines.edu/wp-content/uploads/sites/98/2019/07/BSME-Flowchart-2018-19.pdf), which is for a BSME @ the Colorado School of Mines.

Even better, imagine if every young boy and girl and  interactive graph networks with many possible paths to choose to the same end result, which can be visualized similar to the D3.js network shown [here](https://youtu.be/Mae3uR9HSjQ) from a former Data Incubator alum, Eric Hoppmann, from a not entirely unrelated project.

### Example: Mechanical Engineering Jobs
Take, for example, the mechanical engineer of today.  He might need to know much more than a classic mechanical engineering degree will teach him; this of course, depends on the type of job that he hopes to get.   

A [mechanical engineer at Apple](https://www.linkedin.com/jobs/search/?currentJobId=1843228084&geoId=106758460&keywords=display%20mechanical%20engineer&location=Cupertino%2C%20California%2C%20United%20States), for example, needs to have not only classical ME skills like CAD and tolerancing, but also needs a deep understanding of product development across multiple CAD platforms, multi-physics simulation, product and experimental design, and optimization.  The successful candidate will also be able to demonstrate a systems-level understanding of, for example, an LCD module for MAC displays.  For this he or she must be well-versed in certain aspects of electrical engineering, computer engineering, and computer science that are important for consumer electronics design. 

However, a mechanical engineer down the street at your local machine shop might not need nearly the level of expertise in areas related to electronics, computer engineering and computer science, but might need to be well-versed in operations methodologies from a business perspective, and in emerging technology areas that might affect his job; for example, like 3D printing or robotic automation. 

There are no programs at universities that will force a student to go through the process of learning the necessary skills to be able to complete either one of these jobs.  As the world becomes more complex, we need better tools to help students who don’t have access to multi-faceted internship and co-op programs to be able to compete, remotely.  We must try to synthesize what a young person needs to aim at to the minimally-sufficient amount of complexity, for the student, at that point in their career trajectory.  We must also connect these recommendations to data sources that update with emerging markets and global economic shifts (i.e., COVID-19).

## How will I do it?
My project will focus on a good first step to solving this problem; namely, given two constraints, that I will choose an industry and a job title (say Electrical/Electronic Manufacturing and Display Mechanical Engineer), then my program will develop the minimally-sufficient number of courses that you need to take to match the job description. 

I will scrape LinkedIn for industry and job titles, and I will scrape Coursera to be able to recommend courses.  I also aim at developing a process-flow diagram for the student, so that they have something to aim at. 

Need to create some sort of interactive tool and dashboard that pits supply (courses and certificates that can be received via MOOC offerings like those on Coursera) versus demand (Jobs available in particular markets, like those on LinkedIn).  Essentially, I want a recommender system that provides a education-process-flow; I’d like to do this in the form of a D3.js graph network (similar to https://youtu.be/Mae3uR9HSjQ) 

In order to make this project most relevant to me and my region, I will investigate jobs, locales, and companies where I've historically found myself and may potentially find myself.   will analyze data from that particular city, and if not I will analyze both my current home base of Raleigh, NC; potential future home base of Austin, TX; along with my former hometown of Dayton, OH.  If I find myself taking part in the in-person program, I will include the city in which I'm residing as well. 
 
Further, to make sure that I'm making this as relevant to my own life and the lives of those in my network as possible, so as to create maximum impact, I will focus on two broad categories of jobs; 3D printing (additive manufacturing), and data science roles.  I will need to work with Data Incubator instructors and fellowship cohort members to further develop and refine how exactly to break this down into measurable job titles in specific industries that will span across regions, but I'm certain that I can create a proof-of-concept as long as I appropriately bound the design space that I'm looking at and explicity state my assumptions. 

intuitive dashboard-type approach 

I will use Allegro.ai’s TRAINS-server platform to develop the plumbing necessary to not only manage my data, but also my machine learning model development and iterations. 
