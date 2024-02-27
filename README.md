# Internship-Project
Social Buzz data analytics
## Project/Goals
An analysis of content categories that highlighting the top 5 categories with the largest popularity scores

## Business overview

Social Buzz is a very fast growing social media business that emphasizes content by keeping users anonymous, only tracking user reactions on content. There are over 100 ways in which users can interact with content, spanning beyond the traditional reactions of likes, dislikes, and comments. For this reason; trending content, as opposed to individual users, is at the forefront of user feeds.
In the last 5 years, Social Buzz has reached over 500 million active users each month, scalling faster than anticipated. Due to the rapid growth and digital nature of their core product, the amount of data to be processed is huge. There are over 100,000 daily pieces of content, translating to 36,500,000 pieces of content annually. The resulting data is highly unstructured and requires extremely sophisticated and expensive technology to   manage and maintain. At this point, Social Buzz requires third party firms to offer expertise in the following ways;
1) Expertise to ensure an IPO by the end of next year and guidance to ensure that this goes smoothly.
2) They are still a small company and do not have the resources to manage the scale that they are currently at. They could hire more people, but they want an experienced practice to help instead.
3) Knowledge transfer in data best practices from a large corporation.
Enter Accenture which can provide the following expertise;
- An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity

## Business problem
There is a huge influx of data, owing to the excess of 100000 posts per day. To compound the situation, the entirety of this information is in an unorganized and unstructured format, making it exceptionally challenging to comprehend.

How then can the business leverage the expansion and abundance of data effectively?

Cue my analytics team ans myself. This is where our expertise comes in, after conducting analytics and gleaning insights, we will showcase results and demonstrate the implementation of scaling analytics for production.

## Process
<li>Data understanding - A crucial element for success in data projects lies in a thorough understanding of the data. Consequently, we invested time in comprehending both the data model and the domain specific to social media business
<li>Data cleaning - Following a comprehensive understanding of the business, we proceeded to cleanse the existing datasets and deliberated on the optimal structure for a dataset tailored to address this specific problem. We used the filter function in Excel to delete duplicates after filtering for them. After understanding the optimal structure, we dropped some of the columns that were beyond the scope of the business question, for example, the url columns, they would not have added any relevance to the insights
<li>Data modelling - This process involved processing and modeling the data into a dataset capable of accurately addressing the business inquiries and generating the required results. We made use of VLOOKUP in Excel in order to join data from the content and reation types csv files to that of Reaction csv file, which was being used as the base dataset
<li>Data analysis - Utilizing our newly minted dataset, we applied analytical proficiency to unearth insights and generate visualizations that showcase these findings
<li>We used the insights to facilitate informed business decisions and provide recommendations for next steps


## Results
The top five categories, starting from the highest, are animals, science, healthy eating, technology, and food. Notably, some related categories appear in the top five. Science and technology demonstrate an interrelation, while healthy eating, a subset of food, exhibits slightly higher numbers than the broader food category.
This data presents an opportunity to initiate targeted marketing campaigns, leveraging the connections between these top categories. By capitalizing on these relationships, strategies can be developed to enhance content interaction among users.

The insight derived from the analysis suggests that users on Social Buzz may favor factual content, particularly in categories such as animals and science, which rank the highest. This implies that there is a potential interest among users for informative and educational content rather than purely entertainment-focused material. Additionally, the presence of related categories within the top five, such as healthy eating and technology, further supports this trend. Therefore, content creators and marketers could consider tailoring their strategies to prioritize factual and educational content within these categories to better resonate with the audience and potentially increase engagement levels.

## Next steps

<li>Further analyzing the subcategories within the top five categories to understand specific trends and preferences. For instance, within the "science" category, exploring subtopics such as life sciences or physical/environmental sciences could provide valuable insights into users' interests. Another example; Within the food category; what trends are favored by the users?

<li>Examining temporal patterns in content popularity to identify seasonal trends. This analysis could inform content scheduling and campaign planning amongst users to maximize relevance and engagement. It can also inform the algorithm on which content to push.

<li>Deeper analysis into users’ sentiments and reactions to different types of content within the categories. This could provide insights into which content resonates most strongly with the audience and guide content creation, marketing efforts and site lgorithms accordingly.
