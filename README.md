
# B2B Relationships Analysis from Business Graph Data



## Introduction
This report explores the intricate web of business-to-business relationships through a comprehensive analysis of a business graph, utilizing data collected by the startup Relato during 2015-2016. The dataset contains over 373,000 links representing various types of business interactions, such as partnerships, customer-supplier dynamics, and competitive engagements.

## Dataset Description
Source: Relato (2015-2016) Composition: 373,663 company links Type of Links: Partnerships, customer, supplier, competitor, investment Unique Identifier: Domain names

It contains links between businesses pulled from the web. It contains 373,663 links between companies, of the types "partnership" (one company listed on another company's partnership page), "customer" (one company listed on another company's example customer page), "competitor" (co-bidders on AdWords above some limit), "investment" (a company listed on a VC's website), "supplier" (the inverse of the "customer" type. This dataset was used to drive both a lead generation system where metrics on the graph fed into a classification for leads (lead/no lead) and a market visualization system (a force directed layout of markets and their segments).

## Data Structure
Initial Data


Number of nodes: 53326


Number of edges: 251280

## Objectives
The objectives of this analysis are to:
1	Analyze how companies relate within a large network.
2	Identify key players and influential entities using measures of centrality.
3	Explore potential applications of this data in market analysis and lead generation.
Exploring Measures of Centrality

#### We employed several centrality measures to understand different aspects of influence and connectivity within the network:

•	Degree Centrality: Identifies the most connected companies.

•	Betweenness Centrality: Pinpoints companies that frequently act as bridges across different business clusters.

•	Eigenvector Centrality: Assesses influence within influential circles, enhanced by net worth data.

## Results and Visualizations
The following images and descriptions provide a visual summary of the findings from our analysis:

### Network Overview

#### ![overall coding](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/af31f6f9-42df-493d-a0ba-144deff4d5cc)

## ![overall](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/a3f7a730-2ee9-4f18-80ca-7bfe967c0a2f)

#### ![counts](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/fc90934d-2574-4bab-b6ea-b76b81465c57)
#### ![distribution](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/c52ff060-4858-4ca4-b056-640a6ac18322)


#### ![centrality](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/7110df02-37d0-4bfb-8fbd-45269acae9e6)


#### ![non-supplier network](https://github.com/katewly/SNA2_Luyao_project4/assets/167985824/22af7b1b-33fe-4945-a239-a7ed9611bf27)




## Analysis
The analysis of the business graph highlighted the following insights:


•	Degree Centrality: A few companies hold a significant number of direct connections, making them central hubs within the network.
•	Betweenness Centrality: Companies acting as bridges are critical for the flow of resources and information, holding strategic positions that could be leveraged in negotiations or partnership developments.
•	Eigenvector Centrality: Companies that are influential among other influential companies often control or significantly impact market dynamics.
These findings are supported by the visual distributions and network graphs, which illustrate the non-uniformity in company connectivity and influence.

## Conclusion


The comprehensive analysis of the business graph from Relato’s database has revealed significant insights into the structure and dynamics of B2B relationships. Our study confirms the presence of highly influential companies that dictate the flow and structure of the network, which could be targets for strategic partnerships or competitive analysis.

Further, the project demonstrated the practical application of network theory in real-world business scenarios, aiding in market analysis and lead generation. The centrality measures, supplemented by additional data such as company net worth, provided a deeper understanding of not only who the key players are but also how they influence the market.

This study serves as a foundation for further exploration and application of network analysis in business strategy, offering actionable insights for companies navigating complex market landscapes.

### External Resources
https://data.world/datasyndrome/relato-business-graph-database
