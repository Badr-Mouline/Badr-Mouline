# Badr Mouline
**Computer Science & AI Student @ Université de Montréal**  
**AI & ML Engineer | Python, Deep Learning & LLM Integration | AWS, IBM & Google Certified**

[Portfolio](https://badr-mouline-portfolio.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/badr-mouline) | [Contact](mailto:badr.mouline@umontreal.ca)

---

### PROFESSIONAL SUMMARY
Computer Science student at Université de Montréal and recipient of the Excellence Scholarship. Specializing in bridging rigorous software engineering practices (UML/C4, Design Patterns, TDD) with advanced Machine Learning pipelines and Serverless Cloud Architecture. Experienced in building enterprise-grade Java applications, scalable REST APIs, computer vision systems, and event-driven backend services using Python, Java, and AWS.

---

### TECHNICAL ARSENAL

| Category | Technologies & Tools |
| :--- | :--- |
| **Software Engineering** | Java (JDK 17+), Object-Oriented Design, RESTful Web Services, JUnit 5, Mockito, JaCoCo, Apache Maven, C, Data Structures & Algorithms |
| **AI & Data Science** | Python (Pandas, NumPy, Scikit-Learn, TensorFlow, PyTorch), OpenCV, Tesseract OCR, NLP, Predictive Modeling, R |
| **Cloud & Infrastructure** | AWS (Lambda, API Gateway, S3, DynamoDB, EC2, RDS, Glue, OpenSearch, SQS/SNS, IAM, VPC), Docker, Git, GitHub |
| **Web & Architecture** | React.js, JavaScript (ES6+), HTML5/CSS3, UML Modeling, C4 Architecture, Figma (UX/UI Design), Agile/Scrum |
| **Mathematics** | Linear Algebra, Calculus, Probability & Statistics, Operations Research |

---

### HIGH-IMPACT PROJECTS

#### MaVille – Smart City & Public Works Coordination Platform
* **Architectural Context:** Designed and built an enterprise-grade Java system designed to streamline communication between city residents, municipal agents, and infrastructure contractors across Montreal. Structured the system architecture using UML modeling and the C4 Model (Context, Container, Component, Code) to ensure modularity, separation of concerns, and maintainability.
* **Engineering Execution & Stack:**
  * **Core Logic:** Implemented in Java (JDK 17+) applying Object-Oriented Design Patterns (Factory, Observer, Repository).
  * **API & Data Integration:** Connected directly to the Ville de Montréal Open Data REST APIs to ingest real-time geospatial roadwork datasets, active road closures, and municipal work schedules.
  * **Automated Testing Suite:** Developed end-to-end unit and integration test suites using JUnit 5 and Mockito to mock external API responses and edge cases.
  * **Code Quality & CI/CD:** Integrated JaCoCo for automated code coverage tracking and managed dependencies, builds, and lifecycles via Apache Maven and Git/GitHub under Agile/Scrum workflows.
* **Key Achievements & Metrics:**
  * Automated real-time notifications for registered citizens based on neighborhood impact zones.
  * Achieved high branch code coverage through automated unit testing, preventing regressions across builds.

---

#### SpaceX Booster Landing Intelligence & Cost Analytics (IBM Capstone)
* **Architectural Context:** Engineered an end-to-end Machine Learning and Data Science pipeline to predict the landing success of SpaceX Falcon 9 first-stage boosters, assessing reusability probability and direct cost savings for payload operations.
* **Engineering Execution & Stack:**
  * **Data Acquisition & ETL:** Automated data extraction from SpaceX REST APIs and web scraping via BeautifulSoup. Applied rigorous data wrangling, handling missing geospatial coordinates, and encoding categorical launch site variables using Pandas and NumPy.
  * **Exploratory Data Analysis (EDA):** Built custom statistical visualizations using Matplotlib and Seaborn, and queried telemetry records stored in SQLite / MySQL databases.
  * **Predictive Modeling:** Trained, hyperparameter-tuned (GridSearchCV), and evaluated classification models including Logistic Regression, Support Vector Machines (SVM), Decision Trees, and Random Forest / XGBoost classifiers using Scikit-Learn.
  * **Deployment:** Integrated model predictions into an interactive dashboard for payload mission controllers.
* **Key Achievements & Metrics:**
  * Achieved optimal classification accuracy on unseen test data through cross-validation tuning.
  * Quantified launch site impact factors, providing cost estimation metrics based on booster reusability.

---

#### Autonomous Computer Vision & OCR Processing Engine
* **Architectural Context:** Engineered an automated image processing pipeline in Python designed to extract structured text from low-quality, noisy, or distorted document scans and images.
* **Engineering Execution & Stack:**
  * **Computer Vision Processing:** Leveraged OpenCV to apply custom binarization, adaptive thresholding, Gaussian blurring, morphological operations (erosion/dilation), and deskewing transformations.
  * **Text Extraction Engine:** Integrated Tesseract OCR Engine with tuned configuration parameters (Page Segmentation Modes - PSM and Engine Modes - OEM) to extract clean string data.
  * **Post-Processing & NLP:** Implemented regular expressions and string cleaning algorithms in Python to format extracted metadata for structured JSON/CSV export.
* **Key Achievements & Metrics:**
  * Improved Optical Character Recognition (OCR) accuracy by over 20% on degraded image inputs through custom pre-processing pipelines.
  * Reduced document processing latency through vectorized Python operations.

---

#### Enterprise AWS Serverless & Cloud Infrastructure Portfolio
* **Architectural Context:** Architected scalable, highly available, and event-driven cloud infrastructure solutions adhering to the AWS Well-Architected Framework (Serverless Architecture, Security, Operational Excellence).
* **Engineering Execution & Stack:**
  * **Serverless Backend:** Configured AWS API Gateway endpoints triggering AWS Lambda functions written in Python/Node.js, with persistent storage in Amazon DynamoDB.
  * **Data Lake Architecture:** Structured event-driven ingestion pipelines utilizing Amazon S3 for raw object storage, AWS Glue for automated ETL crawling and data cataloging, and OpenSearch / Athena for indexing and querying.
  * **Security & Networking:** Configured AWS Identity and Access Management (IAM) roles with Least Privilege principles, secured resources inside custom Amazon VPCs, public/private subnets, Security Groups, and API authentication flows.
  * **Relational Storage & Messaging:** Managed Amazon RDS (PostgreSQL/MySQL) and Amazon EC2 instances alongside asynchronous messaging decouplers (AWS SQS / SNS).
* **Key Achievements & Metrics:**
  * Eliminated server maintenance overhead using fully serverless compute and database layers.
  * Optimized payload query response times via indexing and DynamoDB single-table design principles.

---

#### SantéHub – Single-Page Interactive Health Tracking Dashboard
* **Architectural Context:** Designed and implemented a responsive Single Page Application (SPA) aimed at tracking personal wellness habits, monitoring health metrics, and displaying dynamic visual analytics.
* **Engineering Execution & Stack:**
  * **UI/UX Prototyping:** Designed high-fidelity wireframes, design tokens, and user flow interactions in Figma.
  * **Frontend Engineering:** Converted Figma mockups into lightweight, framework-free code using Pure HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+), and DOM manipulation.
  * **Data Visualization & State Management:** Built interactive charts and dynamic filtering components using jQuery and Charting libraries, storing state persistence in LocalStorage.
  * **Accessibility (a11y):** Implemented ARIA roles, semantic HTML, keyboard navigation, and responsive media queries across browser engines.
