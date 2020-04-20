# Robot Data During Quarantine

#### Re-introduction to DataNBots

SOMA, San Francisco circa 2017, a mechanical engineer and a data scientist walk into a women of color breakfast, they hit it off immediately and become fast friends. After hours of conversation breaking down their experiences as women of color working in silicon valley they decide to share their knowledge with others via a podcast. There are so many topics to cover and in season one we focused on social issues of exclusion and academia, but we didn’t get around to talking tech. Welcome to season 2 of DataNBots, where we discuss the technical aspects of robotics and the data being used to create an intelligent robot brain. We thought long and hard about how to deliver this information to our community and encourage developers to create projects and companies in this space.

#### What is Robotics?

Robotics is an interdisciplinary branch of engineering composed of information engineering, computer engineering, computer science, mechanical engineering, electronic engineering and others. Robotics involves design, construction, operation, and use of robots. The goal of robotics is to design intelligent machines that can help and assist humans in their day-to-day lives and keep everyone safe. - Wikipedia

To build robot systems we need people with a variety of skill sets to plan, design and build robots which can interact with the human world. At the moment mainstream robots are confined to specific industries like manufacturing and logistics because these industries are so closely contained and there is not much risk involved in terms of human robot interaction. In order to have robots who can assist us in the real world we need to figure out how to develop the robot brain. We need to improve intelligent systems which can mimic the human brain, more generally we need to work towards artificial general intelligence. If machines are able to learn and think like humans we would not need to programatically design for every scenario a robot finds itself in and the robot would be able to infer from past experiences how to make decisions. Moving towards autonomous robots would enable humankind to use robots to solve some of humanity's most challenging problems and save human hours and lives. Some examples include rummaging through garbage dumps to separate trash and recycling products or medical robots who could perform complex surgical procedures given their ability to think through edge cases and come  up with new ways to handle them.

#### Robotic Internship Spotlight

##### Gaining Access 

As a sophomore mechanical engineering student, Camille had some familiarity with CAD and augmented reality. When she applied for a summer internship, the hiring manager noticed this and placed Camille on a machine learning team creating multi-task robots. This internship lasted two years and Camille learned a lot, we want to explore her experience during this internship and the technical aspects of her experience. 

##### Understanding the Task

The team Camille was working with sought to create robots which would work in an office and use a printer. When she onboarded with the team, they communicated verbally that they wanted her to build an end effector that is trainable, and can complete multiple tasks. An end effector is a device or tool that’s connected to the end of a robot arm, where the hand would be. The end effector is the part of the robot that interacts with the environment. Given the only project description she received for her project was this verbal instruction, she needed to do a lot of research and design in order to create a prototype and get all of the pieces working together. She wrote down in her design notebook the project description and began to design her project.

##### Designing the Project

The end effector needed a well defined task in order to build something which could showcase robotics in action. Camille decided to start with getting the robot hand to push a button on a printer. The robot would require cameras to understand where the robot hand was in relation to the printer and understand where the fingers were in relation to the button. The robot hand would also require sensors to understand what a successful push of the button looked like, simply tapping a button without causing an action is not a successful tap. This internship took place back in 2015 and there were not many advances in computer vision and deep learning models, so it was not yet an option to use deep learning algorithms to solve this. 

##### We had to bring Hardware and Software together

After Camille designed the project, another computer engineering intern was brought on board to help implement all of the design features and get the sensors working with the hardware. This was a manual process. The computer engineering intern needed to use the camera to capture images and then segment the images to identify objects in the frame which were significant like buttons on the printer or the printer itself. The engineer also needed to differentiate between the different types of buttons on the printer and the different portions of the printer which contain the buttons. These are all manual conditions which the engineer needed to implement in her code.

2015 vs. 2020

OpenAI released a learning dexterity project where an end effector robot hand can solve a rubics cube and they use deep learning and reinforcement learning algorithms to do this. You can read all about that in this blog post. https://openai.com/blog/learning-dexterity/

#### Company Watch

For this episode's company watch we want to highlight the company Covariant.AI which has been in the news for the last few months. Covariant.AI builds intelligent robots who work in manufacturing plants and can sort items coming down a conveyor belt into appropriate containers. Covariant is developing the Covariant brain a deep neural network programmed for multi-task learning. Unlike traditional robotics systems which have been explicitly programmed to complete one task over and over again, the covariant brain takes learning from multiple different robot examples and applies that learning to all the robot systems in the warehouse.

https://covariant.ai/
https://medium.com/covariant-ai/bringing-robots-from-lab-to-the-real-world-56062ee93dd5
https://www.wired.com/story/ai-helps-warehouse-bots-pick-new-skills/


#### Researcher of the Day


Our researcher of the day is Pieter Abbeel, a computer science professor at the University of California, Berkeley who also helps run the Berkeley Artificial Intelligence Lab (BAIR). Pieter completed his PhD in computer science at Stanford University and studied under professor Andrew Ng. Pieter is one of the founders of Covariant AI and a leader in the field of reinforcement learning and robotics. 
 
Heros of deep learning
https://www.youtube.com/watch?v=dmkPJpWCVcI
Deep learning for robotics
https://www.youtube.com/watch?v=WGza-jN4CZs&t=3681s
EECS - UCB
https://www2.eecs.berkeley.edu/Faculty/Homepages/abbeel.html


#### Failure Corner

The failure corner is the final portion of our podcast where we explore a specific failure which one of us experienced in our professional career and what we learned from it. We realized that many of our followers were a part of under-represented groups and because of this more likely to face discrimination and thus failure and we wanted to help our listeners plan for and more through it strategically.

During the end of 2017 Alivia was asked to join a data science team of PhD data scientists. This was a really exciting opportunity for her because she was so accustomed to working on software projects and never had the opportunity to design her own data science project. The company Alivia worked for was a small start-up in the finance space and Alivia’s project was called the food labeling project. Alivia was tasked with identifying trends in spending habits for financial transactions coming from the category labeled food. A large portion of the project involved labeling data. Alivia was tasked with defining 5 different subcategories of food transactions like groceries, fast-food, delivery apps, convenience stores, etc. 

Given so many members of this team were advanced data scientists and this was Alivia’s first data science project it was important for the senior member of the team to take the time to mentor Alivia so that she was able to model the project appropriately and understand the direction she sought to take. Alivia ended up leaving this project for another opportunity before being able to complete the project and was forced to present an incomplete project. In the weeks leading up to the presentation Alivia gathered her notes and attempted to summarize what she did in the project this far, but was unable to gather concrete statistical analytics about the transaction data given she hadn’t gotten that far in the project. Senior leaders advised Alivia to present analytic findings and in an effort to appease them she attempted to do so. 

Alivia’s presentation did not go so well, the leadership team were very critical of her findings, and noted how some of the metrics were wrong without looking at the underlying data. The process felt like a moment of failure. Alivia wanted to leave that internship with a memory of all of her learning and be able to hand off the project to someone else so that they would be able to continue with the work. In a moment of sadness Alivia left the office with defeat in her heart and called Camille to talk it over. They spoke about documenting work and how to properly turn over a project to another person. These were lessons very important for any new developer going into a new organization. Here are some of her takeaways from that experience:
Present the work that YOU did. Even if this does not seem satisfactory to your manager or team, you did some learning, planning and exploration and that is important to document and explain in your presentation.
Discuss next steps. This is where you can explain what you would do IF you had more time.
Document your work. Figure out where the team repository is where people collaborate and share their work and regularly push your code and documentation there. Many interns and new hires don’t know how or where to do this and it leads to other people taking credit for your work.





