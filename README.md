Electronics eCommerce shop with admin dashboard in Next.js and Node.js is a free eCommerce store developed using Next.js, Node.js and MySQL. The application is completely built from scratch(custom design) and completely responsive. Singitronic is a modern online shop that specializes in selling all types of electronic products. The goal of the project is to create a modern web application by following key stages in software engineering. I have created this online shop as part of my college exam in software engineering with Bojan Cesnak - @cesnak02. Together with the application, we created detailed 40 pages software engineering documentation. We will describe the main parts of the documentaion in the repository description. Main resource for the software engineering documentation is the book „Razvoj aplikativnog softvera“ by Singidunum University professor Violeta Tomašević. Also, college lectures by Violeta Tomašević and Petar Kresoja helped us a lot with the implementation of the application.

2. Software engineering process
During the design and modeling of the software, we decided to use the cascade model(waterfall model). We decided on it considering its simplicity, easy project monitoring and easy application of the model. The cascade model is probably the oldest published model. It was first published in 1970 and represents a high level of abstraction. The stages in the model are connected in cascade, and the model itself is organized so that the next level is passed only after the completion of the previous level.

2.1. Defining milestones
Milestones are key events in the project that show us by what date something must be finished. At this stage, we defined our milestones for every stage in our software engineering process.

2.2. Plaky - Project management application
The Plaky application was used for project management and project tracking. It is a free application that facilitates collaboration between team members and enables easy export of project reports in one click.

3. Requirements analysis
3.1. Software requirements specification
At this stage we defined all our functional and non-functional software requirements regarding to the whole application. Also we defined requirements that define the connections of the system with the environment and performance requirements that the system should meet.

3.2. Modeling the system with a use case diagram
The Use Case Diagram represents a detailed description of the functionality of the system in different situations. It describes the steps and actors involved in each situation. The use case diagram is used as a basis for further design, implementation and testing of the software.

4. System design
System design is the software engineering stage that transforms concepts and requirements into tangible software structures. It is the strategic process of defining the architecture, components, and interactions of a software system to fulfill specific functional and non-functional requirements. In this stage we wrote about the type of system architecture. We defined our front-end and back-end and we wrote about structure of front-end and back-end in our application. We defined our data structures, database structures and important types in our application.

5. Software implementation
Software implementation is the process of converting a software design into a functional software system. This is where all programming should begin. When you are in the software implementation stage, it is important to take care of the internal documentation. This documentation includes headers and comments that provide basic information about the component and explanations of specific parts of code. Thanks to these elements, we are easier to manage in code and we better understand what we have done, which contributes to more efficient work and maintaining software projects.

6. Testing
Testing is a formal process that is performed by the testing team with the aim of determining the logical correctness and purposefulness of the tested program. The importance of testing is great because it significantly reduces the losses that software companies have due to errors and failure of software incurred after its delivery to the customer. We have done the entire testing process manually and documented everything in detail.


The test scripts represent the instructions from which it is clearly seen as a step by step how the testing was performed. They provide full control over testing, so, if some errors or cancellation occurs, testing conditions can be repeated and the system again lead to that error or cancellation. This is necessary to establish the cause of the problem. As the above image shows, we documented each our test example in terms of test ID, input data, instruction, expected result, actual result, additional comment, component, method and testing technique. Currently, our test script has over 350 manually tested examples.

During the software testing process, we documented each error found in the error report form. As shown in the image above, each error has its own unique error ID and a detailed description of the error containing: date of identifying an error, date of troubleshooting an error, error priority, type of error, file name, testing phase.

6.1. Ad hoc testing
The first step in software testing after each new added functionality in our application was ad hoc testing. The ad hoc testing takes place in an unofficial atmosphere. The developer presents the code to the rest of the group and then the discussion occurs. The members of the group ask questions, the developer corresponds to them, together analyze individual implementation aspects that they consider significant and try to find mistakes. We have applied this method by examining the code after each new added functionality and had long discussions about it and the potential problems that may occur.

6.2. Component system hierarchy
The component system hierarchy of the application components is a complete sketch of all components in our application created in Figma design tool. This sketch is very important to us when testing, because it represents an insight into the order of the component testing. The below image represents our component system hierarchy from the bird eye view:

application component system

6.3. Unit testing
Unit testing for our application includes the process of testing individual functionalities or application components, to ensure each of them work properly independently. The goal of unit testing is to identify and correct errors in the early stages of development, increase the reliability of code and facilitating future application maintenance.

Condition coverage

