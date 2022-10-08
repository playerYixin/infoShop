# infoShop
This is an infomation processing project, the goal of which is to automatically collect and analyze information from RSS feeds and generate a newsletter.

At early stage, the project is created in my personal favor to make everyday reading more efficient. Hopefully, this tool will find more uses in the future.

Output Newsletter:

Medium: https://medium.com/yixins-info-shop 

Mirror: https://mirror.xyz/0x151c218Aa35651C7d7B1822ea213C50609648f7F

### Milestone #1: Infancy

### V0.1

#### Targets: 

1. Collect articles from subscribed RSS feeds daily and select those pushed by manualy tagged feeds to generate a daily reading list.
2. Establish a newsletter to publish the daily reading list everyday.
3. Curate the content and keep reading time cost within 1 hour.

#### TODOs:

- [x] Categorize favorite RSS feeds and set an initial reading strategy.
- [x] Fetch RSS reviewer's local database successfully.
- [x] Fetch feeds' metadata successfully.
- [x] Add personal tags to feeds' metadata.
- [x] Generate a daily reading list in Markdown format with a link attached to each article title.
- [x] Publish the Markdown file manually to Medium and Mirror.
- [ ] Publish the Markdown file automatically to Medium.
  - [x] Get access token of Medium's API.
  - [ ] Requests author ID by using Python's package *requests* (failed due to bad connection)
- [ ] Estimate the average reading time cost (sample size: 7 days)
- [ ] Adjust reading strategy and modify the analyzer accordingly.
- [ ] Add a short comment to each article in the reading list.

### V0.2

#### Targets:

1. Find hot topics based on a recent period of articles' titles. 
2. Generate a trend analysis report.
3. Append the report to the newsletter.

#### TODOs:

- [ ] Generate a list of hot topics by NLP algorithm.
- [ ] Categorize articles according to topics.
- [ ] Design an algorithm to categorize the topics.
- [ ] Design a sorting strategy to select the most relative topics and articles.
- [ ] Design the trend analysis content in the newsletter.
- [ ] Update the newsletter's format.
