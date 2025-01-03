<hr />
<br />

<div align="center">
  <h1> UZOAGULU JOSHUA .C

[![Github Badge](https://img.shields.io/badge/Github-black?style=plastic&logo=github)](#) &nbsp;
[![Yahoo Mail](https://img.shields.io/badge/Yahoo-Mail-purple?logo=yahoo&logoColor=white)](mailto:uzoagulujoshua@yahoo.com) &nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joshua-uzoagulu-b67a70177)

</h1>
</div>

## Solving Problems, One Quirk at a Time

I'm a problem-solving enthusiast who thrives on turning ideas into impactful solutions. if it needs building, automating, or blockchain-ing, I’m your go-to. From whipping up insurance aggregators to creating blockchain voting systems, I’ve been the architect behind some pretty cool (and occasionally chaotic) projects.

When I’m not wrestling with APIs or convincing computers to behave, I’m probably daydreaming about ways to outsmart them. My mantra? “If it’s broken, I’ll fix it. If it’s not broken, I’ll make it better—and probably add a feature or two for fun. 🌚”

Got a wild idea or a project that needs a touch of brilliance (and maybe a sprinkle of madness)? Hit me up—let’s create something unforgettable together!

## Projects Summary:

The projects listed here showcase some of the work I’ve done over the years, highlighting my passion for solving problems and building impactful solutions. Feel free to explore the code repositories and project details. If you’re interested in collaborating or have any questions, don’t hesitate to reach out—I’d love to connect and work on exciting ideas together!

### 1) Resume Tailoring Automation Tool

**Project Overview**:
The Resume Tailoring Automation Tool is a sophisticated automation solution designed to optimize the job application process for users. The tool automatically customizes resumes and cover letters to match specific job postings, saving users valuable time. By leveraging OpenAI and LangChain, the tool generates tailored resumes that are then converted into DOCX files and uploaded to a Google Drive folder. Once the process is completed, a Slack notification is sent to inform the user with a link to the tailored resume.

**Year Developed:** 2024

**Project Description:**
The Tailoring Automation Tool streamlines the resume customization process for job applicants. It takes job descriptions and user resumes, then automatically tailors them to match the job requirements. The tool performs the following steps:

Resume Tailoring:

Using OpenAI's language model and LangChain to process job descriptions and user resumes. The tool adjusts the language, skills, and experience in the resume to fit the specific job posting.
Docx files are generated for the tailored resumes, ensuring they are compatible with traditional job application systems.
Google Drive Upload:

The tailored resume is automatically uploaded to a designated Google Drive folder for easy access and sharing.
The tool uses the Google Drive API to handle file uploads programmatically, organizing resumes in folders by job application.
Slack Notification:

After the resume tailoring process is complete, the tool sends a notification to a Slack channel. This notification includes a message stating that the process is finished, along with a direct link to the tailored resume stored on Google Drive.
The Slack API is used to send the notification, providing a seamless and efficient way for users to receive updates.
Automation Workflow:

The entire process, from resume tailoring to file upload and notification, is automated. Scheduled jobs handle the routine tasks, ensuring that users can rely on the tool to complete their applications in an efficient manner.

**Use Case:**
This tool is ideal for job seekers who want to apply to multiple positions without spending time tailoring their resume for each application. By automating the process, users can increase the speed and efficiency of their job search, all while ensuring that their resumes are aligned with the specific requirements of each job posting.

**Technologies Used:**

**Backend:** ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**LLM:** ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

**Cloud Storage:** ![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

**Notification System:** ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

**Job Queue Processing:** ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

**Website Link:** - click here - [![Yahoo Mail](https://img.shields.io/badge/Yahoo-Mail-purple?logo=yahoo&logoColor=white)](mailto:uzoagulujoshua@yahoo.com?subject=Request%20For%20Resume%20Optimizer)

### 2) Meetup - Social Networking Application

**Project Overview**:
Meetup is a social networking application designed to help individuals connect and interact with others in real-time. It consists of two main modules: Duo Meetup and Meetup Multi. In Duo Meetup, users can connect with other users and engage in one-on-one conversations, while Meetup Multi allows users to view events, get event details, and mark their attendance. The application uses GraphQL and WebSocket for real-time communication and data handling.

**Year Developed:** 2024

**Technologies Used**:

**Backend:** ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)

**Real-time Communication:** ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)

**Website Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/meetup)

### 3) Hyperledger Fabric (test_cura) - Basic Hyperledger Network

**Project Overview:**
The test_cura project is a minimal CLI-based application built using Hyperledger Fabric to set up and benchmark a private blockchain network. The project focuses on creating organizations, configuring channels, and testing data throughput for reading and writing operations. It includes the process of setting up the network, deploying smart contracts, and managing peer communication in a blockchain environment.

**Year Developed:** 2023

**Key Features:**

Network Setup and Configuration:

Creation of artifacts folder for storing network configuration files.
crypto-config.yaml file is used for bootstrapping organizations’ identities, including generating certificates for each organization.
configtx.yaml configures the genesis block, channel configuration, and anchor peers for the organizations.
Channel Creation and Management:

Scripts to create channel artifacts and deploy them.
Channel creation and joining organizations to the channel for collaborative transactions.
Updating anchor peers for each organization.
Smart Contract Deployment:

Deploy script that brings up the network and installs dependencies for the smart contract.
Chaincode packaging outputs the chaincode in .tar.gz format.
Installation of chaincode on endorsing peers and approval by organizations.
Chaincode Commit and Invocation:

Use checkCommitReadiness to ensure all organizations are in favor of committing the chaincode definition.
Commit the chaincode definition to the peers for deployment.
Invoke chaincode init method to start the contract and allow interactions.
Benchmarking Data Throughput:

The project is designed to test the read and write throughput of the blockchain network and smart contracts.
It benchmarks the performance of data transactions across different organizations within the network.
Use Case:
The test_cura project serves as an example of setting up a Hyperledger Fabric-based private blockchain network. It is used for testing, validating, and benchmarking various blockchain operations such as transaction speed, throughput, and scalability in a controlled environment. It provides a foundation for building more complex, real-world applications that require secure, permissioned networks with multiple organizations.

**Technologies Used:**

**Blockchain Framework:** ![Hyperledger](https://img.shields.io/badge/hyperledger-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)

**Scripting:** ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Chaincode:** ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

**Queue:** ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)

**GitHub Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/hyperledger_testing)

### 4) Aoura - Blockchain Messaging Application for the Visually Impaired

**Project Overview:**
Aoura is a blockchain-powered messaging application designed specifically for the visually impaired community. The platform allows users to communicate via text or audio messages, where audio messages are transcribed into text and sent to the recipient. The application also features group chats, allowing users to connect, interact, and foster a sense of belonging. Built on blockchain, it ensures secure, decentralized communication and data privacy for users.

**Year Developed:** 2023

**Key Features:**

Text and Audio Messaging:

Users can send and receive messages via text or audio.
Audio messages are transcribed into text to ensure accessibility for all users.
Group Chat Functionality:

Users can create and join groups to interact with multiple people in real-time.
Group chats promote community building and enable discussions on various topics.
Blockchain-Based Messaging:

Built on the Ethereum network, the application ensures secure, transparent, and decentralized communication.
Blockchain technology guarantees that messages are private and tamper-proof.

Smart Contract Integration:

Developed using Solidity, the backend smart contracts handle secure transactions and interactions between users.
Truffle.js is used for deploying and testing the smart contracts on the Ethereum network.
Accessibility Focus:

**Technologies Used:**

**Frontend:** ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

**Backend:** ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)

**Framework:** Truffle.js

**Website/GitHub Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/blockchain_messaging)

### 5) NutureHub

**Project Overview:**
NutureHub is a minimalist one-page static website template designed to provide a versatile and visually appealing foundation for various personal or professional projects. With its clean design and responsive layout, it offers a fast, secure, and user-friendly platform suitable for developers, bloggers, small businesses, and more.

**Year Developed:** 2024

**Project Description:**
NutureHub was crafted during free time as a personal project to explore minimalist web design and create a template suitable for a wide range of uses. It is designed to be simple yet functional, ensuring users have a reliable and elegant starting point for their online presence.

**Key Features:**

Minimalist Design:

Focuses on clarity and elegance for a modern and clean homepage aesthetic.
Versatile Usage:

Suitable for developers, designers, bloggers, or small businesses looking for a simple and effective website.
Static and Fast:

As a static site, it offers quick load times and enhanced security without complex server requirements.
Responsive Layout:

Designed to provide an optimal user experience across all devices, including desktops, tablets, and smartphones.
Easy Customization:

Users can easily modify the template, including color schemes, fonts, and content organization, to fit their needs.
Open Source:

Available as an open-source project, allowing users to contribute, customize, and enhance its features.

**Use Case:**
Whether you need a portfolio, a landing page, or a simple online presence, NutureHub serves as a flexible, fast, and stylish template that adapts to various purposes. Its simplicity makes it an ideal starting point for both beginners and experienced developers.

**Technologies Used:**

**Frontend:** ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)

