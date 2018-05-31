## [AWS re:Invent 2017](https://reinvent.awsevents.com/) Geospatial Talks
Talks, sessions and workshops that may be of interest to those working with geospatial data. PRs accepted!

### [STG205 - #EarthonAWS: How NASA Is Using AWS](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14954)

[Video](https://www.youtube.com/watch?v=Sh7FB-tkYXM) | [Slides](https://www.slideshare.net/AmazonWebServices/stg205earthonaws-how-nasa-is-using-aws)

Organizations around the world are facing a “data tsunami” as next-generation sensors produce enormous volumes of earth observation data. Come learn how NASA is leveraging AWS to efficiently work with data and computing resources at a massive scale. NASA is transforming its earth science EOSDIS (Earth Observing System Data Information System) program by moving data processing and archiving to the cloud. NASA anticipates that their data archives will grow from 16 PB today to over 400 PB by 2023 and 1 Exabyte by 2030. They’re moving to the cloud to scale their operations for this new paradigm.

### [ABD402 - How Esri Optimizes Massive Image Archives for Analytics in the Cloud](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14666)

[Video](https://www.youtube.com/watch?v=U486YxlDoeM) | [Slides](https://www.slideshare.net/AmazonWebServices/how-esri-optimizes-massive-image-archives-for-analytics-in-the-cloud-abd402-reinvent-2017)

Petabyte scale archives of satellites, planes, and drones imagery continue to grow exponentially. They mostly exist as semi-structured data, but they are only valuable when accessed and processed by a wide range of products for both visualization and analysis. This session provides an overview of how ArcGIS indexes and structures data so that any part of it can be quickly accessed, processed, and analyzed by reading only the minimum amount of data needed for the task. In this session, we share best practices for structuring and compressing massive datasets in Amazon S3, so it can be analyzed efficiently. We also review a number of different image formats, including GeoTIFF (used for the Public Datasets on AWS program, Landsat on AWS), cloud optimized GeoTIFF, MRF, and CRF as well as different compression approaches to show the effect on processing performance. Finally, we provide examples of how this technology has been used to help image processing and analysis for the response to Hurricane Harvey.

### [EUT302 - Data Ingestion at Seismic Scale: Best practices for processing petabyte scale HPC workloads in the Cloud](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14599)

[Video](https://www.youtube.com/watch?v=wq4mgC9FCRA) | [Slides](https://www.slideshare.net/AmazonWebServices/eut302data-ingestion-at-seismic-scale-best-practices-for-processing-petabyte-scale-hpc-workloads-in-the-cloud)

With geoseismic datasets that are petabytes in size and growing, finding tomorrow's energy is increasingly data and compute intensive. Hess Corporation, a global energy company, needed to be able to respond quickly to changing oil market demands, while minimizing costs. By migrating petabytes of data and running high performance computing (HPC) workloads on AWS, Hess reduced compute costs and accelerated time in which geologists received results. In this session, you will learn how Hess built a GeoSeismic data repository on AWS, by leveraging S3 and EFS, and processes that data by building HPC clusters on-demand using the GPU-enabled P2 instance family. Additionally, you will learn how the Hess subsurface computing team was able to move from running on premise cap-ex driven GPU clusters to an op-ex driven on-demand model in the AWS cloud.

### [CMP201 - Auto Scaling: The Fleet Management Solution for Planet Earth](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14605)

[Video](https://www.youtube.com/watch?v=WUUbOQyrnJU) | [Slides](https://www.slideshare.net/AmazonWebServices/auto-scaling-the-fleet-management-solution-for-planet-earth-cmp201-reinvent-2017)

Auto Scaling allows cloud resources to scale automatically in reaction to the dynamic needs of customers. This session shows how Auto Scaling offers an advantage to everyone—whether it's basic fleet management to keep instances healthy as an Amazon EC2 best practice, or dynamic scaling to manage extremes. We share examples of how Auto Scaling helps customers of all sizes and industries unlock use cases and value. We also discuss how Auto Scaling is evolving to scaling different types of elastic AWS resources beyond EC2 instances. Data Scientist & Principal Investigator, Hook Hua, from NASA Jet Propulsion Laboratory (JPL) / California Institute of Technology will share how Auto Scaling is used to scale science data processing of remote sensing data from earth-observing satellite missions, and reduce response times during hazard response events such as those from earthquakes, hurricanes, floods, and volcanoes. JPL will also discuss how they are integrating their science data systems with the AWS ecosystem to expand into NASA’s next two large-scale missions with remote-sensing radar-based observations. Learn how Auto Scaling is being used at a global scale – and beyond!

### [CON326 - Remote Sensing and Image Processing on AWS](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=16433)

Video | Slides

Learn how Encirca services by DuPont Pioneer utilizes Amazon ECS powered by GPU-instances and EC2 Spot instances to run proprietary image processing algorithms against satellite imagery. Mark Lanning and Ethan Harstad, engineers at DuPont Pioneer will show how this architecture has allowed them to process satellite imagery multiple times a day for each agricultural field in the United States in order to identify crop health changes.

#### [ARC326 - Create a Serverless Image Processing Platform](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=16122)

Video | [Slides](https://www.slideshare.net/AmazonWebServices/create-a-serverless-image-processing-platform-arc326-reinvent-2017)

Are you interested in processing images at scale without launching a single virtual machine? In this workshop, we show participants how to create an entirely serverless image processing platform using Amazon Cognito, AWS Lambda, Amazon Rekognition, and Amazon Elasticsearch Service (Amazon ES). Participants leave this workshop with a web portal where users can upload images that ultimately end up in a searchable index powered by Amazon ES and Kibana.

### [CMP213 - GPU (G3) Applications in Media and Entertainment Workloads](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=16798)

[Video](https://www.youtube.com/watch?v=eMKzJnMLS3U) | [Slides](https://www.slideshare.net/AmazonWebServices/cmp213gpug3-applications-in-media-and-entertainment-workloads)

GPUs have a large application in Media and Entertainment workloads. From backend video processing and creation workloads such as VFX/Rendering, transcoding and broadcast playout to high-end creatives as well as video editing workloads. Backed by the NVIDIA Tesla M60 GPUs, G3 instances offer unparalleled power and flexibility to do complex modeling, 3D visualization, computer aided design, seismic visualization, video encoding. G3 instances are the first Amazon EC2 instances to support NVIDIA GRID Virtual Workstation capabilities, with streaming support for four monitors each with up to 4K resolution, and hardware encoding to support up to 10 High Efficiency Video Coding (HEVC) H.265 1080p30 streams or up to 18 H.264 1080p30 streams per GPU for faster video frame processing and improved image fidelity. In this session we will highlight two criticial Media workloads Video Editing via remote application streaming and Broadcast Playout origination from the AWS cloud. We will have Pop Media discuss their remote video editing in the cloud that enables secure remote, real-time editorial and image processing session views. This will be followed by Evertz regarding Discovery Channel’s broadcast Playout application for several live Discovery channels currently.

### [CMP216 - Use Amazon EC2 Spot Instances to Deploy a Deep Learning Framework on Amazon ECS](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=16676)

Video | [Slides](https://www.slideshare.net/AmazonWebServices/cmp216use-amazon-ec2-spot-instances-to-deploy-a-deep-learning-framework-on-amazon-ecs)

Deep learning, an implementation of machine learning, uses neural networks to solve complex problems like computer vision, natural language processing, and recommendations.  Deep learning libraries and frameworks enable developers to enhance the capabilities of their applications and projects.  In this workshop, learn how to build and deploy a powerful deep learning framework, Apache MXNet, on containers.  The portability and resource management benefit of containers enables developers to focus less on infrastructure and more on building.  The lab first demonstrates the automation capabilities of AWS CloudFormation to stand up core infrastructure. We also leverage Spot Fleet for the cost benefit of using Spot Instances, especially important for developer environments. Next we create an MXNet container in Docker and deploy it with Amazon ECS.  Finally, we explore image classification with MXNet to validate that everything is working as expected.

### [MCL405 - Custom Image Recognition with Deep Learning Using Apache MXNet and Convolutional Neural Networks](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14645)

Video | Slides

Convolutional Neural Networks (CNNs) are a category of deep learning algorithms. They were first brought to prominence in 2012 when Alex Krizhevsky used them to win that year’s ImageNet competition to find the best computer vision algorithms. Since then, they have emerged as one of the most influential innovations in computer vision, and have been used to identify objects like faces and traffic signs, in addition to powering vision in robots and self-driving cars. In this Chalk Talk, we explain how CNNs work and demonstrate how to train an image recognition model on your custom image repositories using Gluon, the new intuitive, dynamic programming interface for Apache MXNet.

### [SRV315 - How We Built a Mission-Critical, Serverless File Processing Pipeline for over 100 Million Photos](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=14823)

[Video](https://www.youtube.com/watch?v=Hy2n-fC-r98) | [Slides](https://www.slideshare.net/AmazonWebServices/srv331build-a-multiregion-serverless-application-for-resilience-and-high-availabilitypdf) | [Slides](https://www.slideshare.net/AmazonWebServices/srv315how-we-built-a-missioncritical-serverless-file-processing-pipeline-for-over-100-million-photos)

In this session, principal architect Mike Broadway describes how HomeAway built a high-throughput, scalable pipeline for manipulating, storing, and serving hundreds of image files every second with Lambda, Amazon S3, DynamoDB, and Amazon SNS. He also shares best practices and lessons learned as they scaled their mission-critical On Demand Image Service (ODIS) system into production. Lambda functions form the backbone of ODIS, which handles over 100 million photographs that are uploaded to HomeAway's vacation rental platform. HomeAway is a vacation rental marketplace with more than 2 million rentals in 190 countries and is part of Expedia.

### [SRV318 - Research at PNNL: Powered by AWS](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=15015)

[Video](https://www.youtube.com/watch?v=2-1T-ly1ylE) | [Slides](https://www.slideshare.net/AmazonWebServices/srv318research-at-pnnl-powered-by-aws)

Pacific Northwest National Laboratory's rich data sciences capability has produced novel solutions in numerous research areas including image analysis, statistical modeling, and social media (and many more!). See how PNNL software engineers utilize AWS to enable better collaboration between researchers and engineers, and to power the data processing systems required to facilitate this work, with a focus on Lambda, EC2, S3, Apache Nifi and other technologies. Several approaches will be covered including lessons learned.

### [SRV333 - Designing and Implementing a Serverless Media Processing Workflow Using AWS Step Functions](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=15438)

Video | [Slides](https://www.slideshare.net/AmazonWebServices/designing-and-implementing-a-serverless-media-processing-workflow-using-aws-step-functions-srv333-reinvent-2017)

This workshop demonstrates how to use AWS Step Functions to coordinate multiple AWS Lambda functions using visual workflows. You learn how to build a Step Functions state machine to orchestrate a multi-step serverless application. You work in teams to design and implement an image recognition and processing workflow using AWS Step Functions, AWS Lambda, Amazon S3, Amazon DynamoDB, and Amazon Rekognition. The workflow process photos uploaded to Amazon S3 and extract metadata from the image, such as geolocation, size, format, and time. It then uses image recognition to tag objects in the photo and produce a thumbnail. Prerequisites: Experience using AWS, an AWS account, AWS CLI. We provide AWS credits for use in the hands-on lab. Bring a laptop.

### [WPS204 - Effective Emergency Response in AWS](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=15017)

[Video](https://www.youtube.com/watch?v=Ud73Sq1zzkQ) | [Slides](https://www.slideshare.net/AmazonWebServices/wps204effective-emergency-response-in-awspdf)

Emergencies happen with no notice, whether with weather-related events or man-made incidents. Countless lives can be saved not only by predicting disastrous events but also by reacting quickly and effectively.  In this session, you will discover how organizations are using AWS capabilities to predict and respond to emergencies around the world. StormSense, a project led by City of Virginia Beach enhances the capability of VA Beach and the neighboring communities of Hampton Roads, VA to predict coastal flooding resulting from storm surge, rain, and tides in ways that are replicable, scalable, measurable, and make a difference worldwide. LiveSafe, A communications platform to improve safety and prevention efforts - puts a mobile security system in the hands of everyone in organization, deputizing employees so they can feel involved and empowered to do something when they see something. LiveSafe’s cloud-based command dashboard receives tips in real time and allows security officials to respond via secure live chat.
