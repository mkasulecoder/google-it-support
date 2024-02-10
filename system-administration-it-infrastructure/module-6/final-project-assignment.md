# System Administration Consultation
1.
Question 1
Learning Goals:

Use the systems administration concepts you learned in the course to provide technical improvements to current processes.

Implement solutions based on an organization’s restrictions, like financial resources, number of users, etc.

Overview: You’ll take what you learned in the System Administration and IT Infrastructure Services course and apply that knowledge to real-world situations.

Assignment: For this writing project, you’ll be presented with three scenarios for different companies. You’ll be doing the systems administration for each company’s IT infrastructure. For each scenario, present improvements to processes based on the company’s needs and current restrictions. There’s no right or wrong answer to your consultation, but your responses should explain the problem, the improvement, and the rationale behind them. Please write a 200-400 word process review for each company presented to you.


Scenario 1: 

You’re doing systems administration work for Network Funtime Company. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

Software Company:

Network Funtime Company is a small company that builds open-source software. The company is made up software engineers, a few designers, one person in Human Resources (HR), and a small sales team. Altogether, there are 100 employees. They recently hired you as a system administrator to come in and become their IT department.

When a new person is hired on, the HR person purchases a laptop for them to do their work. The HR representative is unfamiliar with what type of hardware is out there; if a new employee requests a laptop, the HR person will purchase the cheapest option for a laptop online. Because of this, almost everyone has a different laptop model. The company doesn’t have too much revenue to spend, so they don’t order laptops until someone gets hired at the company. This leads to a few days of wait time from when someone starts to when they can actually work on a laptop.

The company doesn’t label their computers with anything, so if a computer is missing or stolen, there’s no way to audit it. There’s no inventory system to keep track of what’s currently in the fleet.

Once a computer is purchased, the HR person hands it to the new employee to set up. Software engineers that use Linux have to find a USB drive and add their preferred distribution to the laptop. Anytime someone needs something from HR -- whether it’s office related or tech related -- they email the HR representative directly.

When a new employee gets a machine, they’re given logins to use cloud services. They get a personal orientation with HR to make sure they can login. This requires the HR person to block off a few hours for every new employee. If an employee forgets the login to their machine, they have no way to retrieve a password and they have to reimagine their machine. Employees don’t have a strict password requirement to set for their computers.

The company currently has many of their services in the cloud, such as email, word processors, spreadsheet applications, etc. They also use the application, Slack, for instant communication.

1 / 1 point
Network Funtime Company faces various issues.
1. The HR department consistently opts for the cheapest laptops for new hires without considering their hardware needs. While this approach saves money upfront, it hampers productivity as employees require laptops tailored to their tasks. To address this, the company must allocate a budget and refine its purchasing strategy, considering different tiers of devices based on user requirements.

2. The company also lacks a system to track its inventory effectively. It's crucial to document and inventory company assets, beginning with labeling each asset of significant value. Regular inventory checks by staff for both personal and corporate assets are necessary.

3. Network Funtime Company lacks dedicated personnel to install and configure its machines. It needs a reliable tech support team to handle these tasks efficiently.

4. Finally, the company's lax password requirements pose a security risk. Strengthening password policies by implementing complexity checks, enforcing multi-factor authentication, and providing password vaults can enhance security and mitigate the risk of data breaches.
Correct
Thank you for your submission!

An excellent response

explains the problem or restrictions that the company faces in great detail.

lists five or more process improvements and explains how they plan to implement each of them.

thoroughly explains the rationale behind each improvement recommendation.

2.
Question 2
Scenario 2:

You’re doing systems administration work for W.D. Widgets. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Please write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

Sales Company:

W.D. Widgets is a small company that sells widgets. They’re mostly made up of salespeople who work with lots of clients. You’ve taken over as the sole IT person for this company of 80-100 people.

When HR tells you to provision a machine for a new employee, you order the hardware directly from a business vendor. You keep one or two machines in stock, in case of emergency. The users receive a username that you generate for them. You then give them an orientation on how to login when they start. You currently manage all of your machines using Windows Active Directory. The company uses only Windows computers. When a new computer is provisioned, you have to install lots of sales-specific applications manually onto every machine. This takes a few hours of your time for each machine. When someone has an IT-related request, they email you directly to help them.