**Hosting Platform:** [![Link](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)](https://sally-builds.github.io/nuturehub.github.io/)

### 6) Budget Assistant

**Project Overview:**
The Budget Assistant is a computerized and automated budget management application designed to help institutions track their income and expenditure. It offers insights into profit and loss margins, and allows users to simulate the actual financial flows based on a specified budget. This project was developed to solidify my knowledge of dependency injection (DI) and inversion of control (IoC) in an API backend.

**Year Developed:** 2023

**Technologies Used:**

**Frontend:** ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

**Backend:** ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

**Database:** ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Design Patterns:** SOLID Principles

**Website/GitHub Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/budget_assistant)

### 7) Blockchain Voting Application

**Project Overview:**
This is a blockchain-based voting system designed to ensure secure, transparent, and tamper-proof elections. The application enables administrators to create elections, manage candidates, and oversee the voting process, while users can cast their votes securely during the election period. Built on the Ethereum blockchain, it leverages smart contracts for transparency and ensures that all actions are immutably recorded on the blockchain.

**Year Developed:** 2023

**Key Features:**

Admin Functionality:

Create elections and specify candidates.
Set the start and end times for each election.
Transfer ownership of the admin role to another blockchain address for flexibility.
Voting System:

Registered users can vote for candidates during the active election period.
Each voter is restricted to one vote per election, enforced by the smart contract.
Transparency and Security:

