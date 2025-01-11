# dev_note_free_portals
This is a list of software (SaaS, PaaS, IaaS, etc.) and other offerings with free developer tiers.


Major Cloud Providers
Google Cloud Platform

App Engine - 28 frontend instance hours per day, nine backend instance hours per day
Cloud Firestore - 1GB storage, 50,000 reads, 20,000 writes, 20,000 deletes per day
Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
Cloud Storage - 5GB, 1GB network egress
Cloud Shell - Web-based Linux shell/primary IDE with 5GB of persistent storage. 60 hours limit per week
Cloud Pub/Sub - 10GB of messages per month
Cloud Functions - 2 million invocations per month (includes both background and HTTP invocations)
Cloud Run - 2 million requests per month, 360,000 GB-seconds memory, 180,000 vCPU-seconds of compute time, 1 GB network egress from North America per month
Google Kubernetes Engine - No cluster management fee for one zonal cluster. Each user node is charged at standard Compute Engine pricing
BigQuery - 1 TB of querying per month, 10 GB of storage each month
Cloud Build - 120 build-minutes per day
Cloud Source Repositories - Up to 5 Users, 50 GB Storage, 50 GB Egress
Google Colab - Free Jupyter Notebooks development environment.
idx.dev Google Project IDX. Online VSCode running on Google Cloud.
Full, detailed list - https://cloud.google.com/free
Amazon Web Services

CloudFront - 1TB egress per month and 2M Function invocations per month
CloudWatch - 10 custom metrics and ten alarms
CodeBuild - 100min of build time per month
CodeCommit - 5 active users,50GB storage, and 10000 requests per month
CodePipeline - 1 active pipeline per month
DynamoDB - 25GB NoSQL DB
EC2 - 750 hours per month of t2.micro or t3.micro(12mo). 100GB egress per month
EBS - 30GB per month of General Purpose (SSD) or Magnetic(12mo)
Elastic Load Balancing - 750 hours per month(12mo)
RDS - 750 hours per month of db.t2.micro, db.t3.micro, or db.t4g.micro, 20GB of General Purpose (SSD) storage, 20GB of storage backups(12 mo)
S3 - 5GB Standard object storage, 20K Get requests and 2K Put requests(12 mo)
Glacier - 10GB long-term object storage
Lambda - 1 million requests per month
SNS - 1 million publishes per month
SES - 3.000 messages per month (12mo)
SQS - 1 million messaging queue requests
Full, detailed list - https://aws.amazon.com/free/
Microsoft Azure

Virtual Machines - 1 B1S Linux VM, 1 B1S Windows VM (12mo)
App Service - 10 web, mobile, or API apps (60 CPU minutes/day)
Functions - 1 million requests per month
DevTest Labs - Enable fast, easy, and lean dev-test environments
Active Directory - 500,000 objects
Active Directory B2C - 50,000 monthly stored users
Azure DevOps - 5 active users, unlimited private Git repos
Azure Pipelines — 10 free parallel jobs with unlimited minutes for open source for Linux, macOS, and Windows
Microsoft IoT Hub - 8,000 messages per day
Load Balancer - 1 free public load-balanced IP (VIP)
Notification Hubs - 1 million push notifications
Bandwidth - 15GB Inbound(12mo) & 5GB egress per month
Cosmos DB - 25GB storage and 1000 RUs of provisioned throughput
Static Web Apps — Build, deploy, and host static apps and serverless functions with free SSL, Authentication/Authorization, and custom domains
Storage - 5GB LRS File or Blob storage (12mo)
Cognitive Services - AI/ML APIs (Computer Vision, Translator, Face detection, Bots, etc) with free tier including limited transactions
Cognitive Search - AI-based search and indexation service, free for 10,000 documents
Azure Kubernetes Service - Managed Kubernetes service, free cluster management
Event Grid - 100K ops/month
Full, detailed list - https://azure.microsoft.com/free/
Oracle Cloud

Compute
2 AMD-based Compute VMs with 1/8 OCPU and 1 GB memory each
4 Arm-based Ampere A1 cores and 24 GB of memory usable as one VM or up to 4 VMs
Instances will be reclaimed when deemed idle
Block Volume - 2 volumes, 200 GB total (used for compute)
Object Storage - 10 GB
Load balancer - 1 instance with 10 Mbps
Databases - 2 DBs, 20 GB each
Monitoring - 500 million ingestion data points, 1 billion retrieval datapoints
Bandwidth - 10 TB egress per month, speed limited to 50 Mbps on x64-based VM, 500 Mbps * core count on ARM-based VM
Public IP - 2 IPv4 for VMs, 1 IPv4 for load balancer
Notifications - 1 million delivery options per month, 1000 emails sent per month
Full, detailed list - https://www.oracle.com/cloud/free/
IBM Cloud

Object Storage - 25GB per month
Cloudant database - 1 GB of data storage
Db2 database - 100MB of data storage
API Connect - 50,000 API calls per month
Availability Monitoring - 3 million data points per month
Log Analysis - 500MB of daily log
Full, detailed list - https://www.ibm.com/cloud/free/
Cloudflare

Application Services - Free DNS for an unlimited number of domains, DDoS Protection, CDN along with free SSL, Firewall rules and page rules, WAF, Bot Mitigation, Free Unmetered Rate Limiting - 1 rule per domain, Analytics, Email forwarding
Zero Trust & SASE - Up to 50 Users, 24 hours of activity logging, three network locations
Cloudflare Tunnel - You can expose locally running HTTP port over a tunnel to a random subdomain on trycloudflare.com use Quick Tunnels, No account required. More features (TCP tunnel, Load balancing, VPN) in Zero Trust Free Plan.
Workers - Deploy serverless code for free on Cloudflare's global network—100k daily requests.
Workers KV - 100k read requests per day, 1000 write requests per day, 1000 delete requests per day, 1000 list requests per day, 1 GB stored data
R2 - 10 GB per month, 1 million Class A operations per month, 10 million Class B operations per month
D1 - 5 million rows read per day, 100k rows written per day, 1 GB storage
Pages - Develop and deploy your web apps on Cloudflare's fast, secure global network. Five hundred monthly builds, 100 custom domains, Integrated SSL, unlimited accessible seats, unlimited preview deployments, and full-stack capability via Cloudflare Workers integration.
Queues - 1 million operations per month
TURN – 1TB of free (outgoing) traffic per month.
⬆️ Back to Top

Cloud management solutions
Brainboard - Collaborative solution to visually build and manage cloud infrastructures from end-to-end.
Cloud 66 - Free for personal projects (includes one deployment server, one static site), Cloud 66 gives you everything you need to build, deploy, and grow your applications on any cloud without the headache of the “server stuff.”.
Pulumi — Modern infrastructure as a code platform that allows you to use familiar programming languages and tools to build, deploy, and manage cloud infrastructure.
terraform.io — Terraform Cloud. Free remote state management and team collaboration for up to 500 resources.
scalr.com - Scalr is a Terraform Automation and COllaboration (TACO) product used to better collaboration and automation on infrastructure and configurations managed by Terraform. Full Terraform CLI support, OPA integration, and a hierarchical configuration model. No SSO tax. All features are included. Use up to 50 runs/month for free.
deployment.io - Deployment.io helps developers automate deployments on AWS. On our free tier, a developer (single user) can deploy unlimited static sites, web services, and environments. We provide 20 job executions free per month with previews and auto-deploys included in the free tier.
⬆️ Back to Top

Source Code Repos
Bitbucket — Unlimited public and private Git repos for up to 5 users with Pipelines for CI/CD
chiselapp.com — Unlimited public and private Fossil repositories
codebasehq.com — One free project with 100 MB space and two users
Codeberg — Unlimited public and private Git repos for free and open-source projects (with unlimited collaborators). Powered by Forgejo. Static website hosting with Codeberg Pages. CI/CD hosting with Codeberg's CI. Translating hosting with Codeberg Translate. Includes Package and Container hosting, Project management, and Issue Tracking
GitGud — Unlimited private and public repositories. Free forever. Powered by GitLab & Sapphire. CI/CD not provided.
GitHub — Unlimited public repositories and unlimited private repositories (with unlimited collaborators). Includes CI/CD, Development Environment, Static Hosting, Package and Container hosting, Project management and AI Copilot
gitlab.com — Unlimited public and private Git repos with up to 5 collaborators. Includes CI/CD, Static Hosting, Container Registry, Project Management and Issue Tracking
framagit.org — Framagit is the software forge of Framasoft based on the Gitlab software includes CI, Static Pages, Project pages and Issue tracking.
heptapod.net — Heptapod is a friendly fork of GitLab Community Edition providing support for Mercurial
ionicframework.com - Repo and tools to develop applications with Ionic; also you have an ionic repo
NotABug — NotABug.org is a free-software code collaboration platform for freely licensed projects, Git-based
OSDN - OSDN.net is a free-of-charge service for open-source software developers, offering SVN/Git/Mercurial/Bazaar/CVS repositories.
Pagure.io — Pagure.io is a free and open source software code collaboration platform for FOSS-licensed projects, Git-based
perforce.com — Free 1GB Cloud and Git, Mercurial, or SVN repositories.
pijul.com - Unlimited free and open source distributed version control system. Its distinctive feature is based on a sound theory of patches, which makes it easy to learn, use, and distribute. Solves many problems of git/hg/svn/darcs.
plasticscm.com — Free for individuals, OSS, and nonprofit organizations
projectlocker.com — One free private project (Git and Subversion) with 50 MB of space
RocketGit — Repository Hosting based on Git. Unlimited Public and private repositories.
savannah.gnu.org - Serves as a collaborative software development management system for free Software projects (for GNU Projects)
savannah.nongnu.org - Serves as a collaborative software development management system for free Software projects (for non-GNU projects)
⬆️ Back to Top