6.4. Integration testing
In integration testing, we used the approach "Integration from the bottom to top". This is very used approach in integration testing. This method starts from the components of the system organized in the hierarchy on which the main program is located. Testing starts by unit testing all components located at the lowest level in hierarchy. The components are then tested at the next level that calls previously tested components.

6.5. End-to-end testing
End-to-end testing is the highest, final level of testing. It is checks whether the system, as a whole, acts in accordance with the specification of the requests set by the customer. Since most functional requirements have already been verified at lower levels of testing, now emphasis is on non-functional requirements, such as speed, reliability, efficiency…

6.6. Error records at a specified time interval
During testing, we recorded the found mistakes by days. The next diagram helped us know how to know how our testing progresses.

6.7. Analysis of errors found
During testing, we also conducted the error report form that we have already mentioned in the introductory chapter on testing. This document has helped us significantly in order to document all the most common types of mistakes in our application.

Singitronic – Key features
Singitronic is Next.js and Node.js full-stack e-commerce website with a free source code. Our application comes with the fully functional admin panel and it is fully open-source. Our free online store website is completely responsive and manually tested. You can use our e-commerce project as a template or boilerplate for you next project. Our ecommerce shop template and Next.js ecommerce theme is fully customized for all your needs. It is available for free download and can be used as an ecommerce example for all your future projects.

Is Next.js good for eCommerce?
Next.js is currently one of the best ways for developing custom eCommerce solutions. It’s benefits include improved performance, SEO-friendliness, easy development and deployment, excellent developer experience, and the ability to handle versatile and scalable projects. By leveraging Next.js, developers can create compelling web applications that deliver an exceptional user experience while maintaining optimal performance.

Instructions
To run the app you first need to download and install Node.js and npm on your computer. Here is a link to the tutorial that explains how to install them: https://www.youtube.com/watch?v=4FAtFwKVhn0. Also here is the link where you can download them: https://nodejs.org/en

When you install Node.js and npm on your computer you need to download and install MySQL on your computer. Here is another link to the tutorial which explains how you can download and install MySQL on your computer: https://www.youtube.com/watch?v=BxdSUGBs0gM&t=212s. Here is a link where you can download MySQL: https://dev.mysql.com/downloads/installer/

This step is optional, but highly recommended if you don't have a database management app. Because HeidiSQL is beginner-friendly and very easy to use than other database management options. Here is a link to the tutorial which explains how to download and install HeidiSQL: https://www.youtube.com/watch?v=oJ24MyLeiPs and here is a link where you can download it: https://www.heidisql.com

When you install all the programs you need on your computer you need to download the project. When you download the project, you need to extract it.

After you extract the project you need to open the project folder in your code editor and in the root create a file with the name .env.

You need to put the following code in the .env file and instead of username and password put your MySQL username and password:

DATABASE_URL="mysql://username:password@localhost:3306/singitronic_nextjs"
NEXTAUTH_SECRET=12D16C923BA17672F89B18C1DB22A
NEXTAUTH_URL=http://localhost:3000
7. After you do it, you need to create another .env file in the server folder and put the same DATABASE_URL you used in the previous .env file:

DATABASE_URL="mysql://username:password@localhost:3306/singitronic_nextjs"
8. Now you need to open your terminal of choice in the root folder of the project and write:

npm install
9. Now you need to navigate with the terminal in the server folder and install everything:

cd server
npm install
10. You will need to run the Prisma migration now. Make sure you are in the server folder and write:

npx prisma migrate dev
11. Next is to insert demo data. To do it you need to go to the server/utills folder and call insertDemoData.js:

cd utills
node insertDemoData.js
12. Now you can go back to the server folder and run the backend:

cd ..
node app.js
13. While your backend is running you need to open another terminal(don't stop the backend). In the second terminal, you need to make sure you are in your root project folder and write the following:

npm run dev
14. Open http://localhost:3000 and see it live!

About
Singitronic is Next.js and Node.js full-stack e-commerce website with a free source code. Our application comes with the fully functional admin panel and it is fully open-source. Our free online store website is completely responsive and manually tested. You can use our e-commerce project as a template or boilerplate for you next project.

Topics
ecommerce-application ecommerce-website online-shop ecommerce-store full-stack-web-development online-shopping-website ecommerce-react react-ecommerce online-store-website nextjs-ecommerce nodejs-ecommerce react-ecommerce-app nextjs-shop react-ecommerce-template e-commerce-react-template free-react-ecommerce-template ecommerce-using-react react-ecommerce-theme react-ecommerce-boilerplate react-online-shop-template