All actions, including election creation and voting, are logged immutably on the Ethereum blockchain.
Results are automatically calculated and displayed transparently after the election ends.
Smart Contract Functionality:

Admin address is set during contract deployment, granting exclusive control over election management.
Ownership transfer ensures continued application governance if the admin changes.

**Technologies Used:**

**Frontend:** ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

**Smart Contracts:** ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)

**Blockchain Network:** ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)

**Blockchain Framework:** Truffle.js

**Wallet Integration:** MetaMask

**Website/GitHub Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/secure_voting)

### 8) Futfund

**Project Overview:**
Futfund is a blockchain-based crowdfunding platform designed to support university projects. Developed by the student union of a university, it allows students, lecturers, and other stakeholders to view proposed school projects, their associated costs, and contribute funds transparently. The Ethereum blockchain ensures that every transaction is open to the public, promoting accountability and trust.

**Year Developed:** 2022

**Technologies Used:**

**Frontend:** ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

**Smart Contracts:** ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)

**Blockchain Framework:** Truffle.js

**Blockchain Network:** ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)

**Wallet Integration:** MetaMask

**Website/GitHub Link:** [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sally-Builds/futfund)

### 9) Online Auction Web Application

**Project Overview:**
This is an online auction platform where users can list products for auction, set specific auction times, and participate in real-time English-style bidding. The application ensures seamless interactions by leveraging socket technology for bid exchanges and integrates a wallet system powered by Flutterwave for secure payments.

**Year Designed:** 2020

**Project Description:**
The platform provides an interactive and efficient way for users to auction products. Users can create auction listings, set auction durations, and monitor bids in real-time. Potential buyers can view upcoming auctions, join auction rooms at scheduled times, and bid competitively. The system implements a wallet feature, ensuring users can only bid if they have sufficient funds, with top-ups facilitated through Flutterwave integration.

**Key Features:**

**User Auctions:**

Create product listings for auction.
Specify auction start and end times.
Wallet System:

