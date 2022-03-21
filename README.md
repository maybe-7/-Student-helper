# -

Software Project Proposal

Name：
Student Helper

Background:

1. The adjustment of school curriculum time makes students have a concentrated lunch time of only 30 minutes, which makes it difficult for students to choose their favorite dishes
2. None of the existing platforms in the market matches the life of students. Meituan and Eleme are the largest takeaway platforms in China, but they are rarely used by businesses in Macao. Aomi, as a local takeaway platform in Macao, has a large number of users but a high price and delivery fee
3. College students have many daily needs, including take-out, express delivery, purchasing and so on.

Purpose:

Our goal is to create a platform where students can use their free time to help each other.
1. Canteen reservation
Students' noon classes are tight, and the function of helping to buy meals is provided. Users can have meals quickly after class by filling in the time and address information, which greatly facilitates life
2. Supermarket daigou
We designed a supermarket purchasing service. When users do not want to go out or go to the supermarket, they can place orders on the supermarket purchasing page and fill in some relevant information, such as nickname, mobile phone number, harvest address, product information, etc. In this way, we can achieve the effect of shopping without going out.
3. Express delivery
The platform also launched the express pickup service. Ordinary users can submit the express to be picked up on the express pickup interface, fill in key information such as the express tracking number, and wait for the Courier to receive the order and send it to the designated harvest address.

Team Member:
The Team leader (PM) :
Wei Zihe
Responsible for the development of program framework and functional testing

Team members:
Wan Qining
Responsible for the code development and requirement document compilation of canteen ordering and supermarket purchasing
Zou Jiacheng
Responsible for the development of express pick-up and write the final instruction document

Design Model:

We use Spring model, And divide it into six phases. 
1.Definition and planning of the problem
In this stage, the demander and developer jointly determine the software development goals, and team members discuss and conduct feasibility studies to determine the feasibility of the project. At this stage, requirements documents and feasibility studies are generated.
2.Demand analysis
Conduct a detailed analysis of all requests from the demand side. This stage requires iterative discussion to ensure that user requirements are fully understood. Best written in a requirements analysis document.
3.Software design
According to the results of demand analysis, the whole software system is abstracted and designed, such as system framework design, database design and so on. Finally, an architectural design document is formed.
4. Program coding
Translate the results of architecture design and interface design into program code that the computer can run. Assign each code section to the appropriate employee.
5. Software testing
After the coding is complete, closely test the working results against the requirements analysis document together. If the tests find problems, they need to be fixed. After the final test is completed, a test report is formed.
6.operation and maintenance
After the software development is completed, the official operation is put into use. Follow-up maintenance is required to fix errors and add functions. The employee is required to provide instructions for delivery

Project Schedule:

Sprint1（3 weeks）
User story：
I hope that it is not convenient for us to take the real name of the student as the certification staff, but also to ensure the safety of the student.
As a merchant and delivery clerk, I hope to get in touch with customers in a timely manner, including some special requirements and needs, which can improve our work efficiency and customer satisfaction. We also hope that if a customer cancels an order maliciously, this behavior can remind us by reducing the reputation of the user account .

（The basic framework interface, database, registration and login functions of the platform are designed）

Sprint2（3 weeks）
User story：
As a student, I hope to see as much as possible the distribution business of restaurants or small shops near me, rather than the fact that the merchants are too far away or the merchants who are not open do not show clearly and affect the ordering situation in time. Lunch time is too short to choose the meal I want.

（The functions of canteen ordering and supermarket purchasing are designed. The two functions are similar and can be solved at the same time）

Sprint3（3 weeks）
User story：
As a student, I usually live in the school dormitory, and I need to collect express delivery to the special collection point in Zhuhai, I hope it can also have the function of taking express delivery on behalf of others. As for the payment method, I hope it can have a function similar to virtual currency, which can not only facilitate our payment, but also ensure the safety of our money compared with directly binding bank cards.
（Design the function of express delivery and virtual currency）

Sprint Planning: this time is used to update or confirm what the next Sprint will accomplish.
Daily Stand-up Meeting: We discuss the progress of the project in the group every night, and the PM summarizes this meeting.
Sprint Review: We will review the output after the sprint is over, in the end, the PM 
will give precise instructions on the next step. 
Sprint Retrospective: At the end of the sprint, we discuss what we did well or 
didn’t do in the process and specify a new improvement plan.

Difficulties and Challenges:

Convenience and security of the platform
This will include platform security and user security considerations
1. Use cookies to implement automatic login and cookie security protection
2. Use the email address and verification code to register
3. Session shopping cart
4. API security protection (prevent XSS attack, prevent CSRF attack, prevent request parameter tampering, prevent replay attack) 5. Using the interface of educational administration system, verify the validity of real name authentication

Follow-up maintenance of the platform
The main goal is to make the code clear and easy to understand
1. Detailed annotations of the code
2. Use enumeration classes to classify multiple states
