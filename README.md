# 🏛️ Community Detection on the 116th U.S. Congress

This project explores how members of the **116th U.S. Congress (2019–2021)** form communities and collaborate on legislation.  
Using **graph analysis** and the **Louvain algorithm**, we detect clusters of legislators based on bill sponsorship and co-sponsorship patterns.  
The results highlight how political parties, committees, and shared policy interests shape the network structure of Congress.

## 📊 Dataset
The data was collected from the official [U.S. Congress website](https://www.congress.gov) through **web scraping**:
- `house_legislation_116.csv` → Bills introduced in the House (title, sponsor, co-sponsors, subjects, policy area, legislative progress).  
- `members_house_116.csv` → Member profiles (name, state, party affiliation, committee assignments).  

## 🛠️ Tools & Libraries
- **Python**  
- **NetworkX** → graph building & community detection  
- **Pandas** → data wrangling  
- **Matplotlib** → visualization  
- **Scrapy** → data scraping  

## 🚀 Key Features
- Build a social network graph of Congress members.  
- Apply **Louvain algorithm** to detect communities.  
- Visualize clusters and analyze collaboration patterns. 
