# CS3220-Assignment6
# Assignment 6 - Redis Queries

## How to run this project

### 1. Import the tweet data into MongoDB
Download the dump file and run this in your terminal:
```bash
mongoimport -h localhost:27017 -d ieeevisTweets -c tweet --file ieeevis2020Tweets.dump
```

### 2. Start Redis
Open Docker Desktop, then run:
```bash
docker start redis-stack
```

### 3. Install dependencies
```bash
npm install
```

### 4. Run the queries
```bash
node Query1.js
node Query2.js
node Query3.js
node Query4.js
node Query5.js
```

## What each query does
- **Query1** - Counts total number of tweets
- **Query2** - Computes total number of favorites
- **Query3** - Counts distinct users
- **Query4** - Top 10 users with the most tweets
- **Query5** - Stores tweet lists and details per user
