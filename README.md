# DA-205-TravelTide-Customer_Segmentation ![image](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/51b78da1-4ee7-456f-b4c8-d7d3d9aaed4c)
  ![image](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/03b7fcd5-be4a-452d-8b52-0471cdeb5721)

In this project, we will segment customer data according to business needs and deliver data-driven recommendations based on our findings.
# Project Motivation
What is segmentation? It refers to a broad category of analytic techniques that allow us to group similar data points. In this project, data points will represent customers, whom we will group according to their shopping behavior in the context of a very specific business initiative.
              ![image](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/cef1ea76-6abd-455e-a695-fc13f38be8b3)
The focus of this Mastery Project is segmenting customers based on their shopping behavior. However, it is important to know that segmentation is a very general approach to data analysis that is broadly applicable to just about every domain. Whenever we suspect a dataset has some natural but hidden structure, we can use segmentation to reveal it. To see this, consider a non-business context like cancer diagnostics. Suppose we have an extensive collection of medical images that physicians have not reviewed for abnormalities. Segmentation can be used to cluster images with similar pixel patterns prior to review by human doctors. Then, instead of manually reviewing every image, doctors can sample images from each cluster to verify if any clusters correspond to abnormal images! This improves diagnostic speed, resulting in better patient care.
Industries such as:
Media: In journalism, segmentation can automatically categorize news stories into different topics for efficient news management and distribution.
Sports: Sports analysts can use segmentation to group players based on ability. This can help team managers make informed decisions about team selection.

From a business perspective, customer segmentation divides a customer database into groups to provide a tailored customer experience, rather than one size fits all. The business value of creating such groups is the ability to implement specific business strategies, including:

1. Customized promotions (e.g. special offers, discounts)
2. Personalized communications (e.g. targeted marketing emails)
3. Specific account policies (e.g. credit line)

The role of a data analyst in driving business value is to define segments that are meaningful and aligned with business objectives. Segmentation projects can be somewhat more open-ended and require analysts to think about the problem space from multiple points of view. Thinking deeply about business needs, customer behavior, and creative ways to apply various analytical tools makes segmentation a rewarding challenge.

# TravelTide 
E-booking startup TravelTide is a hot new player in the online travel industry. It has experienced steady growth since it was founded at the tail end of the COVID pandemic (2021–April) on the strength of its data aggregation and search technology, which is best in class. Customer feedback has shown, and industry analysts agree, that TravelTide customers have access to the largest travel inventory in the e-booking space.

Following the startup playbook, TravelTide has maintained a hyper-focus on building an unfair advantage along a limited number of dimensions—in this case, building the biggest travel inventory and making it easily searchable. Because of this narrow focus, certain aspects of the TravelTide customer experience are underdeveloped, resulting in poor customer retention. CEO Kevin Talanick is very motivated to retain and add value to existing customers with a Marketing strategy built on a solid understanding of customer behavior.
To supercharge the Marketing efforts at TravelTide as an expert in customer retention strategies, specifically rewards programs, an advanced feature proven to generate repeat business if executed well. Head of Marketing Elena’s mission is to design and execute a fantastic personalized rewards program that keeps customers returning to the TravelTide platform. It is difficult to personalize rewards for customers without first understanding them, so for the project to be successful, Elena will need to lean on the data team for customer insights.
              ![Screenshot_20230804_034312](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/bd485a81-8e79-4ba3-927d-3f003f9478cf)

# Marketing 🤝 Data
You are on the Analytics team and responsible for supporting Elena’s rewards program project. Her subject matter expertise, together with your data skills, should result in a product reflecting marketing know-how and backed by solid evidence. Elena sent a follow-up message, reproduced here:
              ![image](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/81118c0e-e6cd-4e0a-80b5-dd407f51f7bb)

Elena believes that to grab customers' attention and maximize the likelihood they will sign up for the rewards program, we want to emphasize the perk we think they are most interested in when we ask them to sign up. To give us a clear picture of the difference our analysis will make, Elena has also shared some mock-ups of rewards program invitation emails.
              ![image](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/02aa642f-5ef6-499e-ad89-dd931d15d6d1)
The email on the right is vague and requires customers to read through a bulleted list of equally important rewards. The one on the left has specific messaging about a free cancellation perk. Elena’s marketing logic is that if we believe a subset of customers will be particularly interested in free cancellation, TravelTide has a much higher chance of getting them to sign up for rewards using the email on the left.

Our mission as Data Analysts is two-fold. First, check if the data supports Elena’s hypothesis about the existence of customers that would be especially interested in the perks she is proposing, and then, for each customer, assign a likely favorite perk.

# Project Overview
* Familiarize yourself with the business context. Use SQL to extract a customer dataset. Explore the data at different levels of aggregation and form a plan for further 
  analysis.
* Make calculations related to the business context, then segment customer behavior data with statistical and visual techniques using the appropriate tools.
* Create an executive summary and slides of the customer segmentation results.
  
# Project Objectives
1. Filter TravelTide data using Elena’s (Head of Marketing) cohort definition on the TravelTide Data Processing page.
2. Aggregate Session, Flight, and Hotel data to the appropriate level, preserving fields that carry demographic or behavioral data, and merge the results into a single table.
3. Use an appropriate outlier definition to filter out extreme data points that might bias segmentation results.
4. Transform the data to remove scale bias.

  ![Social Analytics](https://github.com/SOMPODDA/DA-205-TravelTide-Project-VIII/assets/70188796/a98912d7-b0c2-431c-a580-b1f30891958a)