APIs, Data, and ML
JSONGrid - Free tool to Visualize, Edit, Filter complex JSON data into beautiful tabular Grid. Save and Share JSON data over link link.
Zerosheets - Turn your Google Sheets spreadsheets into powerful API`s to rapidly develop prototypes, websites, apps and more. 500 requests per month available for free.
IP.City — 100 Free IP geolocation requests per day
Abstract API — API suite for various use cases, including IP geolocation, gender detection, or email validation.
Apify — Web scraping and automation platform to create an API for any website and extract data. Ready-made scrapers, integrated proxies, and custom solutions. Free plan with $5 platform credits included every month.
APITemplate.io - Auto-generate images and PDF documents with a simple API or automation tools like Zapier & Airtable. No CSS/HTML is required. The free plan comes with 50 images/month and three templates.
APIToolkit.io - All the tools you need to fully understand what's going on in your APIs and Backends. With automatic API contract validation and monitoring. The free plan covers servers with up to 20,000 requests per month.
APIVerve - Get instant access to over 120+ APIs for free, built with quality, consistency, and reliability in mind. The free plan covers up to 50 API Tokens per month.
Arize AI - Machine learning observability for model monitoring and root-causing issues such as data quality and performance drift. Free up to two models.
Atlas toolkit - Lightweight library to develop single-page web applications that are instantly accessible. Available for Java, Node.js, Perl, Python, and Ruby.
Beeceptor - Mock a rest API in seconds, fake API response and much more. Free 50 requests per day, public dashboard, open endpoints (anyone with a dashboard link can view submissions and answers).
bigml.com — Hosted machine learning algorithms. Unlimited free tasks for development, limit of 16 MB data/task.
Browse AI — Extracting and monitoring data on the web. Fifty credits per month for free.
BrowserCat - Headless browser API for automation, scraping, AI agent web access, image/pdf generation, and more. Free plan with 1k requests per month.
Bruzu — Automate Image production. Generate tons of Image variants with API, Integrations, or nocode sheet. API is FREE with a watermark.
Calendarific - Enterprise-grade Public holiday API service for over 200 countries. The free plan includes 1,000 calls per month.
Canopy - GraphQL API for Amazon.com product, search, and category data. The free plan includes 100 calls per month.
Clarifai — Image API for custom face recognition and detection. Able to train AI models. The free plan has 5,000 calls per month.
Cloudmersive — Utility API platform with full access to expansive API Library including Document Conversion, Virus Scanning, and more with 800 calls/month.
Colaboratory — Free web-based Python notebook environment with Nvidia Tesla K80 GPU.
Collect2 — Create an API endpoint to test, automate, and connect webhooks. The free plan allows for two datasets, 2000 records, one forwarder, and one alert.
CometML - The MLOps platform for experiment tracking, model production management, model registry, and complete data lineage, covering your workflow from training to production. Free for individuals and academics.
Commerce Layer - Composable commerce API that can build, place, and manage orders from any front end. The developer plan allows 100 orders per month and up to 1,000 SKUs for free.
Conversion Tools - Online File Converter for documents, images, video, audio, and eBooks. REST API is available. Libraries for Node.js, PHP, Python. Support files up to 50 GB (for paid plans). The free tier is limited by file size and number of conversions per day.
Country-State-City Microservice API - API and Microservice to provides a wide range of information including countries, regions, provinces, cities, postal codes, and much more. The free tier includes up to 100 requests per day.
Coupler - Data integration tool that syncs between apps. It can create live dashboards and reports, transform and manipulate values, and collect and back up insights. The free plan has unlimited users, 100 runs with 1000 monthly rows, and unlimited integrations.
CraftMyPDF - Auto-Generate PDF documents from reusable templates with a drop-and-drop editor and a simple API. The free plan comes with 100 PDFs/month and three templates.
CurlHub — Proxy service for inspecting and debugging API calls. The free plan includes 10,000 requests per month.
CurrencyScoop - Realtime currency data API for fintech apps. The free plan includes 5,000 calls per month.
Cube - Cube helps data engineers and application developers access data from modern data stores, organize it into consistent definitions, and deliver it to every application. The fastest way to use Cube is with Cube Cloud, which has a free tier with 1GB of data passing through each month.
Data Dead Drop - Simple, free file sharing. Data self-destroys after access. Upload and download data via the browser or your favorite command line client.
Data Fetcher - Connect Airtable to any application or API with no code. Postman-like interface for running API requests in Airtable. Pre-built integrations with dozens of apps. The free plan includes 100 runs per month.
Dataimporter.io - Tool for connecting, cleaning, and importing data into Salesforce. Free Plan includes up to 20,000 records per month.
Datalore - Python notebooks by Jetbrains. Includes 10 GB of storage and 120 hours of runtime each month.
Data Miner - A browser extension (Google Chrome, MS Edge) for data extraction from web pages CSV or Excel. The free plan gives you 500 pages/month.
Datapane - API for building interactive reports in Python and deploying Python scripts and Jupyter Notebooks as self-service tools.
DB-IP - Free IP geolocation API with 1k request per IP per day.lite database under the CC-BY 4.0 License is free too.
DB Designer — Cloud-based Database schema design and modeling tool with a free starter plan of 2 Database models and ten tables per model.
DeepAR — Augmented reality face filters for any platform with one SDK. The free plan provides up to 10 monthly active users (MAU) and tracks up to 4 faces
Deepnote - A new data science notebook. Jupyter is compatible with real-time collaboration and running in the cloud. The free tier includes unlimited personal projects, up to 750 hours of standard hardware, and teams with up to 3 editors.
Diggernaut — Cloud-based web scraping and data extraction platform for turning any website to the dataset or working with it as an API. The free plan includes 5K page requests monthly.
Disease.sh — A free API providing accurate data for building the Covid-19 related useful Apps.
Doczilla — SaaS API empowering the generation of screenshots or PDFs directly from HTML/CSS/JS code. The free plan allows 250 documents month.
Doppio — Managed API to generate and privately store PDFs and Screenshots using top rendering technology. The free plan allows 400 PDFs and Screenshots per month.
dreamfactory.com — Open source REST API backend for mobile, web, and IoT applications. Hook up any SQL/NoSQL database, file storage system, or external service, and it instantly creates a comprehensive REST API platform with live documentation and user management.
DynamicDocs - Generate PDF documents with JSON to PDF API based on LaTeX templates. The free plan allows 50 API calls per month and access to a library of templates.
Efemarai - Testing and debugging platform for ML models and data. Visualize any computational graph. Free 30 debugging sessions per month for developers.
ExtendsClass - Free web-based HTTP client to send HTTP requests.
Export SDK - PDF generator API with drag-and-drop template editor that provides an SDK and no-code integrations. The free plan has 250 monthly pages, unlimited users, and three templates.
Fern - Use your API definition to generate SDKs in popular languages, and generate API reference documentation webpages. Add Markdown pages to your API reference and host them with Fern for a full documentation solution. OpenAPI fully supported.
file.coffee - A platform where you can store up to 15MB/file (30/MB file with an account).
FraudLabs Pro — Screen an order transaction for credit card payment fraud. This REST API will detect all possible fraud traits based on the input parameters of an order. The Free Micro plan has 500 transactions per month.
Geekflare API - Geekflare API lets you take screenshots, audit websites, TLS scan, DNS lookup, test TTFB, and more. The free plan offers 3,000 API requests.
GeoCod — Free geocoding API: Convert postal addresses into geographic coordinates or convert geographic coordinates into postal addresses (reverse geocoding).
GeoDataSource — Location search service looks up city names using latitude and longitude coordinates. Free API queries up to 500 times per month.
Geolocated.io — IP Geolocation API with multi-continent servers, offering a forever free plan with 60000 requests per month for hobbyists.
Glitterly - Programmatically generate dynamic images from base templates. Restful API and nocode integrations. The free tier comes with 50 images/month and five templates.
GoodData - Data as a Service - Create interactive and insightful dashboards. The free tier comes with five workspaces and 100 MB/workspace.
Hex - a collaborative data platform for notebooks, data apps, and knowledge libraries. Free community version with up to 3 authors and five projects. One compute profile per author with 4GB RAM.
Hook0 - Hook0 is an open-source Webhooks-as-a-service (WaaS) that makes it easy for online products to provide webhooks. Dispatch up to 3,000 events/month with seven days of history retention for free.
Hoppscotch - A free, fast, and beautiful API request builder.
Hybiscus - Build pdf reports using a simple declarative API. The free tier includes up to 100 single-page reports per month with the ability to customize color palettes and fonts.
Invantive Cloud — Access over 70 (cloud)platforms such as Exact Online, Twinfield, ActiveCampaign or Visma using Invantive SQL or OData4 (typically Power BI or Power Query). Includes data replication and exchange. Free plan for developers and implementation consultants. Free for specific platforms with limitations in data volumes.
ipaddress.sh — Simple service to get a public IP address in different formats.
ipbase.com - IP Geolocation API - Forever free plan that spans 150 monthly requests.
IP Geolocation — IP Geolocation API - Forever free plan for developers with 30k requests per month (1k/day) limit.
IP Geolocation API — IP Geolocation API from Abstract - Extensive free plan allowing 20,000 monthly requests.
IP2Location — Freemium IP geolocation service. LITE database is available for free download. Import the database in the server and perform a local query to determine the city, coordinates, and ISP information.
IP2Location.io — Freemium, fast and reliable IP geolocation API to determine geolocation data like city, coordinates, ISP, etc. The free plan is available with 30k credits per month. Subscribe to paid plans for more advanced features or contact us for a personalized plan.
ipapi - IP Address Location API by Kloudend, Inc - A reliable geolocation API built on AWS, trusted by Fortune 500. The free tier offers 30k lookups/month (1k/day) without signup.
ipapi.is - A reliable IP Address API from Developers for Developers with the best Hosting Detection capabilities that exist. The free plan offers 1000 lookups without signup.
IPinfo — Fast, accurate, and free (up to 50k/month) IP address data API. Offers APIs with details on geolocation, companies, carriers, IP ranges, domains, abuse contacts, and more. All paid APIs can be trialed for free.
BigDataCloud - Provides fast, accurate, and free (Unlimited or up to 10K-50K/month) APIs for modern web like IP Geolocation, Reverse Geocoding, Networking Insights, Email and Phone Validation, Client Info and more.
IPTrace — An embarrassingly simple API that provides your business with reliable and helpful IP geolocation data.
JSON2Video - A video editing API to automate video marketing and social media videos, programmatically or with no code.
JSON IP — Returns the Public IP address of the client it is requested from. No registration is required for the free tier. Using CORS, data can be requested using client-side JS directly from the browser. Useful for services monitoring change in client and server IPs. Unlimited Requests.
JSON Serve — A free service that helps developers to store JSON objects and use that JSON as a REST API in their app.
JSONing — Create a fake REST API from a JSON object, and customize HTTP status codes, headers, and response bodies.
konghq.com — API Marketplace and powerful private and public API tools. With the free tier, some features such as monitoring, alerting, and support, are limited.
Kreya — Free gRPC GUI client to call and test gRPC APIs. Can import gRPC APIs via server reflection.
Lightly — Improve your machine-learning models by using the correct data. Use datasets of up to 1000 samples for free.
LoginLlama - A login security API to detect fraudulent and suspicious logins and notify your customers. Free for 1,000 logins per month.
MailboxValidator — Email verification service using real mail server connection to confirm valid email. The free API plan has 300 verifications per month.
Market Data API - Provides real-time and historical financial data for stocks, options, mutual funds, and more. The Free Forever API tier allows for 100 daily API requests at no charge.
Meteosource Weather API — global weather API for current and forecasted weather data. Forecasts are based on a machine learning combination of more weather models to achieve better accuracy. The free plan comes with 400 calls per day.
microlink.io – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities, or screenshots as a service. One hundred reqs/day, every day free.
Mindee – Mindee is a powerful OCR software and an API-first platform that helps developers automate applications' workflows by standardizing the document processing layer through data recognition for key information using computer vision and machine learning. The free tier offers 250 pages per month.
Mintlify — Modern standard for API documentation. Beautiful and easy-to-maintain UI components, in-app search, and interactive playground. Free for 1 editor.
monkeylearn.com — Text analysis with machine learning, free 300 queries/month.
MockAPI — MockAPI is a simple tool that lets you quickly mock up APIs, generate custom data, and perform operations using a RESTful interface. MockAPI is meant to be a prototyping/testing/learning tool. One project/4 resources per project for free.
Mockfly — Mockfly is a trusted development tool for API mocking and feature flag management. Quickly generate and control mock APIs with an intuitive interface. The free tier offers 500 requests per day.
Mocki - A tool that lets you create mock GraphQL and REST APIs synced to a GitHub repository. Simple REST APIs are free to develop and use without signup.
Mocko.dev — Proxy your API, choose which endpoints to mock in the cloud and inspect traffic, for free. Speed up your development and integration tests.
Mocky - A simple web app to generate custom HTTP responses for mocking HTTP requests. Also available as open source.
reqres.in - A Free hosted REST-API ready to respond to your AJAX requests.
microenv.com — Create fake REST API for developers with the possibility to generate code and app in a docker container.
Multi-Exit IP Address Checker — A free and simple tool to check your exit IP address across multiple nodes and understand how your IP appears to different global regions and services. Useful for testing rule-based DNS splitting tools such as Control D.
neptune.ai - Log, store, display, organize, compare, and query all your MLOps metadata. Free for individuals: 1 member, 100 GB of metadata storage, 200h of monitoring/month
News API — Search news on the web with code, and get JSON results. Developers get 3,000 queries free each month.
GoCardless — Free open banking data API. PSD2. Connect 2300+ banks with your app/software in EU+UK.
Nyckel — Train, deploy, and invoke image and text ML models. Free training with up to 5,000 pieces of training data. 1000 model invokes per month free.
Observable — a place to create, collaborate, and learn with data. Free: Unlimited notebooks, Unlimited publishing, Five editors per notebook.
OCR.Space — An OCR API parses image and pdf files that return the text results in JSON format. Twenty-five thousand requests per month are free.
Duply.co — Create dynamic images from API & URL, design template once and reuse it. The free tier offers 70 images/month creation from API & URL and Up to 100 through Form.
OpenAPI3 Designer — Visually create Open API 3 definitions for free.
parsehub.com — Extract data from dynamic sites, turn dynamic websites into APIs, five projects free.
pdfEndpoint.com - Effortlessly convert HTML or URLs to PDF with a simple API. One hundred conversions per month for free.
PDF-API.io - PDF Automation API, visual template editor or HTML to PDF, dynamic data integration, and PDF rendering with an API. The free plan comes with one template, 100 PDFs/month.
Pixela - Free daystream database service. All operations are performed by API. Visualization with heat maps and line graphs is also possible.
Postbacks - Request HTTP callbacks for a later time. Eight thousand free requests on signup.
Postman — Simplify workflows and create better APIs – faster – with Postman, a collaboration platform for API development. Use the Postman App for free forever. Postman cloud features are also free forever with certain limits.
Insomnia - Open-source API client for designing and testing APIs, it supports REST and GraphQL
PrefectCloud — A complete platform for dataflow automation. All plans include 20,000 free runs every month. That's enough to power ETL for most small businesses.
Preset Cloud - A hosted Apache Superset service. Forever free for teams of up to 5 users, featuring unlimited dashboards and charts, a no-code chart builder, and a collaborative SQL editor.
PromptLeo - Prompt engineering platform for creators and developers. It offers a prompt engineering library, forms, and API. The free plan provides one prompt formation, one prompt API endpoint, and 30 generations per month.
PromptLoop - Use AI and large language models like GPT-3 with a simple spreadsheet formula to transform, comprehend, and analyze text in Google Sheets. The first 2,000 credits are free each month.
Crawlbase — Crawl and scrape websites without proxies, infrastructure, or browsers. We solve captchas for you and prevent you from being blocked. The first 1000 calls are free of charge.
Public-Apis Github Repo — A list of free public APIs.
Supportivekoala — Allows you to autogenerate images by your input via templates. The free plan allows you to create up to 100 images per week.
QuickMocker — Manage online fake API endpoints under your own subdomain, forward requests to localhost URL for webhooks development and testing, use RegExp and multiple HTTP methods for URL path, prioritize endpoints, more than 100 shortcodes (dynamic or fake response values) for response templating, import from OpenAPI (Swagger) Specifications in JSON format, proxy requests, restrict endpoint by IP address and authorization header. The free account provides one random subdomain, ten endpoints, 5 RegExp URL paths, 50 shortcodes per endpoint, 100 requests per day, and 50 history records in the requests log.
Rapidapi - World’s Largest API Hub Millions of developers find and connect to thousands of APIs, API Development using fun challenges (with solutions!) and interactive examples.
RequestBin.com — Create a free endpoint to which you can send HTTP requests. Any HTTP requests sent to that endpoint will be recorded with the associated payload and headers so you can observe recommendations from webhooks and other services.
Roboflow - create and deploy a custom computer vision model with no prior machine learning experience required. The free tier includes up to 1,000 free source images.
ROBOHASH - Web service to generate unique and cool images from any text.
SaturnCloud - Data science cloud environment that allows running Jupyter notebooks and Dask clusters. Thirty hours of free computation and 3 hours of Dask per month.
Scraper's Proxy — Simple HTTP proxy API for scraping. Scrape anonymously without having to worry about restrictions, blocks, or captchas. First 100 successful scrapes per month free including javascript rendering (more available if you contact support).
ScrapingAnt — Headless Chrome scraping API and free checked proxies service. Javascript rendering, premium rotating proxies, CAPTCHAs avoiding. Free plans are available.
ScraperBox — Undetectable web scraping API using real Chrome browsers and proxy rotation. Use a simple API call to scrape any web page. The free plan has 1000 requests per month.
ScrapingDog — Scrapingdog handles millions of proxies, browsers, and CAPTCHAs to provide you with the HTML of any web page in a single API call. It also includes Web Scraper for Chrome & Firefox and software for instant scraping demand. Free plans are available.
scrapinghub.com — Data scraping with visual interface and plugins. The free plan includes unlimited scraping on a shared server.
Simplescraper — Trigger your webhook after each operation. The free plan includes 100 cloud scrape credits.
Select Star - is an intelligent data discovery platform that automatically analyzes and documents your data. Free light tier with 1 Data Source, up to 100 Tables and 10 Users.
Sheetson - Instantly turn any Google Sheets into a RESTful API. Free plan available.
Shipyard — Low-code data orchestration platform for the cloud. Build with a mix of low-code templates and your code (Python, Node.js, Bash, SQL). Our free developer plan offers 10 hours of runtime every month for one user - more than enough to automate multiple workflows.
shrtcode API - Free URL Shortening API without authorization and no request limits.
SerpApi - Real-time search engine scraping API. Returns structured JSON results for Google, YouTube, Bing, Baidu, Walmart, and many other machines. The free plan includes 100 successful API calls per month.
SmartParse - SmartParse is a data migration and CSV to API platform that offers time- and cost-saving developer tools. The Free tier includes 300 Processing Units per month, Browser uploads, Data quarantining, Circuit breakers, and Job Alerts.
Sofodata - Create secure RESTful APIs from CSV files. Upload a CSV file and instantly access the data via its API allowing faster application development. The free plan includes 2 APIs and 2,500 API calls per month. You don't need a credit card.
Sqlable - A collection of free online SQL tools, including an SQL formatter and validator, SQL regex tester, fake data generator, and interactive database playgrounds.
Stoplight - Saas for collaboratively designing and documenting for APIs. The free plan offers free design, mocking, and documentation tools.
Svix - Webhooks as a Service. Send up to 50,000 messages/month for free.
TemplateTo - Auto-Generate PDF/TXT documents from reusable templates with our drop-and-drop editor and simple API. The free plan comes with 450 PDFs/month and three templates.
TinyMCE - rich text editing API. Core features are free for unlimited usage.
Treblle - Treblle helps teams build, ship, and govern APIs. With advanced API log aggregation, observability, docs, and debugging. You get all features for free, but there is a limit of up to 250k requests per month on the free tier.
Webhook Store - Tool for storing third-party webhooks and debug them on localhost (ngrok style). Open source and self-hostable. Free personal domain username.github.webhook.store, free public domains anything.webhook.store.
Weights & Biases — The developer-first MLOps platform. Build better models faster with experiment tracking, dataset versioning, and model management. Free tier for personal projects only, with 100 GB of storage included.
wit.ai — NLP for developers.
wolfram.com — Built-in knowledge-based algorithms in the cloud.
wrapapi.com — Turn any website into a parameterized API. 30k API calls per month.
ZenRows — Web Scraping API & proxy server that bypasses any anti-bot solution while offering javascript rendering, rotating proxies, and geotargeting. The free tier of 1000 API calls.
Zenscrape — Web scraping API with headless browsers, residentials IPs, and straightforward pricing. One thousand free API calls/month and extra credits for students and non-profits.
ip-api — IP Geolocation API, Free for non-commercial use, no API key required, limited to 45 req/minute from the same IP address for the free plan.
WebScraping.AI - Simple Web Scraping API with built-in parsing, Chrome rendering, and proxies. Two thousand free API calls per month.
Zipcodebase - Free Zip Code API, access to Worldwide Postal Code Data. Ten thousand free requests/month.
huggingface.co - Build, train, and deploy NLP models for Pytorch, TensorFlow, and JAX. Free up to 30k input characters/mo.
vatcheckapi.com - Simple and free VAT number validation API. Five hundred free requests per month.
numlookupapi.com - Free phone number validation API - 100k free requests / month.
Volca - Free API providing lists of technologies such as programming languages and database systems. Unlimited free requests.
Query.me - Collaborative data notebooks that execute script-like and allow to fetch and send data via SQL, API, and many custom blocks, like Slack and Email. Free for small Teams.
ERD Lab — Free cloud-based entity relationship diagram (ERD) tool made for developers.
What The Diff - AI-powered code review assistant. The free plan has a limit of 25,000 monthly tokens (~10 PRs).
Zipcodestack - Free Zip Code API and Postal Code Validation. Ten thousand free requests/month.
OpenWeb Ninja - Extremely comprehensive real-time SERP and public data APIs: Google Search, Shopping, Jobs, Images, Lens, News, Google Maps Businesses / Places, Reviews, Photos, Website Emails and Social Contacts Scraper, Amazon, Yelp and more. All APIs include a free tier with 100 to 200 free monthly requests.
Tavily AI - API for online serach and rapid insights and comprehensive research, with the capability of organization of research results. 1000 request/month for the Free tier with No credit card required.
Composio - Integration platform for AI Agents and LLMs. Integrate over 200+ tools across the agentic internet.
WeatherXu — Global weather data including current conditions, hourly and daily forecasts, and weather alerts via our API. Integrating AI models and ML systems to analyze and combine multiple weather models to deliver improved forecast accuracy. Free tier includes 10,000 API calls/month.
Zuplo - Free API Management platform to design, build, and deploy APIs to the Edge. Add API Key authentication, rate limiting, developer documentation and Monetization to any API in minutes. OpenAPI-native and fully-programmable with web standard apis & Typescript. The free plan offers up to 10 projects, unlimited production edge environments, 250 API keys, 100K monthly requests, and 1GB egress.
⬆️ Back to Top

Artifact Repos
Artifactory - An artifact repository that supports numerous package formats like Maven, Docker, Cargo, Helm, PyPI, CocoaPods, and GitLFS. Includes package scanning tool XRay and CI/CD tool Pipelines (formerly Shippable) with a free tier of 2,000 CI/CD minutes per month.
central.sonatype.org — The default artifact repository for Apache Maven, SBT, and other build systems.
cloudrepo.io - Cloud-based, private and public, Maven and PyPi repositories. Free for open-source projects.
cloudsmith.io — Simple, secure, and centralized repository service for Java/Maven, RedHat, Debian, Python, Ruby, Vagrant, and more. Free tier + free for open source.
jitpack.io — Maven repository for JVM and Android projects on GitHub, free for public projects.
packagecloud.io — Easy to use repository hosting for Maven, RPM, DEB, PyPi, NPM, and RubyGem packages (has free tier).
repsy.io — 1 GB Free private/public Maven Repository.
Gemfury — Private and public artifact repos for Maven, PyPi, NPM, Go Module, Nuget, APT, and RPM repositories. Free for public projects.
paperspace — Build & scale AI models, Develop, train, and deploy AI applications, free plan: public projects, 5Gb storage, basic instances.
RepoForge - Private cloud-hosted repository for Python, Debian, NPM packages and Docker registries. Free plan for open source/public projects.
RepoFlow - RepoFlow Simplifies package management with support for npm, PyPI, Docker, Go, Helm, and more. Try it for free with 10GB storage, 10GB bandwidth, 100 packages, and unlimited users in the cloud, or self-hosted for personal use only.
⬆️ Back to Top

Tools for Teams and Collaboration
3Cols - A free cloud-based code snippet manager for personal and collaborative code.
Bitwarden — The easiest and safest way for individuals, teams, and business organizations to store, share, and sync sensitive data.
Braid — Chat app designed for teams. Free for public access group, unlimited users, history, and integrations. also, it provides a self-hostable open-source version.
cally.com — Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
Calendly — Calendly is the tool for connecting and scheduling meetings. The free plan provides 1 Calendar connection per user and Unlimited sessions. Desktop and Mobile apps are also offered.
Discord — Chat with public/private rooms. Markdown text, voice, video, and screen sharing capabilities. Free for unlimited users.
Telegram — Telegram is for everyone who wants fast, reliable messaging and calls. Business users and small teams may like the large groups, usernames, desktop apps, and powerful file-sharing options.
Dubble — Free Step-by-Step Guide creator. Take screenshots, document processes and colloborate with your team. Also supports async screen recording.
Duckly — Talk and collaborate in real time with your team. Pair programming with IDE, terminal sharing, voice, video, and screen sharing. Free for small teams.
Dyte - The most developer-friendly live video & audio SDK, featuring collaborative plugins to enhance productivity and engagement. The free tier includes monthly 10,000 minutes of live video/audio usage.
evernote.com — Tool for organizing information. Share your notes and work together with others
Fibery — Connected workspace platform. Free for single users, up to 2 GB disk space.
flock.com — A faster way for your team to communicate. Free Unlimited Messages, Channels, Users, Apps & Integrations
Gather - A better way to meet online. Centered around fully customizable spaces, Gather makes spending time with your communities just as easy as real life. Free for up to 10 concurrent users.
gokanban.io - Syntax-based, no registration Kanban Board for fast use. Free with no limitations.
flat.social - Interactive customizable spaces for team meetings & happy hours socials. Unlimited meetings, free up to 8 concurrent users.
GitDailies - Daily reports of your team's Commit and Pull Request activity on GitHub. Includes Push visualizer, peer recognition system, and custom alert builder. The free tier has unlimited users, three repos, and 3 alert configs.
gitter.im — Chat, for GitHub. Unlimited public and private rooms, free for teams of up to 25
Hackmd.io - Real time collaboration & writing tool for markdown format docs/files. Like Google Docs but for markdown files. Free unlimited number of "notes", but the number of collaborators (invitee) for private notes & template will be limited.
hangouts.google.com — One place for all your conversations, for free, need a Google account
HeySpace - Task management tool with chat, calendar, timeline and video calls. Free for up to 5 users.
helplightning.com — Help over video with augmented reality. Free without analytics, encryption, support
ideascale.com — Allow clients to submit ideas and vote, free for 25 members in 1 community
Igloo — Internal portal for sharing documents, blogs, calendars, etc. Free for up to 10 users.
Keybase — Keybase is a FOSS alternative to Slack; it keeps everyone's chats and files safe, from families to communities to companies.
Google Meet — Use Google Meet for your business's online video meeting needs. Meet provides secure, easy-to-join online meetings.
/meet for Slack - Start Google Meetings directly from Slack by using /meet in any channel, group, or DM. Free without any limitations.
Livecycle — Livecycle is an inclusive collaboration platform that makes workflows frictionless for cross-functional product teams and open-source projects.
Lockitbot — Reserve and lock shared resources within Slack like Rooms, Dev environments , servers etc. Free for upto 2 resources
MarkUp — MarkUp lets you collect feedback directly on top of your websites, PDFs and images.
Proton Pass — Password manager with built-in email aliases, 2FA authenticator, sharing and passkeys. Available on web, browser extension, and mobile app and desktop.
Visual Debug - A Visual feedback tool for better client-dev communication
meet.jit.si — One-click video conversations, and screen sharing, for free
Microsoft Teams — Microsoft Teams is a chat-based digital hub that brings conversations, content, and apps together in one place all from a single experience. Free for up to 500k users.
Miro - Scalable, secure, cross-device, and enterprise-ready collaboration whiteboard for distributed teams. With a freemium plan.
nootiz - The go-to tool for gathering and managing visual feedback on any website
Notion - Notion is a note-taking and collaboration application with markdown support that integrates tasks, wikis, and databases. The company describes the app as an all-in-one workspace for note-taking, project management and task management. In addition to cross-platform apps, it can be accessed via most web browsers.
Nuclino - A lightweight and collaborative wiki for all your team's knowledge, docs, and notes. Free plan with all essential features, up to 50 items, and 5GB storage.
OnlineInterview.io - Free code interview platform with embedded video chat, drawing board, and online code editor where you can compile and run your code on the browser. You can create a remote interview room with just one click.
Quidlo Timesheets - A simple timesheet and time tracking app for teams. The free plan has time tracking and generating reports features for up to 10 users.
PageShare.dev - Adds visual review capabilities into GitHub Pull Requests with no need to deploy websites. Free for up to 10 pages each month and 100MB of storage in total.
Pendulums - Pendulums is a free time tracking tool that helps you manage your time in a better manner with an easy-to-use interface and valuable statistics.
Pumble - Free team chat app. Unlimited users and message history, free forever.
Raindrop.io - Private and secure bookmarking app for macOS, Windows, Android, iOS, and Web. Free Unlimited Bookmarks and Collaboration.
element.io — A decentralized and open-source communication tool built on Matrix. Group chats, direct messaging, encrypted file transfers, voice and video chats, and easy integration with other services.
Rocket.Chat - Open-source communication platform with Omnichannel features, Matrix Federation, Bridge with others apps, Unlimited messaging, and Full messaging history.
seafile.com — Private or cloud storage, file sharing, sync, discussions. The cloud version has just 1 GB
Sema - Free developer portfolio tool able to consolidate and snapshot contributions across multiple repositories into a single report.
Screen Sharing via Browser - Free screen sharing tool, share your screen with collabrators right from your browser, no download or registration needed. For free.
Slab — A modern knowledge management service for teams. Free for up to 10 users.
slack.com — Free for unlimited users with some feature limitations
Spectrum - Create public or private communities for free.
StatusPile - A status page of status pages. Could you track the status pages of your upstream providers?
Stickies - Visual collaboration app used for brainstorming, content curation, and notes. Free for up to 3 Walls, unlimited users, and 1 GB storage.
Stacks - Content workspace with integrated notes, links, and file storage to navigate information overload. Forever free personal plan.
talky.io — Free group video chat. Anonymous. Peer‑to‑peer. No plugins, signup, or payment required
Teamhood - Free Project, Task, and Issue-tracking software. Supports Kanban with Swimlanes and full Scrum implementation. Has integrated time tracking. Free for five users and three project portfolios.
Teamplify - improve team development processes with Team Analytics and Smart Daily Standup. Includes full-featured Time Off management for remote-first teams. Free for small groups of up to 5 users.
Tefter - Bookmarking app with a powerful Slack integration. Free for open-source teams.
TeleType — share terminals, voice, code, whiteboard, and more. no sign-in is required for end-to-end encrypted collaboration for developers.
TimeCamp - Free time tracking software for unlimited users. Easily integrates with PM tools like Jira, Trello, Asana, etc.
Teamcamp - All-in-one project management application for software development companies.
twist.com — An asynchronous-friendly team communication app where conversations stay organized and on-topic. Free and Unlimited plans are available. Discounts are provided for eligible teams.
tldraw.com — Free open-source white-boarding and diagramming tool with intelligent arrows, snapping, sticky notes, and SVG export features. Multiplayer mode for collaborative editing. Free official VS Code extension available as well.
BookmarkOS.com - Free all-on-one bookmark manager, tab manager, and task manager in a customizable online desktop with folder collaboration.
typetalk.com — Share and discuss ideas with your team through instant messaging on the web or your mobile
Tugboat - Preview every pull request, automated and on-demand. Free for all, complimentary Nano tier for non-profits.
whereby.com — One-click video conversations, for free (formerly known as appear.in)
windmill.dev - Windmill is an open-source developer platform to quickly build production-grade multi-step automation and internal apps from minimal Python and Typescript scripts. As a free user, you can create and be a member of at most three non-premium workspaces.
vadoo.tv — Video hosting and marketing made simple. Upload videos with a single click. Record, manage, share & more. The free tier provides up to 10 videos, 1 GB of storage, and 10 GB of bandwidth/per month
userforge.com - Interconnected online personas, user stories and context mapping. Helps keep design and dev in sync free for up to 3 personas and two collaborators.
wistia.com — Video hosting with viewer analytics, HD video delivery, and marketing tools to help understand your visitors, 25 videos, and Wistia branded player
wormhol.org — Straightforward file sharing service. Share unlimited files up to 5GB with as many peers as you want.
Wormhole - Share files up to 5GB with end-to-end encryption for up to 24hours. For files larger than 5 GB, it uses peer-to-peer transfer to send your files directly.
zoom.us — Secure Video and Web conferencing add-ons available. The free plan is limited to 40 minutes.
Zulip — Real-time chat with a unique email-like threading model. The free plan includes 10,000 messages of search history and File storage up to 5 GB. also, it provides a self-hostable open-source version.
robocorp.com - Open-source stack for powering Automation Ops. Try out Cloud features and implement simple automation for free. Robot work 240 min/month, 10 Assistant runs, Storage of 100 MB.
Fleep.io — Fleep an alternative to Slack. It has a free plan for small teams with full message history, unlimited 1:1 conversations, 1 group conversation, and 1 GB file storage.
Chanty.com — Chanty is another alternative to Slack. It has a free forever plan for small teams (up to 10) with unlimited public and private conversations, searchable history, unlimited 1:1 audio calls, unlimited voice messages, ten integrations, and 20 GB storage per team.
ruttl.com — The best all-in-one feedback tool to collect digital feedback and review websites, PDFs, and images.
Mattermost — Secure collaboration for technical teams. Free plan with unlimited channels, playbooks, boards, users, 10GB storage, and more.
Webvizio — Website feedback tool, website review software, and bug reporting tool for streamlining web development collaboration on tasks directly on live websites and web apps, images, PDFs, and design files.
Pullflow — Pullflow offers an AI-enhanced platform for code review collaboration across GitHub, Slack, and VS Code.
Webex — Video meetings with a free plan offering 40 minutes per meeting with 100 attendees.
RingCentral — Video meetings with a free plan offering 50 minutes per meeting with 100 participants.
GitBook — Platform for capturing and documenting technical knowledge — from product docs to internal knowledge bases and APIs. Free plan for individual developers.
transfernow — simplest, fastest and safest interface to transfer and share files. Send photos, videos and other large files without a manditory subscription.
paste.sh — This is a JavaScript and the Crypto based simple paste site.
Revolt.chat — An OpenSource alternative forDiscord, that respects your privacy. It also have most proprietary features from discord for free. Revolt is a all in one application that is secure and fast, while being 100% free. every features are free. They also have (official & unofficial) plugins support unlike most main-stream chatting applications.
Tencent RTC — Tencent Real-Time Communication (TRTC) offers solutions for group audio/video calls.10,000 free minutes/month for the first year.
Pastefy - Beautiful and simple Pastebin with optional Client-Encryption, Multitab-Pastes, an API, a highlighted Editor and more.
SiteDots - Share feedback for website projects directly on your website, no emulation, canvas or workarounds. Completely functional free tier.
⬆️ Back to Top

CMS
acquia.com — Hosting for Drupal sites. Free tier for developers. Free development tools (such as Acquia Dev Desktop) are also available.
Contentful — Headless CMS. Content management and delivery APIs in the cloud. Comes with one free Community space that includes five users, 25K records, 48 Content Types, 2 locales.
Cosmic — Headless CMS and API toolkit. Free personal plans for developers.
Crystallize — Headless PIM with ecommerce support. Built-in GraphQL API. The free version includes unlimited users, 1000 catalog items, 5 GB/month bandwidth, and 25k/month API calls.
DatoCMS - Offers free tier for small projects. DatoCMS is a GraphQL-based CMS. On the lower tier, you have 100k/month calls.
Directus — Headless CMS. A completely free and open-source platform for managing assets and database content on-prem or in the Cloud. There are no limitations or paywalls.
FrontAid — Headless CMS that stores JSON content directly in your Git repository. No restrictions.
kontent.ai - A Content-as-a-Service platform that gives you all the headless CMS benefits while empowering marketers at the same time. The developer plan provides two users with unlimited projects with two environments for each, 500 content items, two languages with Delivery and Management API, and Custom elements support. You can use more detailed plans to meet your needs.
Prismic — Headless CMS. Content management interface with fully hosted and scalable API. The Community Plan provides unlimited API calls, documents, custom types, assets, and locales to one user. Everything that you need for your next project. Bigger free plans are available for Open Content/Open Source projects.
Sanity.io - Platform for structured content with an open-source editing environment and a real-time hosted data store. Unlimited projects. Unlimited admin users, three non-admin users, two datasets, 500K API CDN requests, 10GB bandwidth, and 5GB assets included for free per project.
sensenet - API-first headless CMS providing enterprise-grade solutions for businesses of all sizes. The Developer plan provides three users, 500 content items, three built-in roles, 25+5 content types, fully accessible REST API, document preview generation, and Office Online editing.
TinaCMS — Replacing Forestry.io. Open source Git-backed headless CMS that supports Markdown, MDX, and JSON. The basic offer is free with two users available.
GatsbyjsCMS - Gatsby is the fast and flexible framework that makes building websites with any CMS, API, or database fun again. Build and deploy headless websites that drive more traffic, convert better, and earn more revenue!
Hygraph - Offers free tier for small projects. GraphQL first API. Move away from legacy solutions to the GraphQL native Headless CMS - and deliver omnichannel content API first.
Squidex - Offers free tier for small projects. API / GraphQL first. Open source and based on event sourcing (versing every change automatically).
InstaWP - Launch a WordPress site in a few seconds. A free tier with 5 Active Sites, 500 MB Space, 48 hrs Site Expiry.
Storyblok - A Headless CMS for developers and marketers that works with all modern frameworks. The Community (free) tier offers Management API, Visual Editor, ten sources, Custom Field Types, Internationalization (unlimited languages/locales), Asset Manager (up to 2500 assets), Image Optimizing Service, Search Query, Webhook + 250GB Traffic/month included.
WPJack - Set up WordPress on any cloud in less than 5 minutes! The free tier includes 1 server, 2 sites, free SSL certificates, and unlimited cron jobs. No time limits or expirations—your website, your way.
⬆️ Back to Top

Code Generation
Appinvento — AppInvento is a free No code app builder. In the automatically generated backend code, users have complete access to the source code and unlimited APIs and routes, allowing for extensive integration. The free plan includes three projects, five tables, and a Google add-on.
Cody AI - Cody is a coding AI assistant that uses AI and a deep understanding of your codebase to help you write and understand code faster. Cody gives developers a choice of LLMs (including local inference), has support for various IDEs, supports all popular programming languages, and has a free plan. The free plan gives developers 20 chat messages (using Claude 3 Sonnet as the LLM) and 500 autocompletions (using the Starcoder 16b) each month.
DhiWise — Seamlessly turn Figma designs into dynamic Flutter & React applications with DhiWise's innovative code generation technology, optimizing your workflow and helping you craft exceptional mobile and web experiences faster than ever before.
Codeium — Codeium is a free AI-powered code completion tool. It supports over 20+ programming languages (Python, JavaScript, Java, TypeScript, PHP, C/C++, Go, etc.) and integrates with all significant standalone and web IDEs.
Fern - Write API definitions and use them to generate SDKs/client libraries in popular languages such as TypeScript, Python, Java, Go, and more. OpenAPI fully supported. Free tier generates code for up to a max of 20 endpoints.
Metalama - Only for C#. Metalama generates the boilerplate of the code on the fly during compilation so that your source code remains clean. It is free for open-source projects, and its commercial-friendly free tier includes three aspects.
Supermaven — Supermaven is a fast AI code completion plugin for VSCode, JetBrains, and Neovim. Free tier provides unlimited inline completions.
tabnine.com — Tabnine helps developers create better software faster by providing insights learned from all the code in the world. Plugin available.
v0.dev — v0 uses AI models to generate code based on simple text prompts. It generates copy-and-paste friendly React code based on shadcn/ui and Tailwind CSS that people can use in their projects. Each generation takes at minimum 30 credits. You start up with 1200 credits, and get 200 free credits every month.
⬆️ Back to Top

Code Quality
beanstalkapp.com — A complete workflow to write, review, and deploy code), a free account for one user, and one repository with 100 MB of storage
browserling.com — Live interactive cross-browser testing, free only 3 minutes sessions with MS IE 9 under Vista at 1024 x 768 resolution
codacy.com — Automated code reviews for PHP, Python, Ruby, Java, JavaScript, Scala, CSS, and CoffeeScript, free for unlimited public and private repositories
Codeac.io - Automated Infrastructure as Code review tool for DevOps integrates with GitHub, Bitbucket, and GitLab (even self-hosted). In addition to standard languages, it also analyzes Ansible, Terraform, CloudFormation, Kubernetes, and more. (open-source free)
CodeBeat — Automated Code Review Platform available for many languages. Free forever for public repositories with Slack and e-mail integration.
codeclimate.com — Automated code review, free for Open Source and unlimited organisation-owned private repos (up to 4 collaborators). Also free for students and institutions.
codecov.io — Code coverage tool (SaaS), free for Open Source and one free private repo
CodeFactor — Automated Code Review for Git. The free version includes unlimited users, public repositories, and one private repo.
coderabbit.ai — AI-powered code review tool that integrates with GitHub/GitLab. Free tier includes 200 files/hour, 3 reviews per hour, and 50 conversations/hour. Free forever for open source projects.
codescene.io - CodeScene prioritizes technical debt based on how the developers work with the code and visualizes organizational factors like team coupling and system mastery. Free for Open Source.
CodSpeed - Automate performance tracking in your CI pipelines. Catch performance regressions before deployment, thanks to precise and consistent metrics. Free forever for Open Source projects.
coveralls.io — Display test coverage reports, free for Open Source
dareboost - 5 free analysis reports for web performance, accessibility, and security each month
deepcode.ai — DeepCode finds bugs, security vulnerabilities, performance and API issues based on AI. DeepCode's speed of analysis allows us to analyze your code in real time and deliver results when you hit the save button in your IDE. Supported languages are Java, C/C++, JavaScript, Python, and TypeScript. Integrations with GitHub, BitBucket, and GitLab. Free for open source and private repos and up to 30 developers.
deepscan.io — Advanced static analysis for automatically finding runtime errors in JavaScript code, free for Open Source
DeepSource - DeepSource continuously analyzes source code changes, finding and fixing issues categorized under security, performance, anti-patterns, bug-risks, documentation, and style. Native integration with GitHub, GitLab, and Bitbucket.
DiffText - Instantly find the differences between two blocks of code. Completely free to use.
eversql.com — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries automatically.
gerrithub.io — Gerrit code review for GitHub repositories for free
gocover.io — Code coverage for any Go package
goreportcard.com — Code Quality for Go projects, free for Open Source
gtmetrix.com — Reports and thorough recommendations to optimize websites
holistic.dev - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
houndci.com — Comments on GitHub commits about code quality, free for Open Source
Moderne.io — Automatic source code refactoring. Moderne offers framework migrations, code analysis with remediation, and unrivaled code transformation at scale, so developers can spend their time building new things instead of maintaining the old. Free for Open Source.
reviewable.io — Code review for GitHub repositories, free for public or personal repos.
parsers.dev - Abstract syntax tree parsers and intermediate representation compilers as a service
scan.coverity.com — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
scrutinizer-ci.com — Continuous inspection platform, free for Open Source
semanticdiff.com — Programming language aware diff for GitHub pull requests and commits, free for public repositories
shields.io — Quality metadata badges for open source projects
sonarcloud.io — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
SourceLevel — Automated Code Review and Team Analytics. Free for Open Source and organizations up to 5 collaborators.
webceo.com — SEO tools but with also code verifications and different types of devices
zoompf.com — Fix the performance of your web sites, detailed analysis
⬆️ Back to Top

Code Search and Browsing
libraries.io — Search and dependency update notifications for 32 different package managers, free for open source
Namae - Search various websites like GitHub, Gitlab, Heroku, Netlify, and many more for the availability of your project name.
searchcode.com — Comprehensive text-based code search, free for Open Source
tickgit.com — Surfaces TODO comments (and other markers) to identify areas of code worth returning to for improvement.
CodeKeep - Google Keep for Code Snippets. Organize, Discover, and share code snippets, featuring a powerful code screenshot tool with preset templates and a linking feature.
⬆️ Back to Top

CI and CD
AccessLint — AccessLint brings automated web accessibility testing into your development workflow. It's free for open source and education purposes.
appcircle.io — An enterprise-grade mobile DevOps platform that automates the build, test, and publish store of mobile apps for faster, efficient release cycle. Free for 30 minutes max build time per build, 20 monthly builds and 1 concurrent build.
appveyor.com — CD service for Windows, free for Open Source
Argonaut - Deploy apps and infrastructure on your cloud in minutes. Support for custom and third-party app deployments on Kubernetes and Lambda environments. The free tier allows unlimited apps and deployments for 5 domains and 2 users.
bitrise.io — A CI/CD for mobile apps, native or hybrid. With 200 free builds/month 10 min build time and two team members. OSS projects get 45 min build time, +1 concurrency and unlimited team size.
buddy.works — A CI/CD with five free projects and one concurrent run (120 executions/month)
Buildkite CI Pipelines free for 3 users and 5k job minutes/month. Test Analytics free developer tier includes 100k test executions/month, with more free inclusions for open-source projects.
bytebase.com — Database CI/CD and DevOps. Free under 20 users and ten database instances
CircleCI — Comprehensive free plan with all features included in a hosted CI/CD service for GitHub, GitLab, and BitBucket repositories. Multiple resource classes, Docker, Windows, Mac OS, ARM executors, local runners, test splitting, Docker Layer Caching, and other advanced CI/CD features. Free for up to 6000 minutes/month execution time, unlimited collaborators, 30 parallel jobs in private projects, and up to 80,000 free build minutes for Open Source projects.
cirrus-ci.org - Free for public GitHub repositories
cirun.io - Free for public GitHub repositories
codefresh.io — Free-for-Life plan: 1 build, one environment, shared servers, unlimited public repos
codemagic.io - Free 500 build minutes/month
codeship.com — 100 private builds/month, five private projects, unlimited for Open Source
deploybot.com — 1 repository with ten deployments, free for Open Source
deployhq.com — 1 project with ten daily deployments (30 build minutes/month)
drone - Drone Cloud enables developers to run Continuous Delivery pipelines across multiple architectures - including x86 and Arm (both 32-bit and 64-bit) - all in one place
LayerCI — CI for full stack projects. One full stack preview environment with 5GB memory & 3 CPUs.
semaphoreci.com — Free for Open Source, 100 private builds per month
Squash Labs — creates a VM for each branch and makes your app available from a unique URL, Unlimited public & private repos, Up to 2 GB VM Sizes.
styleci.io — Public GitHub repositories only
Mergify — workflow automation and merge queue for GitHub — Free for public GitHub repositories
Make — The workflow automation tool lets you connect apps and automate workflows using UI. It supports many apps and the most popular APIs. Free for public GitHub repositories, and free tier with 100 Mb, 1000 Operations, and 15 minutes of minimum interval.
Spacelift - Management platform for Infrastructure as Code. Free plan features: IaC collaboration, Terraform module registry, ChatOps integration, Continuous resource compliance with Open Policy Agent, SSO with SAML 2.0, and access to public worker pools: up to 200 minutes/month
microtica.com - Startup environments with ready-made infrastructure components, deploy apps on AWS for free, and support your production workloads. The free tier includes 1 Environment (on your AWS account), 2 Kubernetes Services, 100 build minutes per month, and 20 monthly deployments.
Nx Cloud - Nx Cloud speeds up your monorepos on CI with features such as remote caching, distribution of tasks across machines and even automated splitting of your e2e test runs. It comes with a free plan for up to 30 contributors with generous 150k credits included.
blacksmith - Managed performance runners for GitHub Actions that provides 3,000 free minutes per month, with no credit card needed.
Terramate - Terramate is an orchestration and management platform for Infrastructure as Code (IaC) tools such as Terraform, OpenTofu, and Terragrunt. Free up to 2 users including all features.
⬆️ Back to Top

Testing
Applitools.com — Smart visual validation for web, native mobile and desktop apps. Integrates with almost all automation solutions (like Selenium and Karma) and remote runners (Sauce Labs, Browser Stack). free for open source. A free tier for a single user with limited checkpoints per week.
Appetize — Test your Android & iOS apps on this Cloud Based Android Phone / Tablets emulator and iPhone/iPad simulators directly in your browser. The free tier includes two concurrent session with 30 minutes of usage per month. No limit on app size.
Apptim — A mobile testing tool that enables people without performance engineering skills to evaluate an app's performance and user experience (UX). A desktop version using your own device is 100% FREE, with unlimited tests on both iOS and Android.
Argos - Open Source visual testing for developers. Unlimitedprojects, with 5,000 screenshots per month. Free for open-source projects.
Bencher - A continuous benchmarking tool suite to catch CI performance regressions. Free for all public projects.
browserstack.com — Manual and automated browser testing, free for Open Source
BugBug - Lightweight test automation tool for web applications. It is easy to learn and doesn't require coding. You can run unlimited tests on your own computer for free. You also get cloud monitoring and CI/CD integration for an additional monthly fee.
Checkly - Code-first synthetic monitoring for modern DevOps. Monitor your APIs and apps at a fraction of the price of legacy providers. Powered by a Monitoring as Code workflow and Playwright. Generous free tier for devs.
checkbot.io — Browser extension that tests if your website follows 50+ SEO, speed and security best practices. Free tier for smaller websites.
cypress.io - Fast, easy and reliable testing for anything that runs in a browser. Cypress Test Runner is always free and open-source with no restrictions and limitations. Cypress Dashboard is free for open-source projects for up to 5 users.
Cypress Recorder by Preflight - Create AI-powered Cypress Tests/POM models on your browser. It's open-source, except for the AI part. It's free for five monthly test creations with Self-healing scripts, Email, and Visual testing.
everystep-automation.com — Records and replays all steps made in a web browser and creates scripts, free with fewer options
Gremlin — Gremlin's Chaos Engineering tools allow you to safely and securely inject failure into your systems to find weaknesses before they cause customer-facing issues. Gremlin Free provides access to Shutdown and CPU attacks on up to 5 hosts or containers.
gridlastic.com — Selenium Grid testing with a free plan of up to 4 simultaneous selenium nodes/10 grid starts/4,000 test minutes/month
katalon.com - Provides a testing platform that can help teams of all sizes at different levels of testing maturity, including Katalon Studio, TestOps (+ Visual Testing free), TestCloud, and Katalon Recorder.
Keploy - Keploy is a functional testing toolkit for developers. Recording API calls generates E2E tests for APIs (KTests) and mocks or stubs(KMocks). It is free for Open Source projects.
knapsackpro.com - Speed up your tests with optimal test suite parallelization on any CI provider. Split Ruby, JavaScript tests on parallel CI nodes to save time. Free plan for up to 10 minutes of test files and free unlimited plan for Open Source projects.
lambdatest.com — Manual, visual, screenshot, and automated browser testing on selenium and cypress, free for Open Source
loadmill.com - Automatically create API and load tests by analyzing network traffic. Simulate up to 50 concurrent users for up to 60 minutes for free monthly.
lost-pixel.com - holistic visual regression testing for your Storybook, Ladle, Histoire stories and Web Apps. Unlimited team members, totally free for open-source, 7,000 snapshots/month.
octomind.dev - Auto-generated, run and maintained Playwright UI tests with AI-assisted test case generation
percy.io - Add visual testing to any web app, static site, style guide, or component library. Unlimited team members, Demo app, and unlimited projects, 5,000 snapshots/month.
preflight.com - No-code automated web testing. Record tests on your browser that are resilient to UI changes and run them on Windows machines. Could you integrate with your CI/CD? The free plan includes 50 monthly test runs with video, HTML sessions, and more.
qase.io - Test management system for Dev and QA teams. Manage test cases, compose test runs, perform tests, track defects, and measure impact. The free tier includes all core features, with 500MB available for attachments and up to 3 users.
Repeato No-code mobile app test automation tool built on top of computer vision and AI. Works for native apps, flutter, react-native, web, ionic, and many more app frameworks. The free plan is limited to 10 tests for iOS and 10 for Android, but includes most of the features of the paid plans, including unlimited test runs.
Requestly Open-source Chrome Extension to Intercept, Redirect and Mock HTTP Requests. Featuring Debugger, Mock Server, API Client and Session Recording. Redirect URLs, Modify HTTP Headers, Mock APIs, Inject custom JS, Modify GraphQL Requests, Generate Mock API Endpoints, Record session with Network & Console Logs. Create upto 10 rules in Free Tier. Free for open-source.
seotest.me — Free on-page SEO website tester. 10 free website crawls per day. Useful SEO learning resources and recommendations on how to improve the on-page SEO results for any website regardless of technology.
snippets.uilicious.com - It's like CodePen but for cross-browser testing. UI-licious lets you write tests like user stories and offers a free platform - UI-licious Snippets - that allows you to run unlimited tests on Chrome with no sign-up required for up to 3 minutes per test run. Found a bug? You can copy the unique URL to your test to show your devs exactly how to reproduce the bug.
TestCollab - A user-friendly test management software, its free plan includes Jira integration, unlimited projects, test case import using CSV/XLSx, time tracking, and 1 GB file storage.
testingbot.com — Selenium Browser and Device Testing, free for Open Source
Testspace.com - A Dashboard for publishing automated test results and a Framework for implementing manual tests as code using GitHub. The service is free for Open Source and accounts for 450 monthly results.
tesults.com — Test results reporting and test case management. Integrates with popular test frameworks. Open Source software developers, individuals, educators, and small teams getting started can request discounted and free offerings beyond basic free projects.
UseWebhook.com - Capture and inspect webhooks from your browser. Forward to localhost, or replay from history. Free to use.
Vaadin — Build scalable UIs in Java or TypeScript, and use the integrated tooling, components, and design system to iterate faster, design better, and simplify the development process. Unlimited Projects with five years of free maintenance.
websitepulse.com — Various free network and server tools.
webhook-test.com - Debug and inspect webhooks and HTTP requests with a unique URL during integration. Completely free, you can create unlimited URLs and receive recommendations.
webhook.site - Verify webhooks, outbound HTTP requests, or emails with a custom URL. A temporary URL and email address are always free.
webhookbeam.com - Set up webhooks and monitor them via push notifications and emails.
⬆️ Back to Top

Security and PKI
aikido.dev — All-in-one appsec platform covering SCA, SAST, CSPM, DAST, Secrets, IaC, Malware, Container scanning, EOL,... Free plan includes two users, scanning of 10 repos, 1 cloud, 2 containers & 1 domain.
alienvault.com — Uncovers compromised systems in your network
Altcha.org - A Spam Filter for websites and APIs powered by natural language processing and machine learning. Free plan includes 200 requests a day per domain.
atomist.com — A quicker and more convenient way to automate various development tasks. Now in beta.
cloudsploit.com — Amazon Web Services (AWS) security and compliance auditing and monitoring
Public Cloud Threat Intelligence — High confidence Indicator of Compromise(IOC) targeting public cloud infrastructure, A portion is available on github (https://github.com/unknownhad/AWSAttacks). Full list is available via API
CodeNotary.io — Open Source platform with indelible proof to notarize code, files, directories, or container
crypteron.com — Cloud-first, developer-friendly security platform prevents data breaches in .NET and Java applications
CyberChef — A simple, intuitive web app for analyzing and decoding/encoding data without dealing with complex tools or programming languages. Like a Swiss army knife of cryptography & encryption. All features are free to use, with no limit. Open source if you wish to self-host.
DAS — Styra DAS Free, Full lifecycle policy management to create, deploy and manage Open Policy Agent(OPA) authorization
Datree — Open Source CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies
Dependabot Automated dependency updates for Ruby, JavaScript, Python, PHP, Elixir, Rust, Java (Maven and Gradle), .NET, Go, Elm, Docker, Terraform, Git Submodules, and GitHub Actions.
DJ Checkup — Scan your Django site for security flaws with this free, automated checkup tool. Forked from the Pony Checkup site.
Doppler — Universal Secrets Manager for application secrets and config, with support for syncing to various cloud providers. Free for five users with basic access controls.
Dotenv — Sync your .env files, quickly & securely. Stop sharing your .env files over insecure channels like Slack and email, and never lose an important .env file again. Free for up to 3 teammates.
GitGuardian — Keep secrets out of your source code with automated secrets detection and remediation. Scan your git repos for 350+ types of secrets and sensitive files – Free for individuals and teams of 25 developers or less.
Have I been pwned? — REST API for fetching the information on the breaches.
hostedscan.com — Online vulnerability scanner for web applications, servers, and networks. Ten free scans per month.
Infisical — Open source platform that lets you manage developer secrets across your team and infrastructure: everywhere from local development to staging/production 3rd-party services. Free for up to 5 developers.
Internet.nl — Test for modern Internet Standards like IPv6, DNSSEC, HTTPS, DMARC, STARTTLS and DANE
keychest.net - SSL expiry management and cert purchase with an integrated CT database
letsencrypt.org — Free SSL Certificate Authority with certs trusted by all major browsers
meterian.io - Monitor Java, Javascript, .NET, Scala, Ruby, and NodeJS projects for security vulnerabilities in dependencies. Free for one private project, unlimited projects for open source.
Mozilla Observatory — Find and fix security vulnerabilities in your site.
opswat.com — Security Monitoring of computers, devices, applications, configurations, Free 25 users and 30 days history users.
openapi.security - Free tool to quickly check the security of any OpenAPI / Swagger-based API. You don't need to sign up.
pixee.ai - Automated Product Security Engineer as a free GitHub bot that submits PRs to your Java code base to automatically resolve vulnerabilities. Other languages coming soon!
pyup.io — Monitor Python dependencies for security vulnerabilities and update them automatically. Free for one private project, unlimited projects for open source.
qualys.com — Find web app vulnerabilities, audit for OWASP Risks
report-uri.io — CSP and HPKP violation reporting
ringcaptcha.com — Tools to use the phone number as id, available for free
seclookup.com - Seclookup APIs can enrich domain threat indicators in SIEM, provide comprehensive information on domain names, and improve threat detection & response. Get 50K lookups free here.
snyk.io — Can find and fix known security vulnerabilities in your open-source dependencies. Unlimited tests and remediation for open-source projects. Limited to 200 tests/month for your private projects.
ssllabs.com — Intense analysis of the configuration of any SSL web server
SOOS - Free, unlimited SCA scans for open-source projects. Detect and fix security threats before release. Protect your projects with a simple and effective solution.
StackHawk Automate application scanning throughout your pipeline to find and fix security bugs before they hit production. Unlimited scans and environments for a single app.
Sucuri SiteCheck - Free website security check and malware scanner
Protectumus - Free website security check, site antivirus, and server firewall (WAF) for PHP. Email notifications for registered users in the free tier.
TestTLS.com - Test an SSL/TLS service for secure server configuration, certificates, chains, etc. Not limited to HTTPS.
threatconnect.com — Threat intelligence: It is designed for individual researchers, analysts, and organizations starting to learn about cyber threat intelligence. Free up to 3 Users
tinfoilsecurity.com — Automated vulnerability scanning. The free plan allows weekly XSS scans
Ubiq Security — Encrypt and decrypt data with three lines of code and automatic key management. Free for one application and up to 1,000,000 encryptions per month.
Virgil Security — Tools and services for implementing end-to-end encryption, database protection, IoT security, and more in your digital solution. Free for applications with up to 250 users.
Vulert - Vulert continuously monitors your open-source dependencies for new vulnerabilities, recommends fixes, without requiring installation or access to your codebase. Free for open-source projects.
Escape GraphQL Quickscan - One-click security scan of your GraphQL endpoints. Free, no login required.
HasMySecretLeaked - Search across 20 million exposed secrets in public GitHub repositories, gists, issues,and comments for Free
⬆️ Back to Top

Authentication, Authorization, and User Management
Aserto - Fine-grained authorization as a service for applications and APIs. Free up to 1000 MAUs and 100 authorizer instances.
asgardeo.io - Seamless Integration of SSO, MFA, passwordless auth and more. Includes SDKs for frontend and backend apps. Free up to 1000 MAUs and five identity providers.
Auth0 — Hosted SSO. The free plan includes 25,000 MAUs, unlimited Social Connections, a custom domain, and more.
Authgear - Bring Passwordless, OTPs, 2FA, SSO to your apps in minutes. All Front-end included. Free up to 5000 MAUs.
Authress — Authentication login and access control, unlimited identity providers for any project. Facebook, Google, Twitter and more. The first 1000 API calls are free.
Authy - Two-factor authentication (2FA) on multiple devices, with backups. Drop-in replacement for Google Authenticator. Free for up to 100 successful authentications.
Cerbos Hub - A complete authorization management system for authoring, testing, and deploying access policies. Fine-grained authorization and access control, free up to 100 monthly active principals.
Clerk — User management, authentication, 2FA/MFA, prebuilt UI components for sign-in, sign-up, user profiles, and more. Free up to 10,000 monthly active users.
Cloud-IAM — Keycloak Identity and Access Management as a Service. Free up to 100 users and one realm.
Corbado — Add passkey-first authentication to new or existing apps. Free for unlimited MAUs.
Descope — Highly customizable AuthN flows, has both a no-code and API/SDK approach, Free 7,500 active users/month, 50 tenants (up to 5 SAML/SSO tenants).
duo.com — Two-factor authentication (2FA) for website or app. Free for ten users, all authentication methods, unlimited, integrations, hardware tokens.
Kinde - Simple, robust authentication you can integrate with your product in minutes. Everything you need to get started with 7,500 free MAU.
logintc.com — Two-factor authentication (2FA) by push notifications, free for ten users, VPN, Websites, and SSH
MojoAuth - MojoAuth makes it easy to implement Passwordless authentication on your web, mobile, or any application in minutes.
Okta — User management, authentication and authorization. Free for up to 100 monthly active users.
onelogin.com — Identity as a Service (IDaaS), Single Sign-On Identity Provider, Cloud SSO IdP, three company apps, and five personal apps, unlimited users
Ory - AuthN/AuthZ/OAuth2.0/Zero Trust managed security platform. Forever free developer accounts with all security features, unlimited team members, 200 daily active users, and 25k/mo permission checks.
Phase Two - Keycloak Open Source Identity and Access Management. Free realm up to 1000 users, up to 10 SSO connections, leveraging Phase Two's Keycloak enhanced container which includes the Organization extension.
Stytch - An all-in-one platform that provides APIs and SDKs for authentication and fraud prevention. The free plan includes 10,000 monthly active users, unlimited organizations, 5 SSO or SCIM connections, and 1,000 M2M tokens.
Stack Auth — Open-source authentication that doesn't suck. The most developer-friendly solution, getting you started in just five minutes. Self-hostable for free, or offers a managed SaaS version with 10k free Monthly Active Users.
SuperTokens - Open source user authentication that natively integrates into your app - enabling you to get started quickly while controlling the user and developer experience. Free for up to 5000 MAUs.
Warrant — Hosted enterprise-grade authorization and access control service for your apps. The free tier includes 1 million monthly API requests and 1,000 authz rules.
ZITADEL Cloud — A turnkey user and access management that works for you and supports multi-tenant (B2B) use cases. Free for up to 25,000 authenticated requests, with all security features (no paywall for OTP, Passwordless, Policies, and so on).
PropelAuth — A Sell to companies of any size immediately with a few lines of code, free up to 200 users and 10k Transactional Emails (with a watermark branding: "Powered by PropelAuth").
Logto - Develop, secure, and manage user identities of your product - for both authentication and authorization. Free for up to 5,000 MAUs with open-source self-hosted option available.
WorkOS - Free user management and authentication for up to 1 Million MAUs. Support email + password, social auth, Magic Auth, MFA, and more.
⬆️ Back to Top

Mobile App Distribution and Feedback
TestApp.io - Your go-to platform for ensuring your mobile apps work as they should. Free plan: one app, analytics, unlimited versions & installs, and feedback collection.
Loadly - iOS & Android beta apps distribution service offers completely free services with unlimited downloads, high-speed downloads, and unlimited uploads.
Diawi - Deploy iOS & Android apps directly to devices. Free plan: app uploads, password-protected links, 1-day expiration, ten installations.
InstallOnAir - Distribute iOS & Android apps over the air. Free plan: unlimited uploads, private links, 2-day expiration for guests, 60 days for registered users.
GetUpdraft - Distribute mobile apps for testing. The free plan includes one app project, three app versions, 500 MB storage, and 100 app installations per month.
Appho.st - Mobile app hosting platform. The free plan includes five apps, 50 monthly downloads, and a maximum file size of 100 MB.
⬆️ Back to Top

Management System
bitnami.com — Deploy prepared apps on IaaS. Management of 1 AWS micro instance free
Esper — MDM and MAM for Android Devices with DevOps. One hundred devices free with one user license and 25 MB Application Storage.
jamf.com — Device management for iPads, iPhones, and Macs, three devices free
Miradore — Device Management service. Stay up-to-date with your device fleet and secure unlimited devices for free. The free plan offers basic features.
moss.sh - Help developers deploy and manage their web apps and servers. Free up to 25 git deployments per month
runcloud.io - Server management focusing mainly on PHP projects. Free for up to 1 server.
ploi.io - Server management tool to easily manage and deploy your servers & sites. Free for one server.
⬆️ Back to Top

Messaging and Streaming
Ably - Realtime messaging service with presence, persistence and guaranteed delivery. The free plan includes 3m messages per month, 100 peak connections, and 100 peak channels.
cloudamqp.com — RabbitMQ as a Service. Little Lemur plan: max 1 million messages/month, max 20 concurrent connections, max 100 queues, max 10,000 queued messages, multiple nodes in different AZ's
courier.com — Single API for push, in-app, email, chat, SMS, and other messaging channels with template management and other features. The free plan includes 10,000 messages/mo.
engagespot.co — Multi-channel notification infrastructure for developers with a prebuilt in-app inbox and no-code template editor. Free plan includes 10,000 messages/mo.
HiveMQ - Connect your MQTT devices to the Cloud Native IoT Messaging Broker. Free to connect up to 100 devices (no credit card required) forever.
knock.app – Notifications infrastructure for developers. Send to multiple channels like in-app, email, SMS, Slack, and push with a single API call. The free plan includes 10,000 messages/mo.
NotificationAPI.com — Add user notifications to any software in 5 minutes. The free plan includes 10,000 notifications/month + 100 SMS and Automated Calls.
Novu.co — The open-source notification infrastructure for developers. Simple components and APIs for managing all communication channels in one place: Email, SMS, Direct, In-App and Push. The free plan includes 30,000 notifications/month with 90 days of retention.
pusher.com — Realtime messaging service. Free for up to 100 simultaneous connections and 200,000 messages/day
scaledrone.com — Realtime messaging service. Free for up to 20 simultaneous connections and 100,000 events/day
synadia.com — NATS.io as a service. Global, AWS, GCP, and Azure. Free forever with 4k msg size, 50 active connections, and 5GB of data per month.
cloudkarafka.com - Free Shared Kafka cluster, up to 5 topics, 10MB data per topic and 28 days of data retention.
pubnub.com - Swift, Kotlin, and React messaging at 1 million transactions each month. Transactions may contain multiple messages.
eyeson API - A video communication API service based on WebRTC (SFU, MCU) to build video platforms. Allows real-time data Injection, Video Layouts, Recordings, a fully featured hosted web UI (quickstart) or packages for custom UIs. Has a free tier for developers with 1000 meeting minutes a month.
webpushr - Web Push Notifications - Free for upto 10k subscribers, unlimited push notifications, in-browser messaging
httpSMS - Send and receive text messages using your Android phone as an SMS Gateway. Free to send and receive up to 200 messages per month.
EMQX Serverless - Scalable and secure serverless MQTT broker you can get in seconds. 1M session minutes/month free forever (no credit card required).
Pocket Alert - Send push notifications to your iOS and Android devices. Effortlessly integrate via API or Webhooks and maintain full control over your alerts. Free plan: 50 messages per day to 1 device and 1 application.
⬆️ Back to Top

Log Management
bugfender.com — Free up to 100k log lines/day with 24 hours retention
logentries.com — Free up to 5 GB/month with seven days retention
loggly.com — Free for a single user, 200MB/day with seven days retention
logz.io — Free up to 1 GB/day, one day retention
ManageEngine Log360 Cloud — Log Management service powered by Manage Engine. Free Plan offers 50 GB storage with 15 days Storage Retention and 7 days search.
papertrailapp.com — 48 hours search, seven days archive, 50 MB/month
sematext.com — Free up to 500 MB/day, seven days retention
sumologic.com — Free up to 500 MB/day, seven days retention
logflare.app — Free for up to 12,960,000 entries per app per month, 3 days retention
logtail.com — ClickHouse-based SQL-compatible log management. Free up to 1 GB per month, three days retention.
logzab.com — Audit trail management system. Free 1,000 user activity logs per month, 1-month retention, for up to 5 projects.
openobserve.ai - 200 GB Ingestion/month free, 15 Days Retention
⬆️ Back to Top

Translation Management
crowdin.com — Unlimited projects, unlimited strings, and collaborators for Open Source
gitlocalize.com - Free and unlimited for both private and public repositories
Lecto - Machine Translation API with Free tier (30 free requests, 1000 translated characters per request). Integrated with the Loco Translate Wordpress plugin.
lingohub.com — Free up to 3 users, always free for Open Source
localazy.com - Free for 1000 source language strings, unlimited languages, unlimited contributors, startup and open source deals
Localeum - Free up to 1000 strings, one user, unlimited languages, unlimited projects
localizely.com — Free for Open Source
Loco — Free up to 2000 translations, Unlimited translators, ten languages/project, 1000 translatable assets/project
oneskyapp.com — Limited free edition for up to 5 users, free for Open Source
POEditor — Free up to 1000 strings
SimpleLocalize - Free up to 100 translation keys, unlimited strings, unlimited languages, startup deals
Texterify - Free for a single user
Tolgee - Free SaaS offering with limited translations, forever-free self-hosted version
transifex.com — Free for Open Source
Translation.io - Free for Open Source
Translized - Free up to 1000 strings, one user, unlimited languages, unlimited projects
webtranslateit.com — Free up to 500 strings
weblate.org — It's free for libre projects with up to 10,000 string sources for the free tier and Unlimited Self-hosted on-premises.
Free PO editor — Free for everybody
⬆️ Back to Top

Monitoring
UptimeObserver.com - Get 20 uptime monitors with 5-minute intervals and a customizable status page—even for commercial use. Enjoy unlimited, real-time notifications via email and Telegram. No credit card needed to get started.
Pingmeter.com - 5 uptime monitors with 10-minute interval. Monitor SSH, HTTP, HTTPS, and any custom TCP ports.
alerty.ai - Free APM and monitoring for your FE, BE, DB, and more + free agent runs.
appdynamics.com — Free for 24-hour metrics, application performance management agents limited to one Java, one .NET, one PHP, and one Node.js
appneta.com — Free with 1-hour data retention
appspector.com - Mission control for remote iOS/Android/Flutter debugging. Free for small traffic usage (64MB of logs).
assertible.com — Automated API testing and monitoring. Free plans for teams and individuals.
bleemeo.com - Free for 3 servers, 5 uptime monitors, unlimited users, unlimited dashboards, unlimited alerting rules.
checklyhq.com - Open source E2E / Synthetic monitoring and deep API monitoring for developers. Free plan with five users and 50k+ check runs.
cloudsploit.com — AWS security and configuration monitoring. Free: unlimited on-demand scans, unlimited users, unlimited stored accounts. Subscription: automated scanning, API access, etc.
cronitor.io - Performance insights and uptime monitoring for cron jobs, websites, APIs and more. A free tier with five monitors.
datadoghq.com — Free for up to 5 nodes
deadmanssnitch.com — Monitoring for cron jobs. One free snitch (monitor), more if you refer others to sign up
downtimemonkey.com — 60 uptime monitors, 5-minute interval. Email, Slack alerts.
economize.cloud — Economize helps demystify cloud infrastructure costs by organizing cloud resources to optimize and report the same. Free for up to $5,000 spent on Google Cloud Platform every month.
elastic.co — Instant performance insights for JS developers. Free with 24-hour data retention
Grafana Cloud - Grafana Cloud is a composable observability platform that integrates metrics and logs with Grafana. Free: 3 users, ten dashboards, 100 alerts, metrics storage in Prometheus and Graphite (10,000 series, 14 days retention), logs storage in Loki (50 GB of logs, 14 days retention)
healthchecks.io — Monitor your cron jobs and background tasks. Free for up to 20 checks.
Hydrozen.io — Uptime monitoring & Status pages, Free plan: 10 Uptime monitor, 5 heartbeat monitors, 1 Domain monitor and 1 Statuspage free.
incidenthub.cloud — Cloud and SaaS status page aggregator - 20 monitors and 2 notification channels (Slack and Discord) are free forever.
inspector.dev - A complete Real-Time monitoring dashboard in less than one minute with a free forever tier.
instrumentalapp.com - Beautiful and easy-to-use application and server monitoring with up to 500 metrics and 3 hours of data visibility for free
keychest.net/speedtest - Independent speed test and TLS handshake latency test against Digital Ocean
letsmonitor.org - SSL monitoring, free for up to 5 monitors
linkok.com - Online broken link checker, free for small websites up to 100 pages, completely free for open-source projects.
loader.io — Free load testing tools with limitations
netdata.cloud — Netdata is an open-source tool to collect real-time metrics. It's a growing product and can also be found on GitHub!
newrelic.com — New Relic observability platform built to help engineers create more perfect software. From monoliths to serverless, you can instrument everything and then analyze, troubleshoot, and optimize your entire software stack. The free tier offers 100GB/month of free data ingest, one free full-access user, and unlimited free primary users.
Middleware.io - Middleware observability platform provides complete visibility into your apps & stack, so you can monitor & diagnose issues at scale. They have a free forever plan for Dev community use that allows Log monitoring for up to 1M log events, Infrastructure monitoring & APM for up to 2 hosts.
nixstats.com - Free for one server. E-Mail Notifications, public status page, 60-second interval, and more.
OnlineOrNot.com - OnlineOrNot provides uptime monitoring for websites and APIs, monitoring for cron jobs and scheduled tasks. Also provides status pages. The first five checks with a 3-minute interval are free. The free tier sends alerts via Slack, Discord, and Email.
OntarioNet.ca CN Test — Check if a website is blocked in China by the Great Firewall. It identifies DNS pollution by comparing DNS results and ASN information detected by servers in China versus servers in the United States.
opsgenie.com — Powerful alerting and on-call management for operating always-on services. Free up to 5 users.
paessler.com — Powerful infrastructure and network monitoring solution, including alerting, strong visualization capabilities, and basic reporting. Free up to 100 sensors.
pagecrawl.io - Monitor website changes, free for up to 6 monitors with daily checks.
syagent.com — Noncommercial free server monitoring service, alerts and metrics.
pagerly.io - Manage on-calls on Slack (integrates with Pagerduty, OpsGenie). Free up to 1 team (one team refers to one on call)
pagertree.com - Simple interface for alerting and on-call management. Free up to 5 users.
phare.io - Uptime Monitoring free for up to 100,000 events for unlimited projets and unlimited status pages.
pingbreak.com — Modern uptime monitoring service. Check unlimited URLs and get downtime notifications via Discord, Slack, or email.
pingpong.one — Advanced status page platform with monitoring. The free tier includes one public customizable status page with an SSL subdomain. Pro plan is offered to open-source projects and non-profits free of charge.
robusta.dev — Powerful Kubernetes monitoring based on Prometheus. Bring your own Prometheus or install the all-in-one bundle. The free tier includes up to 20 Kubernetes nodes. Alerts via Slack, Microsoft Teams, Discord, and more. Integrations with PagerDuty, OpsGenie, VictorOps, DataDog, and many other tools.
sematext.com — Free for 24-hour metrics, unlimited servers, ten custom metrics, 500,000 custom metrics data points, unlimited dashboards, users, etc.
sitemonki.com — Website, domain, Cron & SSL monitoring, 5 monitors in each category for free
sitesure.net - Website and cron monitoring - 2 monitors free
skylight.io — Free for first 100,000 requests (Rails only)
speedchecker.xyz — Performance Monitoring API, checks Ping, DNS, etc.
stathat.com — Get started with ten stats for free, no expiration
statuscake.com — Website monitoring, unlimited tests free with limitations
statusgator.com — Status page monitoring, 3 monitors free
SweetUptime — Server monitoring, uptime monitoring, DNS & domain monitoring. Monitor 10 server, 10 uptime, and 10 domain for free.
thousandeyes.com — Network and user experience monitoring. 3 locations and 20 data feeds of major web services free
uptimerobot.com — Website monitoring, 50 monitors free
uptimetoolbox.com — Free monitoring for five websites, 60-second intervals, public statuspage.
zenduty.com — End-to-end incident management, alerting, on-call management, and response orchestration platform for network operations, site reliability engineering, and DevOps teams. Free for up to 5 users.
instatus.com - Get a beautiful status page in 10 seconds. Free forever with unlimited subs and unlimited teams.
Squadcast.com - Squadcast is an end-to-end incident management software designed to help you promote SRE best practices. Free forever plan available for up to 10 users.
RoboMiri.com - RoboMiri is a stable uptime monitor that offers a wide range of monitors: cronjob, keyword, website, port, ping. Twenty-five uptime checks with 3-minute interval checks for free. Alerts via Phone Call, SMS, Email, and Webhooks.
Better Stack - Uptime monitoring, incident management, on-call scheduling/alerting, and status pages in a single product. The free plan includes ten monitors with 3-minute check frequency and status pages.
Pulsetic - 10 monitors, 6 Months of historical Uptime/Logs, unlimited status pages, and custom domains included! For infinite time and unlimited email alerts for free. You don't need a credit card.
Wachete - monitor five pages, checks every 24 hours.
Xitoring.com — Uptime monitoring: 20 free, Linux and Windows Server monitoring: 5 free, Status page: 1 free - Mobile app, multiple notification channel, and much more!
⬆️ Back to Top

Crash and Exception Handling
CatchJS.com - JavaScript error tracking with screenshots and click trails. Free for open-source projects.
bugsnag.com — Free for up to 2,000 errors/month after the initial trial
elmah.io — Error logging and uptime monitoring for web developers. Free Small Business subscription for open-source projects.
Embrace — Mobile app monitoring. Free for small teams with up to 1 million user sessions per year.
exceptionless — Real-time error, feature, log reporting, and more. Free for 3k events per month/1 user. Open source and easy to self-host for unlimited use.
GlitchTip — Simple, open-source error tracking. Compatible with open-source Sentry SDKs. 1000 events per month for free, or can self-host with no limits
honeybadger.io - Exception, uptime, and cron monitoring. Free for small teams and open-source projects (12,000 errors/month).
memfault.com — Cloud device observability and debugging platform. 100 devices free for Nordic, NXP, and Laird devices.
rollbar.com — Exception and error monitoring, free plan with 5,000 errors/month, unlimited users, 30 days retention
sentry.io — Sentry tracks app exceptions in real-time and has a small free plan. Free for 5k errors per month/ 1 user, unrestricted use if self-hosted
Axiom — Store up to 0.5 TB of logs with 30-day retention. Includes integrations with platforms like Vercel and advanced data querying with email/Discord notifiers.
Semaphr — Free all-in-one kill switch for your mobile apps.
Jam - Developer friendly bug reports in one click. Free plan with unlimited jams.
Whitespace – One-click bug reports straight in your browser. Free plan with unlimited recordings for personal use.
⬆️ Back to Top

Search
algolia.com — Hosted search solution with typo-tolerance, relevance, and UI libraries to easily create search experiences. The free "Build" plan includes 1M documents and 10K searches/month. Also offers developer documentation search for free.
bonsai.io — Free 1 GB memory and 1 GB storage
CommandBar - Unified Search Bar as-a-service, web-based UI widget/plugin that allows your users to search contents, navigations, features, etc. within your product, which helps discoverability. Free for up to 1,000 Monthly Active Users, unlimited commands.
Magny - SaaS service that helps implement command palettes (e.g. in-app search), which significantly decreases the time users find anything in an app, leveraging the user experience and efficiency.
Orama Cloud — Free 3 indexes, 100K docs/index, unlimited full-text/vector/hybrid searches, 60 days analytics
searchly.com — Free 2 indices and 20 MB storage
⬆️ Back to Top

Education and Career Development
FreeCodeCamp - Open-source platform offering free courses and certifications in Data Analysis, Information Security, Web Development, and more.
The Odin Project - Free, open-source platform with a curriculum focused on JavaScript and Ruby for web development.
Free Professional Resume Templates & Editor - Free platform with lots of Resume templates of Experienced Professionals, ready to clone and edit fully and download, ATS optimized.
DeepLearning.AI Short Courses - Free short courses from industry-leading experts to get hands-on experience with the latest generative AI tools and techniques in an hour or less.
LabEx - Develop skills in Linux, DevOps, Cybersecurity, Programming, Data Science, and more through interactive labs and real-world projects.
Roadmap.sh - Free learning roadmaps covering all aspects of development from Blockchain to UX Design.
Cisco Networking Academy, Skills for All - Offers free certification-aligned courses in topics like cybersecurity, networking, and Python.
MIT OpenCourseWare - MIT OpenCourseWare is an online publication of materials from over 2,500 MIT courses, freely sharing knowledge with learners and educators around the world. Youtube channel can be found at @mitocw
W3Schools - Offers free tutorials on web development technologies like HTML, CSS, JavaScript, and more.
Khan Academy - Free online guides for learning basic and advanced HTML/CSS, JavaScript and SQL.
⬆️ Back to Top

Email
10minutemail - Free, temporary email for testing.
AhaSend - Transactional email service, free for 1000 emails per month, with unlimited domains, team members, webhooks and message routes in the free plan.
AnonAddy - Open-source anonymous email forwarding, create unlimited email aliases for free
Antideo — 10 API requests per hour for email verification, IP, and phone number validation in the free tier. No Credit Cards are required.
Brevo — 9,000 emails/month, 300 emails/day free
OneSignal — 10,000 emails/month,No Credit Cards are required.
Bump - Free 10 Bump email addresses, one custom domain
Burnermail – Free 5 Burner Email Addresses, 1 Mailbox, 7-day Mailbox History
Buttondown — Newsletter service. Up to 100 subscribers free
CloudMailin - Incoming email via HTTP POST and transactional outbound - 10,000 free emails/month
Contact.do — Contact form in a link (bitly for contact forms)
debugmail.io — Easy to use testing mail server for developers
DNSExit - Up to 2 Email addresses under your domain for free with 100MB of storage space. IMAP, POP3, SMTP, SPF/DKIM support.
EmailLabs.io — Send up to 9,000 Emails for free every month, up to 300 emails daily.
EmailOctopus - Up to 2,500 subscribers and 10,000 emails per month free
EmailJS – This is not an entire email server; this is just an email client that you can use to send emails right from the client without exposing your credentials, the free tier has 200 monthly requests, 2 email templates, Requests up to 50Kb, Limited contacts history.
EtherealMail - Ethereal is a fake SMTP service, mainly aimed at Nodemailer and EmailEngine users (but not limited to). It's an entirely free anti-transactional email service where messages never get delivered.
Temp-Mail.org - Temporary / Disposable Mail Gen Utilizing a range variety of domain. Email Address refreshes everytime, the page is reloaded. It is entirely free and does not include any pricing for their services.
TempMailDetector.com - Verify up to 200 emails a month for free and see if an email is temporary or not.
Emailvalidation.io - 100 free email verifications per month
FakeMailGenerator.com - A German Temporary / Disposable Mail generator. Support 10 domain, while giving you the freedom of creating unlimited addresses. (include ads) but other than that, there is no pricing included in the service, it is entirely free.
forwardemail.net — Free email forwarding for custom domains. Create and forward an unlimited amount of email addresses with your domain name (note: You must pay if you use .casa, .cf, .click, .email, .fit, .ga, .gdn, .gq, .lat, .loan, .london, .men, .ml, .pl, .rest, .ru, .tk, .top, .work TLDs due to spam)
Imitate Email - Sandbox Email Server for testing email functionality across build/qa and ci/cd. Free accounts get 15 emails a day forever.
ImprovMX – Free email forwarding.
EForw – Free email forwarding for one domain. Receive and send emails from your domain.
Inboxes App — Create up to 3 temporary emails a day, then delete them when you're done from within a handy Chrome extension. Perfect for testing signup flows.
inboxkitten.com - Free temporary/disposable email inbox, with up to 3-day email auto-deletes. Open source and can be self-hosted.
mail-tester.com — Test if the email's DNS/SPF/DKIM/DMARC settings are correct, 20 free/month.
dkimvalidator.com - Test if the email's DNS/SPF/DKIM/DMARC settings are correct, free service by roundsphere.com
mailcatcher.me — Catches mail and serves it through a web interface.
mailchannels.com - Email API with REST API and SMTP integrations, free for upto 3,000 emails/month.
Mailcheck.ai - Prevent users to sign up with temporary email addresses, 120 requests/hour (~86,400 per month)
Mailchimp — 500 subscribers and 1,000 emails/month free.
Maildroppa - Up to 100 subscribers and unlimited emails as well as automations for free.
MailerLite.com — 1,000 subscribers/month, 12,000 emails/month free
MailerSend.com — Email API, SMTP, 3,000 emails/month free for transactional emails
mailinator.com — Free, public email system where you can use any inbox you want
Mailjet — 6,000 emails/month free (200 emails daily sending limit)
Mailnesia - Free temporary/disposable email, which auto visit registration link.
mailsac.com - Free API for temporary email testing, free public email hosting, outbound capture, email-to-slack/websocket/webhook (1,500 monthly API limit)
Mailtrap.io — Fake SMTP server for development, free plan with one inbox, 100 messages, no team member, two emails/second, no forward rules.
Mail7.io — Free Temp Email Addresses for QA Developers. Create email addresses instantly using Web Interface or API.
Momentary Email — Free Temporary Email Addresses. Read incoming emails on the website or by RSS feed.
Mutant Mail – Free 10 Email IDs, 1 Domain, 1 Mailbox. Single Mailbox for All Email IDs.
Outlook.com - Free personal email and calendar.
Parsio.io — Free email parser (Forward email, extract the data, send it to your server)
pepipost.com — 30k emails free for the first month, then the first 100 emails/day free.
Plunk - 3K emails/month for free
Postmark - 100 emails/month free, unlimited DMARC weekly digests.
Proton Mail - Free secure email account service provider with built-in end-to-end encryption. Free 1GB storage.
Queuemail.dev — Reliable email delivery API. Free tier (10,000 emails/per month). Send asynchronously. Use several SMTP servers. Blocklists, Logging, Tracking, Webhooks, and more.
QuickEmailVerification — Verify 100 emails daily for free on a free tier along with other free APIs like DEA Detector, DNS Lookup, SPF Detector, and more.
Resend - Transactional emails API for developers. 3,000 emails/month, 100 emails/day free, one custom domain.
Sender Up to 15,000 emails/month, up to 2,500 subscribers
SendGrid — 100 emails/day and 2,000 contacts free
Sendpulse — 500 subscribers/month, 15,000 emails/month free
SimpleLogin – Open source, self-hostable email alias/forwarding solution. Free 5 Aliases, unlimited bandwidth, unlimited reply/send. Free for educational staff (student, researcher, etc.).
Substack — Unlimited free newsletter service. Start paying when you charge for it.
Sweego - European transactional emails API for developers. 500 emails/day free.
Takeout - A constantly updated email service that makes sending emails easy. Five hundred transactional emails/month free.
temp-mail.io — Free disposable temporary email service with multiple emails at once and forwarding
tinyletter.com — 5,000 subscribers/month free
Touchlead - A multi-purpose marketing automation tool, with lead management, form builder, and automation. Free for limited number of leads and automations
trashmail.com - Free disposable email addresses with forwarding and automatic address expiration
Tuta - Free secure email account service provider with built-in end-to-end encryption, no ads, no tracking. Free 1GB storage, one calendar (Tuta also have an paid plan.). Tuta is also partially open source, so you can self-host.
Verifalia — Real-time email verification API with mailbox confirmation and disposable email address detector; 25 free email verifications/day.
verimail.io — Bulk and API email verification service. 100 free verifications/month
Zoho — Started as an e-mail provider but now provides a suite of services, some of which have free plans. List of services having free plans :
Email Free for 5 users. 5GB/user & 25 MB attachment limit, one domain.
Zoho Assist — Zoho Assist's forever free plan includes one concurrent remote support license and Access to 5 unattended computer licenses for unlimited duration available for both professional and personnel use.
Sprints Free for 5 users,5 Projects & 500MB storage.
Docs — Free for 5 users with 1 GB upload limit & 5GB storage. Zoho Office Suite (Writer, Sheets & Show) comes bundled.
Projects — Free for 3 users, 2 projects & 10 MB attachment limit. The same plan applies to Bugtracker.
Connect — Team Collaboration free for 25 users with three groups, three custom apps, 3 Boards, 3 Manuals, and 10 Integrations along with channels, events & forums.
Meeting — Meetings with upto 3 meeting participants & 10 Webinar attendees.
Vault — Password Management is accessible for Individuals.
Showtime — Yet another Meeting software for training for a remote session of up to 5 attendees.
Notebook — A free alternative to Evernote.
Wiki — Free for three users with 50 MB storage, unlimited pages, zip backups, RSS & Atom feed, access controls & customizable CSS.
Subscriptions — Recurring Billing management free for 20 customers/subscriptions & 1 user with all the payment hosting done by Zoho. The last 40 subscription metrics are stored
Checkout — Product Billing management with 3 pages & up to 50 payments.
Desk — Customer Support management with three agents, private knowledge base, and email tickets. Integrates with Assist for one remote technician & 5 unattended computers.
Cliq — Team chat software with 100 GB storage, unlimited users, 100 users per channel & SSO.
Campaigns - Email Marketing
Forms - Form Creator
Sign - Paperless Signatures
Surveys - Online Surveys
Bookings - Appointment Scheduling
Maileroo - SMTP relay and email API for developers. 5,000 emails per month, unlimited domains, free email verification, blacklist monitoring, mail tester and more.
⬆️ Back to Top

Feature Toggles Management Platforms
ConfigCat - ConfigCat is a developer-centric feature flag service with unlimited team size, excellent support, and a reasonable price tag. Free plan up to 10 flags, two environments, 1 product, and 5 Million requests per month.
Flagsmith - Release features with confidence; manage feature flags across web, mobile, and server-side applications. Use our hosted API, deploy to your own private cloud, or run on-premise.
GrowthBook - Open source feature flag and A/B testing provider with built-in Bayesian statistical analysis engine. Free for up to 3 users, unlimited feature flags and experiments.
Hypertune - Type-safe feature flags, A/B testing, analytics and app configuration, with Git-style version control and synchronous, in-memory, local flag evaluation. Free for up to 5 team members with unlimited feature flags and A/B tests.
Molasses - Powerful feature flags and A/B testing. Free up to 3 environments with five feature flags each.
Toggled.dev - Enterprise-ready, scalable multi-regional feature toggles management platform. Free plan up to 10 flags, two environments, unlimited requests. SDK, analytics dashboard, release calendar, Slack notifications, and all other features are included in the endless free plan.
Statsig - A robust platform for feature management, A/B testing, analytics, and more. Its generous free plan offers unlimited seats, flags, experiments, and dynamic configurations, supporting up to 1 million events per month.
Abby - Open-Source feature flags & A/B testing. Configuration as Code & Fully Typed Typescript SDKs. Strong integration with Frameworks such as Next.js & React. Generous free tier and cheap scaling options.
⬆️ Back to Top

Font
dafont - The fonts presented on this website are their authors' property and are either freeware, shareware, demo versions, or public domain.
Everything Fonts - Offers multiple tools; @font-face, Units Converter, Font Hinter and Font Submitter.
Font Squirrel - Freeware fonts licensed for commercial work. Hand-selected these typefaces and presented them in an easy-to-use format.
Google Fonts - Many free fonts are easy and quick to install on a website via a download or a link to Google's CDN.
FontGet - Has a variety of fonts available to download and sorted neatly with tags.
Fontshare - is a free fonts service. It’s a growing collection of professional-grade fonts, 100% free for personal and commercial use.
Befonts - Provides several unique fonts for personal or commercial use.
Font of web - Identify all the fonts used on a website and how they are used.
Bunny Privacy oriented Google Fonts
FontsKey - Provides free and commercial paid fonts for personal use and can enter text for quick filtering.
fonts.xz.style free and open source service for delivering font families to websites using CSS.
Fontsensei Opensourced Google fonts tagged by users. With CJK (Chinese,Japanese,Korean) font tags.
⬆️ Back to Top

Forms
Feathery - Powerful, developer-friendly form builder. Build signup & login, user onboarding, payment flows, complex financial applications, and more. The free plan allows up to 250 submissions/month and five active forms.
Form-Data - No-code forms backend. Spam filter, email notification and auto-respond, webhooks, zapier, redirects, AJAX or POST, and more. The free plan offers unlimited forms, 20 submissions/month, and an additional 2000 submissions with Form-Data badge.
FabForm - Form backend platform for intelligent developers. The free plan allows 250 form submissions per month. Friendly modern GUI. Integrates with Google Sheets, Airtable, Slack, Email, and others.
Form.taxi — Endpoint for HTML forms submissions. With notifications, spam blockers, and GDPR-compliant data processing. Free plan for basic usage.
Formcarry.com - HTTP POST Form endpoint, Free plan allows 100 monthly submissions.
formingo.co- Easy HTML forms for static websites. You can start for free without registering an account. The free plan allows 500 monthly submissions and a customizable reply-to email address.
FormKeep.com - Unlimited forms with 50 monthly submissions, spam protection, email notification, and a drag-and-drop designer that can export HTML. Additional features include custom field rules, teams, and integrations to Google Sheets, Slack, ActiveCampaign, and Zapier.
formlets.com — Online forms, unlimited single page forms/month, 100 submissions/month, email notifications.
formspark.io - Form to Email service, free plan allows unlimited forms, 250 submissions per month, support by Customer assistance team.
Formspree.io — Send email using an HTTP POST request. The free tier limits to 50 submissions per form per month.
Formsubmit.co — Easy form endpoints for your HTML forms. Free Forever. No registration is required.
Formlick.com - Typeform alternative with lifetime deal. Users can create 1 free form and receive unlimited submissions. In premium, users can create unlimited forms and unlimited submissions.
getform.io - Form backend platform for designers and developers, 1 form, 50 submissions, Single file upload, 100MB file storage.
HeroTofu.com - Forms backend with bot detection and encrypted archive. Forward submissions via UI to email, Slack, or Zapier. Use your own front end. No server code is required. The free plan gives unlimited forms and 100 submissions per month.
HeyForm.net - Drag and drop online form builder. The free tier lets you create unlimited forms and collect unlimited submissions. Comes with pre-built templates, anti-spam, and 100MB file storage.
Tally.so - 99% of all the features are free. The free tier lets you have: unlimited forms, unlimited submissions, email notifications, form logic, collect payments, file upload, custom thank you page, and many more.
Hyperforms.app — Create a form to email and more in seconds and without backend code. The Personal account gives you up to 50 monthly form submissions for free.
Kwes.io - Feature rich form endpoint. Works great with static sites. The free plan includes up to 1 website with up to 50 monthly submissions.
Pageclip - The free plan allows one site, one form, and 1,000 monthly submissions.
Qualtrics Survey — Create professional forms & survey using this first class tool. 50+ expert-designed survey templates. Free Account has a limit of 1 active survey, 100 responses/survey & 8 response types.
Screeb - In-app surveys and product analytics for decoding user behavior. Forever free plan allows 500 monthly active users, unlimited responses and events, many integrations, export, and periodic reports.
smartforms.dev - Powerful and easy form backend for your website, forever free plan allows 50 submissions per month, 250MB file storage, Zapier integration, CSV/JSON export, custom redirect, custom response page, Telegram & Slack bot, single email notifications.
Survicate — Pull feedback from all sources and send follow-up surveys with one tool. Automatically analyze feedback and extract insights with AI. Free email, website, in-product or mobile surveys, AI survey creator, and 25 monthly responses.
staticforms.xyz - Integrate HTML forms easily without any server-side code for free. After the user submits the form, an email with the form content will be sent to your registered address.
stepFORM.io - Quiz and Form Builder. The free plan has five forms, up to 3 steps per form, and 50 monthly responses.
Typeform.com — Include beautifully designed forms on websites. The free plan allows only ten fields per form and 100 monthly responses.
WaiverStevie.com - Electronic Signature platform with a REST API. You can receive notifications with webhooks. Free plan watermarks signed documents but allow unlimited envelopes + signatures.
Web3Forms - Contact forms for Static & JAMStack Websites without writing backend code. The free plan allows Unlimited Forms, Unlimited Domains & 250 Submissions per month.
WebAsk - Survey and Form Builder. The free plan has three surveys per account, 100 monthly responses, and ten elements per survey.
Wufoo - Quick forms to use on websites. The free plan has a limit of 100 submissions each month.
formpost.app - Free, unlimited Form to Email service. Set up custom redirects, auto-response, webhooks, etc. for free.
Formester.com - Share and embed unique-looking forms on your website—no limits on the number of forms created or features restricted by the plan. Get up to 100 submissions every month for free.
SimplePDF.eu - Embed a PDF editor on your website and turn any PDF into a fillable form. The free plan allows unlimited PDFs with three submissions per PDF.
forms.app — Create online forms with powerful features like conditional logic, automatic score calculator, and AI. Collect up to 100 responses with a free plan, embed your forms on a website, or use them with a link.
Qualli - In App Surveys, designed for mobile. Use Qualli AI to craft the perfect questions. You can try it out on our free plan, up to 500 MAU, create unlimited forms and triggers.
Sprig - 1 In-Product Survey or Survey with Replay per month, with GPT-powered AI Analysis.
feedback.fish - Free plan allows collecting 25 total feedback submissions. Easy to integrate with React and Vue components provided.
⬆️ Back to Top

Generative AI
Keywords AI - The best LLM monitoring platform. One format to call 200+ LLMs with 2 lines of code. 10,000 free requests every month and $0 for platform features!
Portkey - Control panel for Gen AI apps featuring an observability suite & an AI gateway. Send & log up to 10,000 requests for free every month.
Braintrust - Evals, prompt playground, and data management for Gen AI. Free plan gives upto 1,000 private eval rows/week.
Findr - Universal search that lets you search all your apps, at once. Search assistant that lets you answer questions using your information. Free plan offers unlimited unified search and 5 co daily co pilot queries.
ReportGPT - AI Powered Writing Assistant. The entire platform is free as long as you bring your own API key.
Clair - Clinical AI Reference. Students have free access to the professional tool suite, which includes Open Search, Clinical Summary, Med Review, Drug Interactions, ICD-10 Codes, and Stewardship. Additionally, a free trial for the professional suite is available.
Langtrace - enables developers to trace, evaluate, manage prompts and datasets, and debug issues related to an LLM application’s performance. It creates open telemetry standard traces for any LLM which helps with observability and works with any observability client. Free plan offers 50K traces/month.
Ultra AI - AI command center for your product. Features include multi-provider AI gateway, prompts manager, caching, logs, analytics, model fallbacks and user rate limiting. Free forever plan offers 10k+ requests per month and all the features except caching.
Comet Opik - Evaluate, test, and ship LLM applications across your dev and production lifecycles.
Langfuse - Open-source LLM engineering platform that helps teams collaboratively debug, analyze, and iterate on their LLM applications. Free forever plan includes 50k observations per month and all platform features. #opensource
Pollinations.AI - easy-to-use, free image generation AI with free API available. No signups or API keys required, and several option for integrating into a website or workflow. #opensource
⬆️ Back to Top

CDN and Protection
bootstrapcdn.com — CDN for bootstrap, bootswatch and fontawesome.io
cdnjs.com — Simple. Fast. Reliable. Content delivery at its finest. cdnjs is a free and open-source CDN service trusted by over 11% of all websites, powered by Cloudflare.
developers.google.com — The Google Hosted Libraries is a content distribution network for the most popular Open Source JavaScript libraries
Stellate - Stellate is a blazing-fast, reliable CDN for your GraphQL API and free for two services.
jsdelivr.com — A free, fast, and reliable open-source CDN. Supports npm, GitHub, WordPress, Deno, and more.
Microsoft Ajax — The Microsoft Ajax CDN hosts popular third-party JavaScript libraries such as jQuery and enables you to easily add them to your Web application
ovh.ie — Free DDoS protection and SSL certificate
Skypack — The 100% Native ES Module JavaScript CDN. Free for 1 million requests per domain per month.
raw.githack.com — A modern replacement of rawgit.com which simply hosts file using Cloudflare
section.io — A simple way to spin up and manage a complete Varnish Cache solution. Supposedly free forever for one site
statically.io — CDN for Git repos (GitHub, GitLab, Bitbucket), WordPress-related assets, and images
toranproxy.com — Proxy for Packagist and GitHub. Never fail CD. Free for personal use, one developer, no support
UNPKG — CDN for everything on npm
weserv — An image cache & resize service. Manipulate images on the fly with a worldwide cache.
Namecheap Supersonic — Free DDoS protection
Gcore Global content delivery network, 1 TB and 1 million requests per month free and free DNS hosting
CacheFly - Up to 5 TB per month of Free CDN traffic, 19 Core PoPs , 1 Domain and Universal SSL.
⬆️ Back to Top

PaaS
anvil.works - Web app development with nothing but Python. Free tier with unlimited apps and 30-second timeouts.
appwrite - Unlimited projects with no project pausing (supports websockets) and authentication service. 1 Database, 3 Buckets, 5 Functions per project in free tier.
configure.it — Mobile app development platform, free for two projects, limited features but no resource limits
codenameone.com — Open source, cross-platform, mobile app development toolchain for Java/Kotlin developers. Free for commercial use with an unlimited number of projects
deco.cx - Edge-native frontend platform with a visual CMS auto-generated from TypeScript code. Built-in A/B testing, content segmentation, and real-time analytics. Perfect for content-heavy and Enterprise e-commerce websites. Free up to 5k pageviews/month or open-source/personal projects.
Deno Deploy - Distributed system that runs JavaScript, TypeScript, and WebAssembly at the edge worldwide. The free tier includes 100,000 requests per day and 100 GiB data transfers per month.
domcloud.co – Linux hosting service that provides CI/CD with GitHub, SSH, and MariaDB/Postgres database. The free version has 1 GB storage and 1 GB network/month limit and is limited to a free domain.
encore.dev — Backend framework using static analysis to provide automatic infrastructure, boilerplate-free code, and more. Includes free cloud hosting for hobby projects.
flightcontrol.dev - Deploy web services, databases, and more on your own AWS account with a Git push style workflow. Free tier for users with 1 developer on personal GitHub repos. AWS costs are billed through AWS, but you can use credits and the AWS free tier.
gigalixir.com - Gigalixir provides one free instance that never sleeps and a free-tier PostgreSQL database limited to 2 connections, 10, 000 rows and no backups for Elixir/Phoenix apps.
Glitch — Free public hosting with code sharing and real-time collaboration features. The free plan has a 1000-hours/month limit.
Lade - Lade is a cloud platform built for developers. The free tier includes three services, which can be either apps or databases. Each service includes 128 MB RAM and 1 GB storage.
pipedream.com - An integration platform built for developers. Develop any workflow based on any trigger. Workflows are code you can run for free. No server or cloud resources to manage.
pythonanywhere.com — Cloud Python app hosting. Beginner account is free, 1 Python web application at your-username.pythonanywhere.com domain, 512 MB private file storage, one MySQL database
ampt.dev - Ampt lets teams build, deploy, and scale JavaScript apps on AWS without complicated configs or managing infrastructure. Free Preview plan includes 500 invocations hourly, 2,500 invocations daily and 50,000 invocations monthly. Custom domains are allowed only in the paid plans.
Koyeb - Koyeb is a developer-friendly serverless platform to deploy apps globally. Seamlessly run Docker containers, web apps, and APIs with git-based deployment, native autoscaling, a global edge network, and built-in service mesh and discovery. Free Instance lets you deploy a web service in Frankfurt, Germany or Washington, D.C., US. Free Managed Postgres database available in Frankfurt (Germany), Washington, D.C. (US), and Singapore. 512MB memory, 2GB storage, and 0.1 CPU. No credit card is required to get started.
Napkin - FaaS with 500Mb of memory, a default timeout of 15 seconds, and 5,000 free API calls/month rate-limited to 5 calls/second.
Meteor Cloud — Galaxy hosting. Meteor's platform-as-a-service for Meteor apps includes free MongoDB Shared Hosting and automatic SSL.
Northflank — Build and deploy microservices, jobs, and managed databases with a powerful UI, API & CLI. Seamlessly scale containers from version control and external Docker registries. The free tier includes two services, two cron jobs and 1 database.
YepCode - All-in-one platform to connect APIs and services in a serverless environment. It brings all the agility and benefits of NoCode tools but with all the power of using programming languages. The free tier includes 1.000 yeps.
WunderGraph - An open-source platform that allows you to quickly build, ship and manage modern APIs. Built-in CI/CD, GitHub integration, and automatic HTTPS. Up to 3 projects, 1GB egress, 300 minutes of build time per month on the free plan
Zeabur - Deploy your services with one click. Free for three services, with US$ 5 free credits per month.
mogenius - Easily build, deploy, and run services on Kubernetes. The free tier supports connecting a local Kubernetes with mogenius, enabling individual developers to create a production-like test environment on their machine.
genezio - A serverless function provider offers 1 million function calls, 100GB of bandwidth, and 10 cron jobs per month for free, exclusively for non-commercial or academic use.
⬆️ Back to Top

BaaS
Activepieces - Build automation flows to connect several apps together in your app's backend. For example, send a Slack message or add a Google Sheet row when an event fires in your app. Free up to 5,000 tasks per month.
back4app.com - Back4App is an easy-to-use, flexible and scalable backend based on Parse Platform.
backendless.com — Mobile and Web Baas, with 1 GB file storage free, push notifications of 50,000/month, and 1000 data objects in the table.
bismuth.cloud — Our AI will boostrap your Python API on our function runtime and hosted storage, build and host for free in our online editor or locally with your favorite tools.
BMC Developer Program — The BMC Developer Program provides documentation and resources to build and deploy digital innovations for your enterprise. Access to a comprehensive, personal sandbox that includes the platform, SDK, and a library of components that can be used to build and tailor apps.
connectycube.com - Unlimited chat messages, p2p voice & video calls, files attachments and push notifications. Free for apps up to 1000 users.
convex.dev - Reactive backend as a service, hosting your data (documents with relationships & serializable ACID transactions), serverless functions, and WebSockets to stream updates to various clients. Free for small projects - up to 1M records, 5M monthly function calls.
darklang.com - Hosted language combined with editor and infrastructure. Accessible during the beta, a generous free tier is planned after beta.
Firebase — Firebase helps you build and run successful apps. Free Spark Plan offers Authentication, Hosting, Firebase ML, Realtime Database, Cloud Storage, Testlab. A/B Testing, Analytics, App Distribution, App Indexing, Cloud Messaging (FCM), Crashlytics, Dynamic Links, In-App Messaging, Performance Monitoring, Predictions, and Remote Config are always free.
Flutter Flow — Build your Flutter App UI without writing a single line of code. Also has a Firebase integration. The free plan includes full access to UI Builder and Free templates.
getstream.io — Build scalable In-App Chat, Messaging, Video and audio, and Feeds in a few hours instead of weeks
hasura.io — Hasura extends your existing databases wherever it is hosted and provides an instant GraphQL API that can be securely accessed for web, mobile, and data integration workloads. Free for 1GB/month of data pass-through.
iron.io — Async task processing (like AWS Lambda) with free tier and 1-month free trial
nhost.io - Serverless backend for web and mobile apps. The free plan includes PostgreSQL, GraphQL (Hasura), Authentication, Storage, and Serverless Functions.
onesignal.com — Unlimited free push notifications. 10,000 email sends per month, with unlimited contacts and access to Auto Warm Up.
paraio.com — Backend service API with flexible authentication, full-text search and caching. Free for one app, 1GB of app data.
progress.com — Mobile backend, starter plan has unlimited requests/second, with 1 GB of data storage. Enterprise application support
pubnub.com — Free push notifications for up to 1 million messages/month and 100 active daily devices
pushbots.com — Push notification service. Free for up to 1.5 million pushes/month
pushcrew.com — Push notification service. Unlimited notifications for up to 2,000 Subscribers
pusher.com — Free, unlimited push notifications for 2000 monthly active users. A single API for iOS and Android devices.
quickblox.com — A communication backend for instant messaging, video, and voice calling, and push notifications
restspace.io - Configure a server with services for auth, data, files, email API, templates, and more, then compose into pipelines and transform data.
Salesforce Developer Program — Build apps Lightning fast with drag-and-drop tools. Customize your data model with clicks. Go further with Apex code. Integrate with anything using powerful APIs. Stay protected with enterprise-grade security. Customize UI with clicks or any leading-edge web framework. Free Developer Program gives access to the full Lightning Platform.
ServiceNow Developer Program — Rapidly build, test, and deploy applications that make work better for your organization. Free Instance & access to early previews.
simperium.com — Move data everywhere instantly and automatically, multi-platform, unlimited sending and storage of structured data, max. 2,500 users/month
Singlebase.cloud — SinglebaseCloud is an AI-powered all-in-one backend platform to accelerate app development. It offers tools like Vector DB, Relational Document DB, Auth, Search, and Storage, aiming to simplify backend development. Free/Starter Plan offers Relational Document DB, Auth, Search, Storage.
stackstorm.com — Event-driven automation for apps, services, and workflows, free without flow, access control, LDAP
streamdata.io — Turns any REST API into an event-driven streaming API. Free plan up to 1 million messages and ten concurrent connections.
Supabase — The Open Source Firebase Alternative to build backends. Free Plan offers Authentication, Realtime Database & Object Storage.
tyk.io — API management with authentication, quotas, monitoring and analytics. Free cloud offering
zapier.com — Connect the apps you use to automate tasks. Five zaps every 15 minutes and 100 tasks/month
IFTTT — Automate your favorite apps and devices. Free 2 Applets
Integrately — Automate tedious tasks with a single click. Free 100 Tasks, 15 Minute Update Time, five active automations, webhooks.
LeanCloud — Mobile backend. 1GB of data storage, 256MB instance, 3K API requests/day, and 10K pushes/day are free. (API is very similar to Parse Platform)
⬆️ Back to Top

Low-code Platform
Clappia — A low-code platform designed for building business process applications with customizable mobile and web apps. Offers a drag-and-drop interface, features like Offline Support, real-time location tracking and integration with various third-party services.
Basedash — Low-code platform for building internal admin panels and dashboards. Supports SQL databases and REST APIs.
BudiBase — Budibase is an open-source low-code platform for creating internal apps in minutes. Supports PostgreSQL, MySQL, MSSQL, MongoDB, Rest API, Docker, K8s
appsmith — Low code project to build admin panels, internal tools, and dashboards. Integrates with 15+ databases and any API.
ToolJet — Extensible low-code framework for building business applications. Connect to databases, cloud storages, GraphQL, API endpoints, Airtable, etc., and build apps using drag-and-drop application builder.
ReTool — Low-code platform for building internal applications. Retool is highly hackable. If you can write it with JavaScript and an API, you can make it in Retool. The free tier allows up to five users per month, unlimited apps and API connections.
DronaHQ — DronaHQ - a low code platform that helps engineering teams and product managers to build internal tools, custom user journeys, digital experiences, automation, custom admin panels, operational apps 10X faster.
ILLA Cloud — ILLA Cloud - A robust open-source low-code platform for developers to build internal tools. By using ILLA's library of Components and Actions, developers can save massive amounts of time on building tools. Free for 5 team members.
outsystems.com — Enterprise web development PaaS for on-premise or cloud, free "personal environment" offering allows for unlimited code and up to 1 GB database
UI Bakery — Low-code platform that enables faster building of custom web applications. Supports building UI using drag and drop with a high level of customization through JavaScript, Python, and SQL. Available as both cloud and self-hosted solutions. Free for up to 5 users.
Mendix — Rapid Application Development for Enterprises, unlimited accessible sandbox environments supporting total users, 0.5 GB storage and 1 GB RAM per app. Also, Studio and Studio Pro IDEs are allowed in the free tier.
lil'bots - write and run scripts online utlizing free built-in APIs like OpenAI, Anthropic, Firecrawl and others. Great for building AI agents / internal tooling and sharing with team. Free-tier includes full access to APIs, AI coding assistant and 10,000 execution credits / month.
⬆️ Back to Top

Web Hosting
Alwaysdata — 100 MB free web hosting with support for MySQL, PostgreSQL, CouchDB, MongoDB, PHP, Python, Ruby, Node.js, Elixir, Java, Deno, custom web servers, access via FTP, WebDAV and SSH; mailbox, mailing list and app installer included.
Awardspace.com — Free web hosting + a free short domain, PHP, MySQL, App Installer, Email Sending & No Ads.
Bohr — Free for non commercial projects + Developer-First Deployment and Development Platform that minimizes infrastructure hassle and speed up setup.
Bubble — Visual programming to build web and mobile apps without code, free with Bubble branding.
dAppling Network - Decentralized web hosting platform for Web3 frontends focusing on increasing uptime and security and providing an additional access point for users.
DigitalOcean - Build and deploy three static sites for free on the App Platform Starter tier.
Drive To Web — Host directly to the web from Google Drive & OneDrive. Static sites only. Free forever. One site per Google/Microsoft account.
Fenix Web Server - A developer desktop app for hosting sites locally and sharing them publically (in real-time). Work however you like, using its beautiful user interface, API, and/or CLI.
Fern - Build and host a Markdown-based documentation site on Fern's free plan. You can even auto-generate an API reference for your site from API definition files. The site is hosted at yoursite.docs.buildwithfern.com.
Free Hosting — Free Hosting With PHP 5, Perl, CGI, MySQL, FTP, File Manager, POP E-Mail, free sub-domains, free domain hosting, DNS Zone Editor, Web Site Statistics, FREE Online Support and many more features not offered by other free hosts.
Freehostia — FreeHostia offers free hosting services incl. an industry-best Control Panel & a 1-click installation of 50+ free apps. Instant setup. No forced ads.
HelioHost — Non-profit free web hosting with Plesk control panel, PHP, Node.js, Python, Django, Flask, .NET, Perl, CGI, MySQL, PostgreSQL, SQLite, IMAP/POP3/SMTP email, unlimited bandwidth, free subdomains, 1000 MB storage for free with the option to upgrade.
Kinsta Static Site Hosting — Deploy up to 100 static sites for free, custom domains with SSL, 100 GB monthly bandwidth, 260+ Cloudflare CDN locations.
Lecturify - Web hosting with SFPT access for file upload and download, php available.
Neocities — Static, 1 GB free storage with 200 GB Bandwidth.
Netlify — Builds, deploys and hosts static site/app free for 100 GB data and 100 GB/month bandwidth.
pantheon.io — Drupal and WordPress hosting, automated DevOps, and scalable infrastructure. Free for developers and agencies. No custom domain.
readthedocs.org — Free documentation hosting with versioning, PDF generation, and more
render.com — Unified cloud to build and run apps and sites with free SSL, a global CDN, private networks, auto-deploys from Git, and completely free plans for web services, databases, and static web pages.
SourceForge — Find, Create, and Publish Open Source software for free
surge.sh — Static web publishing for Front-End developers. Unlimited sites with custom domain support
telegra.ph Easily create web page using Quill
tilda.cc — One site, 50 pages, 50 MB storage, only the main pre-defined blocks among 170+ available, no fonts, no favicon, and no custom domain
Vercel — Build, deploy, and host web apps with free SSL, global CDN, and unique Preview URLs each time you git push. Perfect for Next.js and other Static Site Generators.
Versoly — SaaS-focused website builder - unlimited websites, 70+ blocks, five templates, custom CSS, favicon, SEO and forms. No custom domain.
Qoddi - PaaS service similar to Heroku with a developer-centric approach and all-inclusive features. Free tier for static assets, staging, and developer apps.
FreeFlarum - Community-powered free Flarum hosting for up to 250 users (donate to remove the watermark from the footer).
fleek.co - Build modern sites and apps on the Open Web and its protocols seamlessly free for unlimited websites and 50 GB/month bandwidth.
MDB GO - Free hosting for one project with two weeks Container TTL, 500 MB RAM per project, SFTP - 1G disk space.
Patr Cloud — An easy-to-use cloud platform, among its paid services it offers to host three static sites for free.
Serv00.com — 3 GB of free web hosting with daily backups (7 days). Support: Crontab jobs, SSH access, repositories (GIT, SVN, and Mercurial), support: MySQL, PostgreSQL, MongoDB, PHP, Node.js, Python, Ruby, Java, Perl, TCL/TK, Lua, Erlang, Rust, Pascal, C, C++, D, R, and many more.
⬆️ Back to Top

DNS
1.1.1.1 - Free public DNS Resolver, which is fast and secure (encrypt your DNS query), provided by Cloudflare. Useful to bypass your internet provider's DNS blocking, prevent DNS query spying, and to block adult & malware content. It can also be used via API. Note: Just a DNS resolver, not a DNS hoster.
1984.is — Free DNS service with API and lots of other free DNS features included.
cloudns.net — Free DNS hosting up to 1 domain with 50 records
deSEC - Free DNS hosting with API support, designed with security in mind. Runs on open-source software and is supported by SSE.
dns.he.net — Free DNS hosting service with Dynamic DNS Support
Zonomi — Free DNS hosting service with instant DNS propagation. Free plan: 1 DNS zone (domain name) with up to 10 DNS records.
dnspod.com — Free DNS hosting.
duckdns.org — Free DDNS with up to 5 domains on the free tier. With configuration guides for various setups.
Dynv6.com — Free DDNS service with API support and management of a lot of dns record types (like CNAME, MX, SPF, SRV, TXT and others).
freedns.afraid.org — Free DNS hosting. Also, provide free subdomains based on numerous public user contributed domains. Get free subdomains from the "Subdomains" menu after signing up.
luadns.com — Free DNS hosting, three domains, all features with reasonable limits
namecheap.com — Free DNS. No limit on the number of domains
nextdns.io - DNS-based firewall, 300K free queries monthly
noip.at — Free DDNS service without registration, tracking, logging or advertising. No limit to domains.
noip — a dynamic DNS service that allows up to 3 hostnames free with confirmation every 30 days
sslip.io — Free DNS service that when queried with a hostname with an embedded IP address returns that IP address.
zilore.com — Free DNS hosting for 5 domains.
zoneedit.com — Free DNS hosting with Dynamic DNS Support.
zonewatcher.com — Automatic backups and DNS change monitoring. One domain free
huaweicloud.com – Free DNS hosting by Huawei
Hetzner – Free DNS hosting from Hetzner with API support.
Glauca – Free DNS hosting for up to 3 domains and DNSSEC support
⬆️ Back to Top

Domain
eu.org — Free eu.org domain. The request is usually approved in 14 days.
pp.ua — Free pp.ua subdomains.
us.kg - Free us.kg subdomains.
⬆️ Back to Top

IaaS
4EVERLAND — Compatible with AWS S3 - APIs, interface operations, CLI, and other upload methods, upload and store files from the IPFS and Arweave networks in a safe, convenient, and efficient manner. Registered users can get 6 GB of IPFS storage and 300MB of Arweave storage for free. Any Arweave file uploads smaller than 150 KB are free.
backblaze.com — Backblaze B2 cloud storage. Free 10 GB (Amazon S3-like) object storage for unlimited time
filebase.com - S3 Compatible Object Storage Powered by Blockchain. 5 GB free storage for an unlimited duration.
Tebi - S3 compatibility object storage.Free 25 GB storage and 250GB outbound transfer.
Idrive e2 - S3 compatibility object storage. 10 GB free storage and 10 GB download bandwidth per month.
C2 Object Storage - S3 compatibility object storage. 15 GB free storage and 15 GB downloads per month.
⬆️ Back to Top

Managed Data Services
Aiven - Aiven offers free PostgreSQL, MySQL and Redis plans on its open-source data platform. Single node, 1 CPU, 1GB RAM, and for PostgreSQL and MySQL, 5GB storage. Easy migration to more extensive plans or across clouds.
airtable.com — Looks like a spreadsheet, but it's a relational database unlimited bases, 1,200 rows/base, and 1,000 API requests/month
Astra — Cloud Native Cassandra as a Service with 80GB free tier
codehooks.io — Easy to use JavaScript serverless API/backend and NoSQL database service with functions, Mongdb-ish queries, key/value lookups, a job system, realtime messages, worker queues, a powerful CLI and a web-based data manager. Free plan has 5GB storage and 60/API calls per minute. 2 developers included. No credit-card required.
CrateDB - Distributed Open Source SQL database for real-time analytics. Free Tier CRFREE: One-node with 2 CPUs, 2 GiB of memory, 8 GiB of storage. One cluster per organization, no payment method needed.
FaunaDB — Serverless cloud database with native GraphQL, multi-model access, and daily free tiers up to 100 MB
Upstash — Serverless Redis with free tier up to 10,000 requests per day, 256MB max database size, and 20 concurrent connections
MongoDB Atlas — free tier gives 512 MB
redsmin.com — Online real-time monitoring and administration service for Redis, Monitoring for 1 Redis instance free
redislabs - Free 30MB redis instance
MemCachier — Managed Memcache service. Free for up to 25MB, 1 Proxy Server, and basic analytics
scalingo.com — Primarily a PaaS but offers a 128MB to 192MB free tier of MySQL, PostgreSQL, or MongoDB
SeaTable — Flexible, Spreadsheet-like Database built by the Seafile team. unlimited tables, 2,000 lines, 1-month versioning, up to 25 team members.
skyvia.com — Cloud Data Platform offers a free tier and all plans are completely free while in beta
StackBy — One tool that combines spreadsheets' flexibility, databases' power, and built-in integrations with your favorite business apps. The free plan includes unlimited users, ten stacks, and a 2GB attachment per stack.
TiDB Cloud — TiDB is an open-source MySQL-compatible distributed HTAP RDBMS. TiDB Serverless provides 5GB of row storage, 5GB of column storage, and 50 million Request Units (RUs) for free each month.
Turso by ChiselStrike - Turso is SQLite Developer Experience in an Edge Database. Turso provides a Free Forever starter plan, 9 GB of total storage, Up to 500 databases, Up to 3 locations, 1 billion row reads per month, and Local development support with SQLite.
InfluxDB — Timeseries database, free up to 3MB/5 minutes writes, 30MB/5 minutes reads and 10,000 cardinalities series
restdb.io - a fast and straightforward NoSQL cloud database service. With restdb.io you get schema, relations, automatic REST API (with MongoDB-like queries), and an efficient multi-user admin UI for working with data. The free plan allows 3 users, 2500 records, and 1 API request per second.
cockroachlabs.com — Free CockroachDB up to 5GB and 1vCPU (limited request units)
Neo4j Aura — Managed native Graph DBMS / analytics platform with a Cypher query language and a REST API. Limits on graph size (50k nodes, 175k relationships).
Neon — Managed PostgreSQL, 0.5 GB of storage (total), 1 Project ,10 branches, Unlimited Databases, always-available primary branch ( Auto suspend after 5 minutes), 20 hours of Active time per month (total) for non-primary branch compute.
Dgraph Cloud — Managed native Graph DBMS with a GraphQL API. Limited to 1 MB data transfer per day.
Tinybird - A serverless managed ClickHouse with connection-less data ingest over HTTP and lets you publish SQL queries as managed HTTP APIs. There is no time limit on free-tier, 10GB storage + 1000 API requests per day.
TigerGraph Cloud — Managed native Graph DBMS / analytics platform with a SQL-like graph query language and a REST API. One free instance with two vCPU, 8GB Memory, and 50GB storage that sleeps after 1 hour of inactivity.
TerminusCMS — Managed free service for TerminusDB, a document and graph database written in Prolog and Rust. Free for dev, paid service for enterprise deployments and support.
YugabyteDB - YugabyteDB is a distributed SQL database compatible with PostgreSQL. The cloud-free tier includes two vCPU, 4GB RAM, and 10GB Disk.
filess.io - filess.io is a platform where you can create one database of the following DBMS for free: MySQL, MariaDB, MongoDB, and PostgreSQL.
xata.io - Xata is a serverless database with built-in powerful search and analytics. One API, multiple type-safe client libraries, and optimized for your development workflow. The free-forever tier is sufficient for hobby developers which comes with three units of Xata, please refer to the website for unit definition.
8base.com - 8base is a full-stack low-code development platform built for JavaScript developers built on top of MySQL and GraphQL and serverless backend-as-a-service. It allows you to start building web applications quickly using a UI app builder and scale quickly, The Free tier includes rows: 2,500, Storage: 500, Serverless computing: 1Gb/h, and client app users: 5.
Nile — A Postgres platform for B2B apps. Unlimited databases, Always available with no shutdown, 1GB of storage (total), 50 million query tokens, autoscaling, unlimited vector embeddings
⬆️ Back to Top

Tunneling, WebRTC, Web Socket Servers and Other Routers
Pinggy — Public URLs for localhost with a single command, no downloads required. HTTPS / TCP / TLS tunnels. The free plan has 60 minutes tunnel lifetime.
conveyor.cloud — Visual Studio extension to expose IIS Express to the local network or over a tunnel to a public URL.
Hamachi — LogMeIn Hamachi is a hosted VPN service that lets you securely extend LAN-like networks to distributed teams with a free plan that allows unlimited networks with up to 5 people
Mirna Sockets - Free Socket as a Service Platform that gives you a wss:// URL when deploying your Web Socket Server code and also allows you to monitor its performance.
localhost.run — Expose locally running servers over a tunnel to a public URL.
localtunnel — Expose locally running servers over a tunnel to a public URL. Free hosted version, and open source.
ngrok.com — Expose locally running servers over a tunnel to a public URL.
cname.dev — Free and secure dynamic reverse proxy service.
serveo — Expose local servers to the internet. No installation, no signup. Free subdomain, no limits.
Radmin VPN — Connect multiple computers together via a VPN-enabling LAN-like network. Unlimited peers. (Hamachi alternative)
segment.com — Hub to translate and route events to other third-party services. 100,000 events/month free
Google STUN — stun:stun.l.google.com:19302
Twilio STUN — stun:global.stun.twilio.com:3478?transport=udp
Tailscale — Zero config VPN, using the open-source WireGuard protocol. Installs on MacOS, iOS, Windows, Linux, and Android devices. Free plan for personal use with 100 devices and three users.
webhookrelay.com — Manage, debug, fan-out, and proxy all your webhooks to public or internal (i.e. localhost) destinations. Also, expose servers running in a private network over a tunnel by getting a public HTTP endpoint (https://yoursubdomain.webrelay.io <----> http://localhost:8080).
Hookdeck — Develop, test, and monitor your webhooks from anywhere. 100K requests and 100K attempts per month with three days retention.
Xirsys — Unlimited STUN usage + 500 MB monthly TURN bandwidth, capped bandwidth, single geographic region.
ZeroTier — FOSS managed virtual Ethernet as a service. Unlimited end-to-end encrypted networks of 25 clients on the free plan. Clients for desktop/mobile/NA; web interface for configuration of custom routing rules and approval of new client nodes on private networks
LocalXpose — Reverse proxy that enables you to expose your localhost servers to the internet. The free plan has 15 minutes tunnel lifetime.
Traefik-Hub - Publish locally, running services over a tunnel to a public custom URL and secure them with access control. Free for 5 services in one cluster.
Expose - Expose local sites via secure tunnels. The free plan includes an EU Server, Random subdomains, and Single users.
btunnel — Expose localhost and local tcp server to the internet. Free plan includes file server, custom http request and response headers, basic auth protection and 1 hour tunnel timeout.
⬆️ Back to Top

Issue Tracking and Project Management
acunote.com — Free project management and SCRUM software for up to 5 team members
asana.com — Free for private project with collaborators
Backlog — Everything your team needs to release great projects in one platform. The free plan offers 1 Project with ten users & 100MB of storage.
Basecamp - To-do lists, milestone management, forum-like messaging, file sharing, and time tracking. Up to 3 projects, 20 users, and 1GB of storage space.
bitrix24.com — Intranet and project management tool. The free plan has 5GB for unlimited users.
cacoo.com — Online real-time diagrams: flowchart, UML, network. Free max. 15 users/diagram, 25 sheets
Chpokify — Teams-based Planning Poker that saves time on sprint estimation. Free up to 5 users, free Jira integrations, unlimited video calls, unlimited teams, unlimited sessions.
clickup.com — Project management. Free, premium version with cloud storage. Mobile applications and Git integrations are available.
Clockify - Time tracker and timesheet app that lets you track work hours across projects. Unlimited users, free forever.
Cloudcraft — Design a professional architecture diagram in minutes with the Cloudcraft visual designer, optimized for AWS with intelligent components that show live data too. Free plan has unlimited private diagrams for single user.
Codegiant — Project Management with Repository hosting & CI/CD. Free Plan Offers Unlimited Repositories, Projects & Documents with 5 Team Members. 500 CI/CD minutes per month. 30000 Serverless Code Run minutes per month 1GB repository storage.
Confluence - Atlassian's content collaboration tool is used to help teams collaborate and share knowledge efficiently. Free plan for up to 10 users.
contriber.com — Customizable project management platform, free starter plan, five workspaces
Crosswork - Versatile project management platform. Free for up to 3 projects, unlimited users, 1 GB storage.
diagrams.net — Online diagrams stored locally in Google Drive, OneDrive, or Dropbox. Free for all features and storage levels
freedcamp.com - tasks, discussions, milestones, time tracking, calendar, files and password manager. Free plan with unlimited projects, users, and file storage.
easyretro.io — Simple and intuitive sprint retrospective tool. The free plan has three public boards and one survey per board per month.
GForge — Project Management and issue Tracking toolset for complex projects with self-premises and SaaS options. SaaS free plan offers the first five users free & free for Open Source Projects.
gleek.io — Free description-to-diagrams tool for developers. Create informal UML class, object, or entity-relationship diagrams using your keyword.
GraphQL Inspector - GraphQL Inspector outputs a list of changes between two GraphQL schemas. Every difference is precisely explained and marked as breaking, non-breaking, or dangerous.
huboard.com — Instant project management for your GitHub issues, free for Open Source
Hygger — Project management platform. The free plan offers unlimited users, projects & boards with 100 MB of Storage.
Instabug — A comprehensive bug reporting and in-app feedback SDK for mobile apps. Free plan up to 1 app and one member.
WishKit — Collect in-app user feedback for your iOS/macOS app and prioritize features based on user votes. Free plan up to 1 app.
Ilograph — interactive diagrams that allow users to see their infrastructure from multiple perspectives and levels of detail. Charts can be expressed in code. The free tier has unlimited private diagrams with up to 3 viewers.
Jira — Advanced software development project management tool used in many corporate environments. Free plan for up to 10 users.
kanbanflow.com — Board-based project management. Free, premium version with more options
kanbantool.com — Kanban board-based project management. The free plan has two boards and two users, without attachments or files.
Kitemaker.co - Collaborate through all phases of the product development process and keep track of work across Slack, Discord, Figma, and Github. Unlimited users, unlimited spaces. Free plan up to 250 work items.
Kiter.app - Let anyone organize their job search and track interviews, opportunities, and connections. Powerful web app and Chrome extension. Completely free.
Kumu.io — Relationship maps with animation, decorations, filters, clustering, spreadsheet imports, etc. The free tier allows unlimited public projects. Graph size unlimited. Free private projects for students. Sandbox mode is available if you prefer not to leave your file publicly online (upload, edit, download, discard).
Linear — Issue tracker with a streamlined interface. Free for unlimited members, up to 10MB file upload size, 250 issues (excluding Archive)
leiga.com — Leiga is a SaaS product that uses AI to automatically manage your projects, helping your team stay focused and unleash immense potential, ensuring your projects progress as planned. Free for up to 10 users, 20 custom fields, 2GB of storage space, Video Recording with AI limited to 5 mins/video, Automation Runs at 20/user/month.
Lucidchart - An online diagram tool with collaboration features. Free plan with three editable documents, 100 professional templates, and basic collaboration features.
MeisterTask — Online task management for teams. Free up to 3 projects and unlimited project members.
MeuScrum - Free online scrum tool with kanban board
nTask — Project management software that enables your teams to collaborate, plan, analyze, and manage everyday tasks. The essential plan is free forever with 100 MB storage and five users/teams. Unlimited workspaces, meetings, assignments, timesheets, and issue tracking.
Ora - Agile task management & team collaboration. Free for up to 3 users and files are limited to 10 MB.
pivotaltracker.com — Free for unlimited public projects and two private projects with three total active users (read-write) and unlimited passive users (read-only).
plan.io — Project Management with Repository Hosting and more options. Free for two users with ten customers and 500MB Storage
Plane - Plane is a simple, extensible, open-source project and product management tool. Free for unlimited members, up to 5MB file upload size, 1000 issues.
planitpoker.com — Free online planning poker (estimation tool)
point.poker - Online Planning Poker (consensus-based estimation tool). Free for unlimited users, teams, sessions, rounds, and votes. You don't need to register.
ScrumFast - Scrum board with a very intuitive interface, free up to 5 users.
Shake - In-app bug reporting and feedback tool for mobile apps. Free plan, ten bug reports per app/month.
Shortcut - Project management platform. Free for up to 10 users forever.
Tadum - Meeting agenda and minutes app designed for recurring meetings, free for teams of up to 10
taiga.io — Project management platform for startups and agile developers, free for Open Source
Tara AI — Simple sprint management service. The free plan has unlimited tasks, sprints, and workspaces without user limits.
targetprocess.com — Visual project management, from Kanban and Scrum to almost any operational process. Free for unlimited users, up to 1,000 data entities {more details}
taskade.com — Real-time collaborative task lists and team outlines. The free plan has one workspace with unlimited tasks and projects; 1GB file storage; 1-week project history; and five attendees per video meeting.
taskulu.com — Role based project management. Free up to 5 users. Integration with GitHub/Trello/Dropbox/Google Drive
Teaminal - Standup, retro, and sprint planning tool for remote teams. Free for up to 15 users.
teamwork.com — Project management & Team Chat. Free for five users and two projects. Premium plans are available.
teleretro.com — Simple and fun retrospective tool with icebreakers, gifs and emojis. The free plan includes three retros and unlimited members.
testlio.com — Issue tracking, test management and beta testing platform. Free for private use
terrastruct.com — Online diagram maker specifically for software architecture. Free tier up to 4 layers per diagram.
todoist.com — Collaborative and individual task management. The free plan has: 5 active projects, five users in the project, file uploading up to 5MB, three filters, and one week of activity history.
trello.com — Board-based project management. Unlimited Personal Boards, 10 Team Boards.
Tweek — Simple Weekly To-Do Calendar & Task Management.
ubertesters.com — Test platform, integration and crowd testers, 2 projects, five members
Wikifactory — Product designing Service with Projects, VCS & Issues. The free plan offers unlimited projects & collaborators and 3GB storage.
Yodiz — Agile development and issue tracking. Free up to 3 users, unlimited projects.
YouTrack — Free hosted YouTrack (InCloud) for FOSS projects and private projects (free for three users). Includes time tracking and agile boards
zenhub.com — The only project management solution inside GitHub. Free for public repos, OSS, and nonprofit organizations
zenkit.com — Project management and collaboration tool. Free for up to 5 members, 5 GB attachments.
Zube — Project management with free plan for 4 Projects & 4 users. GitHub integration is available.
Toggl — Provides two free productivity tools. Toggl Track for time management and tracking app with a free plan provides seamless time tracking and reporting designed with freelancers in mind. It has unlimited tracking records, projects, clients, tags, reporting, and more. And Toggl Plan for task planning with a free plan for solo developers with unlimited tasks, milestones, and timelines.
Sflow — sflow.io is a project management tool built for agile software development, marketing, sales, and customer support, especially for outsourcing and cross-organization collaboration projects. Free plan up to 3 projects and five members.
Pulse.red — Free Minimalistic Time Tracker and Timesheet app for projects.
⬆️ Back to Top

Storage and Media Processing
AndroidFileHost - Free file-sharing platform with unlimited speed, bandwidth, file count, download count, etc. It is mainly aimed for Android dev-related files like APK build, custom ROM & modifications, etc. But seems to accept any other files as well.
borgbase.com — Simple and secure offsite backup hosting for Borg Backup. 10 GB free backup space and two repositories.
icedrive.net - Simple cloud storage service. 10 GB free storage
sync.com - End-to-End cloud storage service. 5 GB of free storage
pcloud.com - Cloud storage service. Up to 10 GB of free storage
sirv.com — Smart Image CDN with on-the-fly image optimization and resizing. The free tier includes 500 MB of storage and 2 GB of bandwidth.
cloudimage.io — Full image optimization and CDN service with 1500+ Points of Presence around the world. A variety of image resizing, compression, and watermarking functions. Open source plugins for responsive images, 360 image making and image editing. Free monthly plan with 25GB of CDN traffic 25GB of cache storage and unlimited transformations.
cloudinary.com — Image upload, powerful manipulations, storage, and delivery for sites and apps, with Ruby, Python, Java, PHP, Objective-C, and more libraries. The free tier includes 25 monthly credits. One credit equals 1,000 image transformations, 1 GB of storage, or 1 GB of CDN usage.
embed.ly — Provides APIs for embedding media in a webpage, responsive image scaling, and extracting elements from a webpage. Free for up to 5,000 URLs/month at 15 requests/second
filestack.com — File picker, transform, and deliver, free for 250 files, 500 transformations, and 3 GB bandwidth
file.io - 2 GB storage of files. A file is auto-deleted after one download. REST API to interact with the storage. Rate limit one request/minute.
freetools.site — Free online tools. Convert or edit documents, images, audio, video, and more.
GoFile.io - Free file sharing and storage platform can be used via web-based UI & also API. unlimited file size, bandwidth, download count, etc. But it will be deleted when a file becomes inactive (no download for more than ten days).
gumlet.com — Image and video hosting, processing and streaming via CDN. Provides generous free tier of 250 GB / month for videos and 30 GB / month for images.
image-charts.com — Unlimited image chart generation with a watermark
Imgbot — Imgbot is a friendly robot that optimizes your images and saves you time. Optimized images mean smaller file sizes without sacrificing quality. It's free for open source.
ImgBB — ImgBB is an unlimited image hosting servce. Drag and drop your image anywhere on the screen. 32 MB / image limit. Receive Direct image links, BBCode and HTML thumbnails after uploading image. Login to see the upload history.
imgen - Free unlimited social cover image generation API, no watermark
imgix - Image Caching, management and CDN. Free plan includes 1000 origin images, infinite transformations and 100 GB bandwidth
kraken.io — Image optimization for website performance as a service, free plan up to 1 MB file size
kvstore.io — Key-value storage service. The free tier allows 100 keys, 1KB/key, 100 calls/hour
npoint.io — JSON store with collaborative schema editing
nitropack.io - Accelerate your site's speed on autopilot with complete front-end optimization (caching, images and code optimization, CDN). Free for up to 5,000 pageviews/month
otixo.com — Encrypt, share, copy, and move all your cloud storage files from one place. The basic plan provides unlimited file transfer with 250 MB max. file size and allows five encrypted files
packagecloud.io — Hosted Package Repositories for YUM, APT, RubyGem and PyPI. Limited free plans and open-source plans are available via request
getpantry.cloud — A simple JSON data storage API perfect for personal projects, hackathons, and mobile apps!
Pinata IPFS — Pinata is the simplest way to upload and manage files on IPFS. Our friendly user interface and IPFS API make Pinata the easiest IPFS pinning service for platforms, creators, and collectors. 1 GB storage free, along with access to API.
placekitten.com — A quick and simple service for getting pictures of kittens for use as placeholders
plot.ly — Graph and share your data. The free tier includes unlimited public files and ten private files
podio.com — You can use Podio with a team of up to five people and try out the features of the Basic Plan, except user management
QuickChart — Generate embeddable image charts, graphs, and QR codes
redbooth.com — P2P file syncing, free for up to 2 users
resmush.it — reSmush.it is a FREE API that provides image optimization. reSmush.it has been implemented on the most common CMS such as WordPress, Drupal, or Magento. reSmush.it is the most used image optimization API with more than seven billion images already treated, and it is still Free of charge.
Shotstack - API to generate and edit video at scale. Free up to 20 minutes of rendered video per month
tinypng.com — API to compress and resize PNG and JPEG images, offers 500 compressions for free each month
transloadit.com — Handles file uploads and encoding of video, audio, images, documents. Free for Open source, charities, and students via the GitHub Student Developer Pack. Commercial applications get 2 GB free for test driving
twicpics.com - Responsive images as a service. It provides an image CDN, a media processing API, and a frontend library to automate image optimization. The service is free for up to 3GB of traffic/per month.
uploadcare.com — Uploadcare provides the media pipeline with the ultimate toolkit based on cutting-edge algorithms. All features are available for developers absolutely for free: File Uploading API and UI, Image CDN and Origin Services, Adaptive Delivery, and Smart Compression. The free tier has 3000 uploads, 3 GB traffic, and 3 GB storage.
imagekit.io – Image CDN with automatic optimization, real-time transformation, and storage that you can integrate with existing setup in minutes. The free plan includes up to 20GB of bandwidth per month.
internxt.com – Internxt Drive is a zero-knowledge file storage service based on absolute privacy and uncompromising security. Sign up and get 10 GB for free, forever!
degoo.com – AI based cloud storage with free up to 20 GB, three devices, 5 GB referral bonus (90 days account inactivity).
MConverter.eu – Convert files in bulk. Supports many file formats, including new ones like AVIF. Extract all image frames from videos. Free for up to ten 100MB-files per day, processed in batches of two.
ImageEngine – ImageEngine is an easy to use global image CDN. Sub 60 sec setup. AVIF and JPEGXL support, WordPress-, Magento-, React-, Vue- plugins and more. Claim your free developer account here.
DocsParse – GPT powered AI processing of PDFs, Images, into structured data in JSON, CSV, EXCEL formats. 30 credits for free each month.
⬆️ Back to Top

Design and UI
AllTheFreeStock - a curated list of free stock images, audio and videos.
Float UI - free web development tool for quickly creating modern, responsive websites with sleek design, even for non-designers.
Ant Design Landing Page - Ant Design Landing Page provides a template built by Ant Motion's motion components. It has a rich homepage template, downloads the template code package, and can be used quickly. You can also use the editor to quickly build your own dedicated page.
Backlight — With collaboration between developers and designers at heart, Backlight is a complete coding platform where teams build, document, publish, scale, and maintain Design Systems. The free plan allows up to 3 editors to work on one design system with unlimited viewers.
BoxySVG — A free installable Web app for drawing SVGs and exporting in SVG, PNG, jpeg, and other formats.
Carousel Hero - Free online tool to create social media carousels.
Circum Icons - Consistent open-source icons such as SVG for React, Vue, and Svelte.
clevebrush.com — Free Graphics Design / Photo Collage App. Also, they offer paid integration of it as a component.
cloudconvert.com — Convert anything to anything. Two hundred eight supported formats including videos and gifs.
CodeMyUI - Handpicked collection of Web Design & UI Inspiration with Code Snippets.
ColorKit - Create color palettes online or get inspiration from top palettes.
coolors - Color palette generator. Free.
Branition - Hand-curated color pallets best fitted for brands.
css-gradient.com - Free tool to quickly generate custom cross-browser CSS gradients. In RGB and HEX format.
easyvectors.com — EasyVectors.com is a free SVG vector art stock. Download the best vector graphics absolutely for free.
figma.com — Online, collaborative design tool for teams; free tier includes unlimited files and viewers with a max of 2 editors and three projects.
Flyon UI- The Easiest Components Library For Tailwind CSS.
framer.com - Framer helps you iterate and animate interface ideas for your next app, website, or product—starting with powerful layouts. For anyone validating Framer as a professional prototyping tool: unlimited viewers, up to 2 editors, and up to 3 projects.
freeforcommercialuse.net — FFCU Worry-free model/property release stock photos
Gradientos - Makes choosing a gradient fast and easy.
Icon Horse – Get the highest resolution favicon for any website from our simple API.
Iconoir – An open-source icons library with thousands of icons, supporting React, React Native, Flutter, Vue, Figma, and Framer.
Icons8 — Icons, illustrations, photos, music, and design tools. Free Plan offers Limited formats in lower resolution. Link to Icons8 when you use our assets.
landen.co — Generate, edit, and publish beautiful websites and landing pages for your startup. All without code. The free tier allows you to have one website, fully customizable and published on the web.
Quant Ux - Quant Ux is a prototyping and design tool. - It's completely free and also open source.
lensdump.com - Free cloud image hosting.
Lorem Picsum - A Free tool, easy to use, stylish placeholders. After our URL, add your desired image size (width & height), and you'll get a random image.
LottieFiles - The world’s largest online platform for the world’s most miniature animation format for designers, developers, and more. Access Lottie animation tools and plugins for Android, iOS, and Web.
MagicPattern — A collection of CSS & SVG background generators & tools for gradients, patterns, and blobs.
marvelapp.com — Design, prototyping, and collaboration, free plan limited to one user and project.
Mindmup.com — Unlimited mind maps for free and store them in the cloud. Your mind maps are available everywhere, instantly, from any device.
Mockplus iDoc - Mockplus iDoc is a powerful design collaboration & handoff tool. Free Plan includes three users and five projects with all features available.
mockupmark.com — Create realistic t-shirt and clothing mockups for social media and E-commerce, 40 free mockups.
Mossaik - Free SVG image generator with different tools like waves, blogs and patterns.
movingpencils.com — Fast, browser-based vector editor. Completely free.
Octopus.do — Visual sitemap builder. Build your website structure in real time and rapidly share it to collaborate with your team or clients.
Pencil - Open source design tool using Electron.
Penpot - Web-based, open-source design and prototyping tool. Supports SVG. Completely free.
pexels.com - Free stock photos for commercial use. Has a free API that allows you to search photos by keywords.
photopea.com — A Free, Advanced online design editor with Adobe Photoshop UI supporting PSD, XCF & Sketch formats (Adobe Photoshop, Gimp and Sketch App).
pixlr.com — Free online browser editor on the level of commercial ones.
Plasmic - A fast, easy-to-use, robust web design tool and page builder that integrates into your codebase. Build responsive pages or complex components; optionally extend with code; and publish to production sites and apps.
Pravatar - Generate a random/placeholder fake avatar whose URL can be directly hot-linked in your web/app.
Proto.io - Create fully interactive UI prototypes without coding. The free tier is available when the free trial ends. The free tier includes one user, one project, five prototypes, 100MB of online storage, and a preview of the proto.io app.
resizeappicon.com — A simple service to resize and manage your app icons.
Rive — Create and ship beautiful animations to any platform. Free forever for Individuals. The service is an editor that also hosts all the graphics on their servers. They also provide runtimes for many platforms to run representations made using Rive.
storyset.com — Create incredible free customized illustrations for your project using this tool.
smartmockups.com — Create product mockups, 200 free mockups.
tabler-icons.io — Over 1500 free copy-and-paste SVG editable icons.
UI Avatars - Generate avatars with initials from names. The URLs can be directly hot-linked in your web/app. Support config parameters via the URL.
unDraw - A constantly updated collection of beautiful SVG images that you can use completely free without attribution.
unsplash.com - Free stock photos for commercial and noncommercial purposes (do-whatever-you-want license).
vectr.com — Free Design App for Web + Desktop.
walkme.com — Enterprise Class Guidance and Engagement Platform, free plan three walk-thru up to 5 steps/walk.
Webflow - WYSIWYG website builder with animations and website hosting. Free for two projects.
Updrafts.app - WYSIWYG website builder for tailwindcss-based designs. Free for non-commercial usage.
whimsical.com - Collaborative flowcharts, wireframes, sticky notes and mind maps. Create up to 4 free boards.
Zeplin — Designer and developer collaboration platform. Show designs, assets, and style guides. Free for one project.
Pixelixe — Create and edit engaging, unique graphics and images online.
Responsively App - A free dev tool for faster and more precise responsive web application development.
SceneLab - Online mockup graphics editor with an ever-expanding collection of free design templates
xLayers - Preview and convert Sketch design files into Angular, React, Vue, LitElement, Stencil, Xamarin, and more (free and open source at https://github.com/xlayers/xlayers)
Grapedrop — Responsive, powerful, SEO-optimized web page builder based on GrapesJS Framework. Free for the first five pages, unlimited custom domains, all features, and simple usage.
Mastershot - Completely free browser-based video editor. No watermark, up to 1080p export options.
Unicorn Platform - Effortless landing page builder with hosting. One website for free.
SVGmix.com - Massive repository of 300K+ of free SVG icons, collections, and brand logos. It has a simple vector editing program right in the browser for quick file editing.
svgrepo.com - Explore, search, and find the best-fitting icons or vectors for your projects using various vector libraries. Download free SVG Vectors for commercial use.
haikei.app - Haikei is a web app to generate unique SVG shapes, backgrounds, and patterns – ready to use with your design tools and workflow.
Canva - Free online design tool to create visual content.
Superdesigner - A collection of free design tools to create unique backgrounds, patterns, shapes, images, and more with just a few clicks.
TeleportHQ - Low-code Front-end Design & Development Platform. TeleportHQ is the collaborative front-end platform to instantly create and publish headless static websites. Three free projects, unlimited collaborators, and free code export.
vector.express — Convert your AI, CDR, DWG, DXF, EPS, HPGL, PDF, PLT, PS and SVG vector fast and easily.
Vertopal - Vertopal is a free online platform for converting files to various formats. Including developer converters like JPG to SVG, GIF to APNG, PNG to WEBP, JSON to XML, etc.
okso.app - Minimalistic online drawing app. Allows to create fast sketches and visual notes. Exports sketches to PNG, JPG, SVG, and WEBP. Also installable as PWA. Free to use for everyone (no registration is needed).
Wdrfree SVG - Black and White Free SVG Cut files.
Lucide - Free customizable and consistent SVG icon toolkit.
Logo.dev - Company logo API with 44M+ brands that's as easy as calling a URL. First 10,000 API calls are free.
MDBootstrap - Free for personal & commercial use Bootstrap, Angular, React, and Vue UI Kits with over 700 components, stunning templates, 1-min installation, extensive tutorials & colossal community.
TW Elements - Free Bootstrap components recreated with Tailwind CSS, but with better design and more functionalities.
DaisyUI -- Free. "Use Tailwind CSS but write fewer class names" offers components like buttons.
Scrollbar.app -- Simple free web app for designing custom scrollbars for the web.
css.glass -- Free web app for creating glassmorphic designs using CSS.
hypercolor.dev -- A curated collection of Tailwind CSS color gradients also provides a variety of generators to create your own.
iconify.design -- A collection of over 100 icon packs with a unified interface. Allows you to search for icons across packs and export individual icons as SVGs or for popular web frameworks.
NextUI -- Free. Beautiful, fast, and modern React & Next.js UI library.
Glyphs -- Free, The Mightiest Icons on the Web, Fully editable & truly open source design system.
ShadcnUI -- Beautifully designed components that you can copy and paste into your apps. Accessible. Customizable. Open Source.
HyperUI -- Free Open Source Tailwind CSS Components.
Calendar Icons Generator -- Generate an entire year's worth of unique icons in a single click, absolutely FREE
Image BG Blurer -- Generate a blurred background frame for an image, using that image source as the background blur, for Notion, Trello, Jira, and more tools
Webstudio -- Open-source alternative to Webflow. The free plan offers unlimited websites on their domain. Five websites with custom domains. Ten thousand page views/month. 2 GB asset storage.
Nappy -- Beautiful photos of Black and Brown people, for free. For commercial and personal use.
⬆️ Back to Top

Design Inspiration
awwwards. - [Top websites] A showcase of all the best-designed websites (voted on by designers).
Behance - [Design showcase] A place where designers showcase their work. Filterable with categories for UI/UX projects.
dribbble - [Design showcase] Unique design inspiration, generally not from real applications.
Landings - [Web screenshots] Find the best landing pages for your design inspiration based on your preference.
Lapa Ninja - [Landing page / UI KIts / Web screenshots] Lapa Ninja is a gallery featuring the best 6025 landing page examples, free books for designers and free UI kits from around the web.
LovelyLanding.net - [Landing Page Designs] Frequently updated landing page screenshots. Includes Desktop, Tablet, and Mobile screenshots.
Mobbin - [Mobile screenshots] Save hours of UI & UX research with our library of 50,000+ fully searchable mobile app screenshots.
Uiland Design - [Mobile screenshots] Explore Mobile and Web UI Designs from Leading Companies in Africa and the world.
Mobile Patterns - [Mobile screenshots] A design inspirational library featuring the finest UI UX Patterns (iOS and Android) for designers, developers, and product makers to reference.
Page Flows - [Mobile / web videos and screenshots] Videos of full flows across many mobile and web apps. Also includes screenshots. Highly searchable and indexed.
Screenlane - [Mobile screenshots] Get inspired and keep up with the latest web & mobile app UI design trends. Filterable by pattern and app.
scrnshts - [Mobile screenshots] A hand-picked collection of the finest app store design screenshots.
UI Garage - [Mobile / web screenshots] Daily UI inspiration & patterns for designers and developers to find inspiration, tools, and the best resources for your project.
Refero - [Web screenshots] Tagged and searchable collection of design references from great web applications.
⬆️ Back to Top

Data Visualization on Maps
IP Geolocation — Free DEVELOPER plan available with 30K requests/month.
carto.com — Create maps and geospatial APIs from your and public data.
Clockwork Micro — Map tools that work like clockwork. Fifty thousand free monthly queries (map tiles, db2vector, elevation).
developers.arcgis.com — APIs and SDKs for maps, geospatial data storage, analysis, geocoding, routing, and more across web, desktop, and mobile. Two million free base map tiles, 20,000 non-stored geocodes, 20,000 simple routes, 5,000 drive time calculations, and 5GB free tile+data storage per month.
Foursquare - Location discovery, venue search, and context-aware content from Places API and Pilgrim SDK.
geoapify.com - Vector and raster map tiles, geocoding, places, routing, isolines APIs. Three thousand free requests/day.
geocod.io — Geocoding via API or CSV Upload. Two thousand five hundred free queries/day.
geocodify.com — Geocoding and Geoparsing via API or CSV Upload. 10k free queries/month.
geojs.io - Highly available REST/JSON/JSONP IP Geolocation lookup API.
giscloud.com — Visualize, analyze, and share geo data online.
graphhopper.com A free developer package is offered for Routing, Route Optimization, Distance Matrix, Geocoding, and Map Matching.
here — APIs and SDKs for maps and location-aware apps. 250k transactions/month for free.
locationiq.com — Geocoding, Maps, and Routing APIs. Five thousand requests/day for free.
mapbox.com — Maps, geospatial services and SDKs for displaying map data.
maptiler.com — Vector maps, map services and SDKs for map visualization. Free vector tiles with weekly updates and four map styles.
nominatim.org — OpenStreetMap's free geocoding service, providing global address search functionality and reverse geocoding capabilities.
nextbillion.ai - Maps related services: Geocoding, Navigation (Direction, Routing, Route Optimization, Distance Matrix), Maps SDK (Vector, Static, Mobile SDK). Free with specified quota for each services.
opencagedata.com — Geocoding API aggregating OpenStreetMap and other open geo sources. Two thousand five hundred free queries/day.
osmnames — Geocoding, search results ranked by the popularity of related Wikipedia page.
positionstack - Free geocoding for global places and coordinates. 25,000 Requests per month for personal use.
stadiamaps.com — Map tiles, routing, navigation, and other geospatial APIs. Two thousand five hundred free map views and API requests/day for non-commercial usage and testing.
maps.stamen.com - Free map tiles and tile hosting.
ipstack - Locate and identify Website Visitors by IP Address
Geokeo api - Geocoding API with language correction and more. Worldwide coverage. 2,500 free daily queries
⬆️ Back to Top

Package Build System
build.opensuse.org — Package build service for multiple distros (SUSE, EL, Fedora, Debian, etc.).
copr.fedorainfracloud.org — Mock-based RPM build service for Fedora and EL.
help.launchpad.net — Ubuntu and Debian build service.
⬆️ Back to Top

IDE and Code Editing
3v4l - Free online PHP shell and snippet-sharing site, that runs your code in 300+ PHP versions
Android Studio — Android Studio provides the fastest tools for building apps on every type of Android device. Open Source IDE is free for everyone and the best Android app development. Available for Windows, Mac, Linux, and even ChromeOS!
AndroidIDE — An Open Source IDE to develop real, Gradle-based Android applications on Android devices.
Apache Netbeans — Development Environment, Tooling Platform and Application Framework.
apiary.io — Collaborative design API with instant API mock and generated documentation (Free for unlimited API blueprints and unlimited users with one admin account and hosted documentation).
BBEdit - BBEdit is a popular and extensible editor for macOS. Free Mode provides a powerful core feature set and an upgrade path to advanced features.
Binder - Turn a Git repo into a collection of interactive notebooks. It is a free public service.
BlueJ — A free Java Development Environment designed for beginners, used by millions worldwide. Powered by Oracle & simple GUI to help beginners.
Bootify.io - Spring Boot app generator with custom database and REST API.
Brackets - Brackets is an open-source text editor specifically designed for web development. It is lightweight, easy to use, and highly customizable.
cacher.io — Code snippet organizer with labels and support for 100+ programming languages.
Code::Blocks — Free Fortran & C/C++ IDE. Open Source and runs on Windows,macOS & Linux.
Cody - Free AI coding assistant that can write (Code blocks, autocomplete, unit tests), understand (knowledge of your entire codebase), fix, and find your code. Available for VS Code, JetBrains and Online.
codiga.io — Coding Assistant that lets you search, define, and reuse code snippets directly in your IDE. Free for individual and small organizations.
codesnip.com.br — Simple code snippets manager with categories, search and tags. free and unlimited.
cocalc.com — (formerly SageMathCloud at cloud.sagemath.com) — Collaborative calculation in the cloud. Browser access to full Ubuntu with built-in collaboration and lots of free software for mathematics, science, data science, preinstalled: Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn, etc.
code.cs50.io - Visual Studio Code for CS50 is a web app at code.cs50.io that adapts GitHub Codespaces for students and teachers.
codepen.io — CodePen is a playground for the front-end side of the web.
codesandbox.io — Online Playground for React, Vue, Angular, Preact, and more.
Components.studio - Code components in isolation, visualize them in stories, test them, and publish them on npm.
Eclipse Che - Web-based and Kubernetes-Native IDE for Developer Teams with multi-language support. Open Source and community-driven. An online instance hosted by Red Hat is available at workspaces.openshift.com.
fakejson.com — FakeJSON helps you quickly generate fake data using its API. Make an API request describing what you want and how you want it. The API returns it all in JSON. Speed up the go-to-market process for ideas and fake it till you make it.
GetVM — Instant free Linux and IDEs chrome sidebar. The free tier includes 5 VMs per day.
GitPod — Instant, ready-to-code dev environments for GitHub projects. The free tier includes 50 hours/month.
ide.goorm.io goormIDE is full IDE on cloud. multi-language support, Linux-based container via the fully-featured web-based terminal, port forwarding, custom URL, real-time collaboration and chat, share link, Git/Subversion support. There are many more features (The free tier includes 1GB RAM and 10GB Storage per container, 5 Container slots).
JDoodle — Online compiler and editor for more than 60 programming languages with a free plan for REST API code compiling up to 200 credits per day.
jetbrains.com — Productivity tools, IDEs and deploy tools (aka IntelliJ IDEA, PyCharm, etc). Free license for students, teachers, Open Source and user groups.
jsbin.com — JS Bin is another playground and code-sharing site of front-end web (HTML, CSS, and JavaScript. It Also supports Markdown, Jade, and Sass).
jsfiddle.net — JS Fiddle is a playground and code-sharing site of front-end web, supporting collaboration.
JSONPlaceholder Some REST API endpoints that return some fake data in JSON format. The source code is also available if you would like to run the server locally.
Lazarus — Lazarus is a Delphi-compatible cross-platform IDE for Rapid Application Development.
MarsCode - A free AI-powered cloud-based IDE.
micro-jaymock - Tiny API mocking microservice for generating fake JSON data.
mockable.io — Mockable is a simple configurable service to mock out RESTful API or SOAP web services. This online service allows you to quickly define REST API or SOAP endpoints and have them return JSON or XML data.
mockaroo — Mockaroo lets you generate realistic test data in CSV, JSON, SQL, and Excel formats. You can also create mocks for back-end API.
Mocklets - an HTTP-based mock API simulator that helps simulate APIs for faster parallel development and more comprehensive testing, with a lifetime free tier.
Paiza — Develop Web apps in Browser without needing to set up anything. Free Plan offers one server with 24 24-hour lifetime and 4 hours of running time per day with 2 CPU cores, 2 GB RAM, and 1 GB storage.
Prepros - Prepros can compile Sass, Less, Stylus, Pug/Jade, Haml, Slim, CoffeeScript, and TypeScript out of the box, reloads your browsers and makes it easy to develop & test your websites so you can focus on making them perfect. You can also add your own tools with just a few clicks.
Replit — A cloud coding environment for various program languages.
SoloLearn — A cloud programming playground well-suited for running code snippets. Supports various programming languages. No registration is required for running code, but it is necessary when saving code on their platform. Also offers free courses for beginners and intermediate-level coders.
stackblitz.com — Online/Cloud Code IDE to create, edit, & deploy full-stack apps. Support any popular NodeJs-based frontend & backend frameworks. Shortlink to create a new project: https://node.new.
Sublime Text - Sublime Text is a popular, versatile, and highly customizable text editor used for coding and text editing tasks.
Visual Studio Code - Code editor redefined and optimized for building and debugging modern web and cloud applications. Developed by Microsoft.
Visual Studio Community — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
VSCodium - Community-driven, without telemetry/tracking, and freely-licensed binary distribution of Microsoft’s editor VSCode
wakatime.com — Quantified self-metrics about your coding activity using text editor plugins, limited plan for free.
Wave Terminal - Wave is an open-source, cross-platform terminal for seamless workflows. Render anything inline. Save sessions and history. Powered by open web standards. MacOS and Linux.
WebComponents.dev — In-browser IDE to code web components in isolation with 58 templates available, supporting stories, and tests.
PHPSandbox — Online development environment for PHP
WebDB - Free Efficient Database IDE. Featuring Server Discovery, ERD, Data Generator, AI, NoSQL Structure Manager, Database Versioning and many more.
Zed - Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.
⬆️ Back to Top

Analytics, Events and Statistics
Dwh.dev - Data Cloud Observability Solution (Snowflake). Free for personal use.
Hightouch - Hightouch is a Reverse ETL platform that helps you sync customer data from your data warehouse to your CRM, marketing, and support tools. The free tier offers you one destination to sync data to.
Avo — Simplified analytics release workflow. Single-source-of-truth tracking plan, type-safe analytics tracking library, in-app debuggers, and data observability to catch all data issues before you release. Free for two workspace members and 1 hour data observability lookback.
Branch — Mobile Analytics Platform. Free Tier offers up to 10K Mobile App Users with deep-linking & other services.
Cauldron — Analytics open source solution that allows users to aggregate information from multiple collaboration platforms as different types of data sources (Git, Github, and Gitlab). The free tier includes an unlimited number of reports.
Census — Reverse ETL & Operational Analytics Platform. Sync 10 fields from your data warehouse to 60+ SaaS like Salesforce, Zendesk, or Amplitude.
Clicky — Website Analytics Platform. Free Plan for one website with 3000 views analytics.
Databox — Business Insights & Analytics by combining other analytics & BI platforms. Free Plan offers 3 users, dashboards & data sources. 11M historical data records.
Hitsteps.com — 2,000 pageviews per month for 1 website
amplitude.com — 1 million monthly events, up to 2 apps
GoatCounter — GoatCounter is an open-source web analytics platform available as a hosted service (free for non-commercial use) or self-hosted app. It aims to offer easy-to-use and meaningful privacy-friendly web analytics as an alternative to Google Analytics or Matomo. The free tier is for non-commercial use and includes unlimited sites, six months of data retention, and 100k pageviews/month.
Google Analytics — Google Analytics
MetricsWave — Privacy-friendly Google Analytics alternative for developers. Free plan allows 20k pageviews per month without credit card.
Expensify — Expense reporting, free personal reporting approval workflow
getinsights.io - Privacy-focused, cookie-free analytics, free for up to 3k events/month.
heap.io — Automatically captures every user action in iOS or web apps. Free for up to 10K monthly sessions.
Hotjar — Website Analytics and Reports . Free Plan allows 2000 pageviews/day. One hundred snapshots/day (max capacity: 300). Three snapshot heatmaps can be stored for 365 days. Unlimited Team Members. Also in App and standalone surveys, feedback widgets with screenshots. Free tier allows creating 3 surveys & 3 feedback widgets and collecting 20 responses per month.
Keen — Custom Analytics for data collection, analysis and visualization. 1,000 events/month free
Yandex.Datalens — Yandex Cloud data visualization and analysis service. The service is provided free of charge. No restrictions on the number of users and requests.
Yandex.Metrica — Unlimited free analytics
Mixpanel — 100,000 monthly tracked users, unlimited data history and seats, US or EU data residency
Moesif — API analytics for REST and GraphQL. (Free up to 500,000 API calls/mo)
optimizely.com — A/B Testing solution, free starter plan, one website, 1 iOS, and 1 Android app
Microsoft PowerBI — Business Insights & Analytics by Microsoft. Free Plan offers limited use with 1 Million User licenses.
Row Zero - Blazingly fast, connected spreadsheet. Connect directly to data databases, S3, and APIs. Import, analyze, graph, and share millions of rows instantly. Three free (forever) workbooks.
sematext.com — Free for up to 50 K actions/month, 1-day data retention, unlimited dashboards, users, etc.
Similar Web — Analytics for Web & Mobile Apps. Free Plan offers five results per metric, one month of mobile app data & 3 months of website data.
StatCounter — Website Viewer Analytics. Free plan for analytics of 500 most recent visitors.
Statsig - All-in-one platform spanning across analytics, feature flagging, and A/B testing. Free for up to 1m metered events per month.
Tableau Developer Program — Innovate, create, and make Tableau work perfectly for your organization. The free developer program gives a personal development sandbox license for Tableau Online. The version is the latest pre-release version so Data Devs can test each & every feature of this superb platform.
usabilityhub.com — Test designs and mockups on real people and track visitors. Free for one user, unlimited tests
woopra.com — Free user analytics platform for 500K actions, 90-day data retention, 30+ one-click integration.
counter.dev — Web analytics made simple and therefore privacy friendly. Free or pay what you want by donation.
PostHog - Full Product Analytics suite free for up to 1m tracked events per month. Also provides unlinited in-App Surveys with 250/month responses.
Uptrace - Distributed Tracing Tool that helps developers pinpoint failures and find performance bottlenecks. Has a free plan, offers a complimentary Personal subscription for open-source projects, and has an open-source version.
Microsoft Clarity - Clarity is a free, easy-to-use tool that captures how real people use your site.
Beampipe.io - Beampipe is simple, privacy-focussed web analytics. free for up to 5 domains & 10k monthly page views.
Aptabase — Open Source, Privacy-Friendly, and Simple Analytics for Mobile and Desktop Apps. SDKs for Swift, Kotlin, React Native, Flutter, Electron, and many others. Free for up to 20,000 events per month.
Trackingplan - Automatically detect digital analytics, marketing data and pixels issues, maintain up-to-date tracking plans, and foster seamless collaboration. Deploy it to your production environment with real traffic or add analytics coverage to your regression tests without writing code.
LogSpot - Full unified web and product analytics platform, including embeddable analytics widgets and automated robots (slack, telegram, and webhooks). Free plan includes 10,000 events per month.
Umami - Simple, fast, privacy-focused, open-source alternative to Google Analytics.
TrackWith Dicloud - Free lightweight privacy-focused alternative to Google Analytics. Unlimited pageviews, unlimited visitor, unlimited page heatmaps & goal tracking. Free for up to 3 domains and 600 session replay per domain.
AppFit - AppFit is a comprehensive analytics and product management tool designed to facilitate seamless, cross-platform management of analytics and product updates. Free plan includes 10,000 events per month, product journal and weekly insights.
Seline - Seline is a simple & private website and product analytics. Cookieless, lightweight, independent. Free plan includes 3,000 events per month and provides access to all our features, such as the dashboard, user journeys, funnels, and more.
⬆️ Back to Top

Visitor Session Recording
Reactflow.com — Per site: 1,000 pages views/day, three heatmaps, three widgets, free bug tracking
OpenReplay.com - Open-source session replay with dev tools for bug reproduction, live session for real-time support, and product analytics suite. One thousand sessions/month with access to all features and 7-day retention.
LogRocket.com - 1,000 sessions/month with 30-day retention, error tracking, live mode
FullStory.com — 1,000 sessions/month with one month data retention and three user seats. More information here.
hotjar.com — Per site: 1,050 pages views/month, unlimited heatmaps, data stored for three months
inspectlet.com — 2,500 sessions/month free for one website
Microsoft Clarity - Session recording completely free with "no traffic limits", no project limits, and no sampling
mouseflow.com — 500 sessions/month free for one website
mousestats.com — 100 sessions/month free for one website
smartlook.com — free packages for web and mobile apps (1500 sessions/month), three heatmaps, one funnel, 1-month data history
howuku.com — Track user interaction, engagement, and event. Free for up to 5,000 visits/month
UXtweak.com — Record and watch how visitors use your website or app. Free unlimited time for small projects
⬆️ Back to Top

International Mobile Number Verification API and SDK
numverify — Global phone number validation and lookup JSON API. 100 API requests/month
veriphone — Global phone number verification in a free, fast, reliable JSON API. 1000 requests/month
⬆️ Back to Top

Payment and Billing Integration
Qonversion - All-in-one cross-platform subscription management platform offering analytics, A/B testing, Apple Search Ads, remote configs, and growth tools for optimizing in-app purchases and monetization. Compatible with iOS, Android, React Native, Flutter, Unity, Cordova, Stripe, and web. Free up to $10k in monthly tracked revenue.
ParityVend – Automatically adjust pricing based on visitor location to expand your business globally and reach new markets (purchasing power parity). The free plan includes 7,500 API requests/month.
Glassfy – In-app subscriptions infrastructure, real-time subscription events and out-of-the-box monetization tools on iOS, Android, Stripe and Paddle. Free up to $10k monthly revenue.
Adapty.io – One-stop solution with open-source SDK for mobile in-app subscription integration to iOS, Android, React Native, Flutter, Unity, or web app. Free up to $10k monthly revenue.
CoinMarketCap — Provides cryptocurrency market data including the latest crypto and fiat currency exchange rates. The free tier offers 10K call credits/month.
CurrencyFreaks — Provides current and historical currency exchange rates. Free DEVELOPER plan available with 1000 requests/month.
CoinGecko — Provides cryptocurrency market data including the latest crypto exchange rates and historical data. The demo api comes with a stable rate limit of 30 calls/min and a monthly cap of 10,000 calls.
CurrencyApi — Live Currency Rates for Physical and Cryptocurrencies, delivered in JSON and XML. The free tier offers 1,250 API requests/month.
currencylayer — Reliable Exchange Rates and Currency Conversion for your Business, 100 API requests/month free.
exchangerate-api.com - An easy-to-use currency conversion JSON API. The free tier updates once per day with a limit of 1,500 requests/month.
FraudLabsPRO — Help merchants to prevent payment fraud and chargebacks. Free Micro Plan available with 500 queries/month.
FxRatesAPI — Provides real-time and historical exchange rates. The free tier requires attribution.
Moesif API Monetization - Generate revenue from APIs via usage-based billing. Connect to Stripe, Chargebee, etc. The free tier offers 30,000 events/month.
Nami ML - Complete platform for in-app purchases and subscriptions on iOS and Android, including no-code paywalls, CRM, and analytics. Free for all base features to run an IAP business.
RevenueCat — Hosted backend for in-app purchases and subscriptions (iOS and Android). Free up to $2.5k/mo in tracked revenue.
vatlayer — Instant VAT number validation and EU VAT rates API, free 100 API requests/month
Currencyapi — Free currency conversion and exchange rate data API. Free 300 requests per month, 10 requests per minute for private use.
⬆️ Back to Top

Docker Related
canister.io — 20 free private repositories for developers, 30 free private repositories for teams to build and store Docker images
Container Registry Service - Harbor based Container Management Solution. The free tier offers 1 GB of storage for private repositories.
Docker Hub — One free private repository and unlimited public repositories to build and store Docker images
Play with Docker — A simple, interactive, fun playground to learn Docker.
quay.io — Build and store container images with unlimited free public repositories
ttl.sh - Anonymous & ephemeral Docker image registry
⬆️ Back to Top

Vagrant Related
Vagrant Cloud - HashiCorp Vagrant Cloud. Vagrant box hosting.
Vagrantbox.es — An alternative public box index
⬆️ Back to Top

Dev Blogging Sites
BearBlog - Minimalist, Markdown-powered blog and website builder.
Dev.to - Where programmers share ideas and help each other grow.
Hashnode — Hassle-free Blogging Software for Developers!.
Medium — Get more thoughtful about what matters to you.
AyeDot — Share your ideas, knowledge, and stories with the world for Free in the form of Modern multimedia short-format Miniblogs.
⬆️ Back to Top

Commenting Platforms
GraphComment - GraphComment is a comments platform that helps you build an active community from the website’s audience.
Utterances - A lightweight comments widget built on GitHub issues. Use GitHub issues for blog comments, wiki pages, and more!
Disqus - Disqus is a networked community platform used by hundreds of thousands of sites all over the web.
Remarkbox - Open source hosted comments platform, pay what you can for "One moderator on a few domains with complete control over behavior & appearance"
IntenseDebate - A feature-rich comment system for WordPress, Tumblr, Blogger, and many other website platforms.
⬆️ Back to Top

Screenshot APIs
ApiFlash — A screenshot API based on Aws Lambda and Chrome. Handles full page, captures timing, and viewport dimensions.
microlink.io – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities, or screenshots as a service. 250 requests/day every day free.
ScreenshotAPI.net - Screenshot API uses a straightforward API call to generate screenshots of any website. Built to scale and hosted on Google Cloud. Offers 100 free screenshots per month.
screenshotlayer.com — Capture highly customizable snapshots of any website. Free 100 snapshots/month
screenshotmachine.com — Capture 100 snapshots/month, png, gif and jpg, including full-length captures, not only home page
PhantomJsCloud — Browser automation and page rendering. Free Tier offers up to 500 pages/day. Free Tier since 2017.
Webshrinker.com — Web Shrinker provides website screenshots and domain intelligence API services. Free 100 requests/month.
Httpic.com — Turn any website into jpg, png or pdf. Capture full-page screenshots, adjust the viewport, and inject custom code. Free tier at 150 images/month.
Screenshots — Your API for Screenshots. With highly customizable options for capture. Free 100 screenshots/month.
⬆️ Back to Top

Flutter Related and Building IOS Apps without Mac
FlutLab - FlutLab is a modern Flutter online IDE and the best place to create, debug, and build cross-platform projects. Build iOS (Without a Mac) and Android apps with Flutter.
CodeMagic - Codemagic is a fully hosted and managed CI/CD for mobile apps. You can build, test, and deploy with a GUI-based CI/CD tool. The free tier offers 500 free minutes/month and a Mac Mini instance with 2.3 GHz and 8 GB of RAM.
FlutterFlow - FlutterFlow is a browser-based drag-and-drop interface to build mobile app using flutter.
⬆️ Back to Top

Browser-based hardware emulation written in Javascript
JsLinux — a really fast x86 virtual machine capable of running Linux and Windows 2k.
Jor1k — an OpenRISC virtual machine capable of running Linux with network support.
v86 — an x86 virtual machine capable of running Linux and other OS directly into the browser.
⬆️ Back to Top

Privacy Management
Bearer - Helps implement privacy by design via audits and continuous workflows so that organizations comply with GDPR and other regulations. The free tier is limited to smaller teams and the SaaS version only.
Osano - Consent management and compliance platform with everything from GDPR representation to cookie banners. The free tier offers basic features.
Iubenda - Privacy and cookie policies and consent management. The free tier offers limited privacy and cookie policy as well as cookie banners.
Cookiefirst - Cookie banners, auditing, and multi-language consent management solution. The free tier offers a one-time scan and a single banner.
Ketch - Consent management and privacy framework tool. The free tier offers most features with a limited visitor count.
Concord - Full data privacy platform, including consent management, privacy request handling (DSARs), and data mapping. Free tier includes core consent management features and they also provide a more advanced plan for free to verified open source projects.
⬆️ Back to Top

Miscellaneous
BackgroundStyler.com - Create aesthetic screenshots of your code, text or images to share on social media.
BinShare.net - Create & share code or binaries. Available to share as a beautiful image e.g. for Twitter / Facebook post or as a link e.g. for chats or forums.
Blynk — A SaaS with API to control, build & evaluate IoT devices. Free Developer Plan with 5 devices, Free Cloud & data storage. Mobile Apps are also available.
Bricks Note Calculator - a note-taking app (PWA) with a powerful built-in multiline calculator.
Carbon.now.sh - create and share code snippets in an aesthetic screenshot-like image format. Usually used to aesthetically share/show off code snippets on Twitter or blog posts.
Code Time - an extension for time-tracking and coding metrics in VS Code, Atom, IntelliJ, Sublime Text, and more.
Codepng - Create excellent snapshots from your source code to share on social media.
CodeToImage - Create screenshots of code or text to share on social media.
Cronhooks - Schedule on-time or recurring webhooks. The free plan allows 5 ad-hoc schedules.
cron-job.org - Online cronjobs service. Unlimited jobs are free of charge.
datelist.io - Online booking / appointment scheduling system. Free up to 5 bookings per month, includes 1 calendar
Domain Forward - A straightforward tool to forward any URL or Domain. Free up to 5 domains and 200k requests per month.
Elementor — WordPress website builder. Free plan available with 40+ Basic Widgets.
Format Express - Instant online format for JSON / XML / SQL.
FOSSA - Scalable, end-to-end management for third-party code, license compliance and vulnerabilities.
Hook Relay - Add webhook support to your app without the hassles: done-for-you queueing, retries with backoff, and logging. The free plan has 100 deliveries per day, 14-day retention, and 3 hook endpoints.
http2.pro — HTTP/2 protocol readiness test and client HTTP/2 support detection API.
kandi — Jumpstart Application Development: build custom functions, and use cases, and complete applications faster through code snippets and open-source library reuse.
Base64 decoder/encoder — Online free tool for decoding & encoding data.
newreleases.io - Receive notifications on email, Slack, Telegram, Discord, and custom webhooks for new releases from GitHub, GitLab, Bitbucket, Python PyPI, Java Maven, Node.js NPM, Node.js Yarn, Ruby Gems, PHP Packagist, .NET NuGet, Rust Cargo and Docker Hub.
OnlineExifViewer — View EXIF data online instantly for a photo including GPS location and metadata.
PDFMonkey — Manage PDF templates in a dashboard, call the API with dynamic data, and download your PDF. Offers 300 free documents per month.
Pika Code Screenshots — Create beautiful, customizable screenshots from code snippets and VSCode using the extension.
QuickType.io - Quickly auto-generate models/class/type/interface and serializers from JSON, schema, and GraphQL for working with data quickly & safely in any programming language. Convert JSON into gorgeous, typesafe code in any language.
RandomKeygen - A free mobile-friendly tool that offers a variety of randomly generated keys and passwords you can use to secure any application, service, or device.
ray.so - Create beautiful images of your code snippets.
readme.com — Beautiful documentation made easy, free for Open Source.
redirection.io — SaaS tool for managing HTTP redirections for businesses, marketing and SEO.
redirect.ing - Fast & secure domain forwarding without managing servers or SSL certificates. Free plan includes 10 hostnames and 100,000 requests per month.
redirect.pizza - Easily manage redirects with HTTPS support. The free plan includes 10 sources and 100,000 hits per month.
ReqBin — Post HTTP Requests Online. Popular Request Methods include GET, POST, PUT, DELETE, and HEAD. Supports Headers and Token Authentication. Includes a basic login system for saving your requests.
Smartcar API - An API for cars to locate, get fuel tank, battery levels, odometer, unlock/lock doors, etc.
snappify - Enables developers to create stunning visuals. From beautiful code snippets to fully fletched technical presentations. The free plan includes up to 3 snaps at once with unlimited downloads and 5 AI-powered code explanations per month.
Sunrise and Sunset - Get sunrise and sunset times for a given longitude and latitude.
superfeedr.com — Real-time PubSubHubbub compliant feeds, export, analytics. Free with less customization
SurveyMonkey.com — Create online surveys. Analyze the results online. The free plan allows only 10 questions and 100 responses per survey.
Tiledesk - Create chatbots and conversational apps. Bring them omnichannel: from your website (live chat widget) to WhatsApp. Free plan with unlimited chatbots.
Versionfeeds — Custom RSS feeds for releases of your favorite software. Have the latest versions of your programming languages, libraries, or loved tools in one feed. (The first 3 feeds are free)
videoinu — Create and edit screen recordings and other videos online.
Webacus — Access a wide range of free developer tools for encoding, decoding, and data manipulation.
⬆️ Back to Top

Remote Desktop Tools
Getscreen.me — Free for 2 devices, no limits on the number and duration of sessions
Apache Guacamole™ — Open source clientless remote desktop gateway
RemSupp — On-demand support and permanent access to devices (2 sessions/day for free)
RustDesk - Open source virtual/remote desktop infrastructure for everyone!
⬆️ Back to Top

Game Development
itch.io — Free/Paid assets like sprites, tile sets, and character packs.
Gamefresco.com — Discover, collect, and share free game assets from game artists everywhere.
GameDevMarket — Free/Paid assets like 2D, 3D, Audio, GUI.
OpenGameArt — OpenSource Game Assets like music, sounds, sprites, and gifs.
CraftPix — Free/Paid assets like 2D, 3D, Audio, GUI, backgrounds, icons, tile sets, game kits.
Game Icons - Free styleable SVG/PNG icons provided under a CC-BY license.
LoSpec — Online tools for creating pixel art and other restrictive digital art, lots of tutorials/pallet list available to choose from for your games
ArtStation - MarketPlace for Free/Paid 2D, 3D assets & audios, icons, tile sets, game kits. Also, It can be used for showcasing your art portfolio.
Rive - Community assets as well as create your own game assets using its free plan.
Poly Pizza - Free low poly 3D assets
3Dassets.one - Over 8,000 free/paid 3D models, and PBR materials for making textures.
Kenney - Free (CC0 1.0 Universal licensed) 2D, 3D, Audio, and UI game assets.
Poliigon - Free and paid textures (with variable resolution), models, HDRIs, and brushes. Offers free plugins to export to software like Blender.
Freesound - Free collaborative sound library offerer with different CC licenses.
⬆️ Back to Top

Other Free Resources
Wikimint Developer - Always free tools for web developers that includes CSS minify unminify, image optimizer, image resizer, case convertor, CSS validator, JavaScript compiler, HTML editor, etc.
ElevateAI - Get up to 200 hours of audio transcription for free every month.
get.localhost.direct — A better *.localhost.direct Wildcard public CA signed SSL cert for localhost development with sub-domain support
Framacloud — A list of Free/Libre Open Source Software and SaaS by the French non-profit Framasoft.
github.com — FOSS for Dev — A hub of free and Open Source software for developers.
GitHub Education — Collection of free services for students. Registration required.
Markdown Tools - Tools for converting HTML, CSVs, PDFs, JSON, and Excel files to and from Markdown
Microsoft 365 Developer Program — Get a free sandbox, tools, and other resources you need to build solutions for the Microsoft 365 platform. The subscription is a 90-day Microsoft 365 E5 Subscription (Windows excluded) which is renewable. It is renewed if you're active in development(measured using telemetry data & algorithms).
Pyrexp — Free web-based regex tester and visualizer for debugging regular expressions.
RedHat for Developers — Free access to Red Hat products including RHEL, OpenShift, CodeReady, etc. exclusively for developers. Individual plan only. Free e-books are also offered for reference.
smsreceivefree.com — Provides free temporary and disposable phone numbers.
sandbox.httpsms.com — Send and receive test SMS messages for free.
SimpleBackups.com — Backup automation service for servers and databases (MySQL, PostgreSQL, MongoDB) stored directly into cloud storage providers (AWS, DigitalOcean, and Backblaze). Provides a free plan for 1 backup.
SnapShooter — Backup solution for DigitalOcean, AWS, LightSail, Hetzner, and Exoscale, with support for direct database, file system and application backups to s3 based storage. Provides a free plan with daily backups for one resource.
Themeselection — Selected high quality, modern design, professional and easy-to-use Free Admin Dashboard Template, HTML Themes and UI Kits to create your applications faster!
Web.Dev — This is a free tool that allows you to see the performance of your website and improve the SEO to get a higher rank list in search engines.
SmallDev.tools — A free tool for developers that allows you to Encode/Decode various formats, Minify HTML/CSS/Javascript, Beautify, Generate Fake/Testing datasets in JSON/CSV & multiple other formats and many more features. With a delightful interface.
UseCSV by Layercode — Add CSV and Excel import to your web app in minutes. Give your users an enjoyable and robust data import experience. Get Started for Free without any credit card details, and start integrating UseCSV today. You can create unlimited Importers and upload files up to 100Mb.
Buttons Generator — 100+ buttons you can use in your project.
WrapPixel — Download High Quality Free and Premium Admin dashboard template created with Angular, React, VueJs, NextJS, and NuxtJS!
Utils.fun — All offline daily and development tools based on the browser's computing power, including watermark generation, screen recording, encoding and decoding, encryption and decryption, and code formatting, are completely free and do not upload any data to the cloud for processing.
Free Code Tools — Effective code tools which are 100% free. Markdown editor, Code minifier/beautifier, QR code generator, Open Graph Generator, Twitter card Generator, and more.
regex101 — Free this website allows you to test and debug regular expressions (regex). It provides a regex editor and tester, as well as helpful documentation and resources for learning regex.
Kody Tools — 100+ dev tools including formatter, minifier, and converter.
AdminMart — High-Quality Free and Premium Admin Dashboard and Website Templates created with Angular, Bootstrap, React, VueJs, NextJS, and NuxtJS!
Glob tester — A website that allows you to design and test glob patterns. It also provides resources to learn glob patterns.
SimpleRestore - Hassle-free MySQL backup restoration. Restore MySQL backups to any remote database without code or a server.
360Converter - Free tier useful website to convert: Video to Text && Audio to Text && Speech to Text && Real-time Audio to Text && YouTube Video to Text && add Video Subtitle. Maybe it will be helpful in a short video conversion or in a short youtube tutorial:)
QRCodeBest - Create custom QR codes with 13 templates, full privacy, and personal branding. Features tracking pixels, project categorization, and unlimited team seats on QRCode.Best.
PostPulse - Boost your online presence, enhance your SEO and site ranking with monthly AI-crafted posts to SEO-optimized domains The free Plan allows you to manually publish one Post on our site every month.
PageTools - Offers a suite of forever free AI-powered tools to help you generate essential website policies, create social media bios, posts and web pages with a simple one-click interface.
MySQL Visual Explain - Easy-to-understand and free MySQL EXPLAIN output visualizer to optimize slow queries.
Killer Coda - Interactive playground in your browser to study Linux, Kubernetes, Containers, Programming, DevOps, Networking