Users can credit their wallets via Flutterwave's secure payment gateway.
Wallet balances are validated before bidding.
Real-Time Bidding:

Auctions use the Pusher Socket Library for instantaneous bid updates.
English auction style ensures dynamic and competitive bidding.
Auction Rooms:

Users join specific auction rooms at the scheduled time.
Live updates for all participants during the auction.
Admin Features (if applicable):

Monitor auctions and user activities.
Manage listings and transactions.
Use Case:
Developed as a final-year defense project, this application demonstrates real-world problem-solving and technical proficiency in building robust, real-time systems with seamless user interactions.

**Technologies Used:**

**Frontend:** [![Vuejs Badge](https://img.shields.io/badge/Vue.js-blue?style=plastic&logo=vuedotjs)](#) [![Javascript Badge](https://img.shields.io/badge/javascript-peach?style=plastic&logo=javascript)](#) [![Css3 Badge](https://img.shields.io/badge/CSS3-darkblue?style=plastic&logo=css3)](#)

**Backend:** [![Nodejs Badge](https://img.shields.io/badge/Nodejs-brown?style=plastic&logo=nodedotjs)](#) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

**Database:** ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Real-Time Communication:** ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)

**Payment Gateway:** ![Stripe](https://img.shields.io/badge/Stripe-5469d4?style=for-the-badge&logo=stripe&logoColor=ffffff)

**Hosting Platform:** ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

**Website/GitHub Link:** Client -[![Github Badge](https://img.shields.io/badge/Github-black?style=plastic&logo=github)](https://github.com/Sally-Builds/auction-client-side-nuxt) &nbsp; Server -[![Github Badge](https://img.shields.io/badge/Github-black?style=plastic&logo=github)](https://github.com/Sally-Builds/auction-server)

### 10) FranAir Construction

**Project Overview:**
FranAir Construction is a premier Nigerian building contracting company specializing in providing top-notch construction and building services. The company's mission is to design and construct homes and commercial projects while maintaining quality and on-time delivery. It caters to a wide array of services including estate building, interior decoration, aluminum profiling, tiling, painting, and more.

**Year Designed**: 2020

**Technologies Used:**

**Web Development:** [![Vuejs Badge](https://img.shields.io/badge/Vue.js-blue?style=plastic&logo=vuedotjs)](#) [![Javascript Badge](https://img.shields.io/badge/javascript-peach?style=plastic&logo=javascript)](#) ![Css3 Badge](https://img.shields.io/badge/CSS3-darkblue?style=plastic&logo=css3)

**Website/GitHub Link:** [![Link](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)](https://sally-builds.github.io/franairconstruction/)

### 11) Fendbank App

**Project Overview:**
Fendbank App is a fintech solution designed to provide users with a seamless banking experience. The application allows users to sign up, receive a unique account number, transfer and receive funds from other users, and fund their wallets using an external payment gateway. This project highlights a secure, user-friendly, and scalable approach to modern digital banking.

**Year Designed:** 2020

**Technologies Used:**

**Frontend:** ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Nuxtjs](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82)

**Backend:** ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

**Database:** ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Payment Gateway:** Flutterwave

**Hosting Platform:** ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

## Technical Skills:

#### Programming Languages

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

#### Frameworks

![Hyperledger](https://img.shields.io/badge/hyperledger-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Nuxtjs](https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

#### Database

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

#### Web Scraping & Data Extraction

![Puppeteer](https://img.shields.io/badge/Puppeteer-white.svg?style=for-the-badge&logo=Puppeteer&logoColor=black)

#### Test Frameworks

![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)

#### AI Tools

[![Css3 Badge](https://img.shields.io/badge/CSS3-darkblue?style=plastic&logo=css3)](#)
[![Html5 Badge](https://img.shields.io/badge/HTML5-red?style=plastic&logo=html5)](#)
[![Passport Badge](https://img.shields.io/badge/Passport-black?style=plastic&logo=passport)](#)
[![Solidity Badge](https://img.shields.io/badge/Solidity-purple?style=plastic&logo=solidity)](#)

#### Cloud Platforms

![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white)
![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![Linode](https://img.shields.io/badge/linode-00A95C?style=for-the-badge&logo=linode&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

#### CI CD

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