* **Key Achievements & Metrics:**
  * Achieved sub-second initial page load time through zero third-party framework overhead.
  * Fully compliant with accessibility standards and cross-browser responsiveness tests.

---

#### Urban Mobility Infrastructure & Cycling Safety Study (Google Capstone)
* **Architectural Context:** Executed a data-driven statistical research study analyzing urban cycling behavior, commuter patterns, and road infrastructure safety risks to inform urban planning decisions.
* **Engineering Execution & Stack:**
  * **Data Pipeline in R:** Processed, cleaned, and normalized multi-source mobility datasets using R, tidyverse, dplyr, and ggplot2.
  * **Statistical Validation:** Conducted hypothesis testing, correlation analyses, and variance assessments to identify significant safety risk variables.
  * **Reporting & Dashboards:** Built interactive visual dashboards in Tableau / Power BI to translate statistical findings into executive summaries for city planners.
* **Key Achievements & Metrics:**
  * Identified key high-risk transit corridors and peak accident probability windows.
  * Formulated actionable infrastructure recommendations backed by rigorous statistical validation.

---

### CERTIFICATIONS & EDUCATION

* **B.S. in Computer Science** – Université de Montréal (In Progress)
* **AWS Certified Cloud Solutions Architect – Associate** (2024)
* **IBM Data Science Professional Certificate** (2024)
* **Google Data Analytics Professional Certificate** (2024)
* **Google UX Design Professional Certificate** (2024)

---

### EXCELLENCE & DISTINCTIONS

* **Excellence Scholarship** – Université de Montréal (Awarded for top-tier academic performance)
* **Valedictorian / Salutateur** – Professional Diploma in Computerized Management

---

### CONTACT & NETWORKING

* **Portfolio:** https://badr-mouline-portfolio.vercel.app/
* **LinkedIn:** https://www.linkedin.com/in/badr-mouline
* **Email:** badrmouline1@gmail.com
* **Location:** Montreal, QC, Canada