Almost all software is kept in-house, meaning that you’re responsible for the email server, local machine software, and instant messenger. None of the company’s services are kept on the cloud.

Customer data is stored on a single file server. When a new salesperson starts, you also map this file server onto their local machine, so that they can access it like a directory. Whoever creates a folder on this server owns that folder and everything in it. There are no backups to this critical customer data. If a user deletes something, it may be lost for everyone.

The company generates a lot of revenue and is rapidly growing. They’re expecting to hire hundreds of new employees in the next year or so, and you may not be able to scale your operations at the pace you’re working.

1 / 1 point
W.D. Widgets currently faces several IT infrastructure challenges and limitations that need addressing for smoother operations and future scalability.

Implement an automated system for provisioning new machines for employees. This system could streamline the hardware ordering process, generate user accounts, and provide basic orientation instructions, reducing manual intervention and ensuring consistency.

Develop a standardized software deployment process to install sales-specific applications on new machines efficiently. This would save significant time and effort for the IT personnel, allowing them to focus on more critical tasks.

Explore transitioning some services, such as email, file storage, and instant messaging, to cloud-based solutions. This move would offload maintenance responsibilities from the local infrastructure, enhance accessibility, and potentially improve data security and reliability.

Establish a centralized data management system with proper backup procedures for critical customer data. Implementing user access controls and regular backups would mitigate the risk of data loss and ensure data integrity for all users.

Develop a scalability plan to accommodate the company's rapid growth and future hiring projections. This plan should include considerations for expanding IT infrastructure, staffing, and processes to support the increasing workforce effectively.

These improvements would aim to address existing inefficiencies, enhance data security and accessibility, and prepare the IT infrastructure for the company's anticipated growth.
Correct
Thank you for your submission!

An excellent response

explains the problem or restrictions that the company faces in great detail.

lists five or more process improvements and explains how they plan to implement each of them.

thoroughly explains the rationale behind each improvement recommendation.

3.
Question 3
You’re doing systems administration work for Dewgood. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Please write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

Non-profit Company:

Dewgood is a small, local non-profit company of 50 employees. They hired you as the sole IT person in the company. The HR person tells you when they need a new computer for an employee. Currently, computers are purchased directly in a physical store on the day that an employee is hired. This is due to budget reasons, as they can’t keep extra stock in the store.

The company has a single server with multiple services on it, a file server, and email. They don’t currently have a messaging system in place. When a new employee is hired, you have to do an orientation with them for login. You’re also responsible for installing all the software they need on their machine, and mapping the file server to their computer. The computers are managed through Windows Active Directory. When an employee leaves, they’re currently not disabled in the directory service.

The company uses an open-source ticketing system to handle all internal requests as well as external non-profit requests. But the ticketing system is confusing and difficult to use, so lots of the employees reach out to you directly to figure out how to do things. In fact, so many things are difficult to find that employees typically ask around when they have a question.

There are nightly backups in place of the file server. You store this information on a disk backup and take it home with you everyday to keep it safe in case something happens onsite. There’s also a small company website that’s hosted on the single server at the company. This website is a single html page that explains the mission of the company and provides contact information. The website has gone down many times, and no one knows what to do when it happens.

1 / 1 point
Dewgood, a local non-profit with 50 employees, faces several IT infrastructure challenges that need addressing for smoother operations and improved efficiency.

Implement a centralized computer procurement process to avoid last-minute purchases and ensure availability of necessary hardware for new employees. This could involve maintaining a small inventory of standard computer configurations or exploring bulk purchasing options to save costs.

Introduce a dedicated messaging system to facilitate internal communication and collaboration among employees. This system would enhance efficiency and reduce reliance on external communication channels.

Develop a streamlined employee onboarding process that includes pre-configured software installations and file server mappings. This would reduce manual intervention and ensure new employees are productive from day one.

Implement a process to promptly disable employee accounts in the directory service upon termination or resignation. This would enhance security and prevent unauthorized access to company resources.

Upgrade or replace the existing ticketing system with a user-friendly solution to simplify internal and external request management. This would reduce dependency on IT personnel for routine tasks and improve overall productivity.

By addressing these areas for improvement, Dewgood can enhance its IT infrastructure, streamline operations, and better support its mission as a non-profit organization.
