Based on the 5 previous question papers you provided for **Big Data Analytics (BE IT, Semester 8, Rev-2019 C-Scheme)**, here is the **pattern-match analysis** and the **High-Probability Hit List** for your upcoming exam.

---

## The Core Pillars (Master these 3-5 chapters first)

These topics account for ~70% of the total marks across all papers:

1. **MapReduce (Matrix Multiplication & Algorithms)** – Appears in **5/5 papers** (Always a 10-mark Q)
2. **Clustering & Graph Algorithms (CPM / CURE)** – Appears in **5/5 papers**
3. **PCY Algorithm (Frequent Itemsets)** – Appears in **4/5 papers**
4. **DGIM Algorithm (Streaming)** – Appears in **4/5 papers**
5. **NoSQL (Column Family, Graph Store, CAP/BASE)** – Appears in **5/5 papers**

---

## The "Repeater" Bank (Direct questions that keep appearing)

These exact or near-identical questions have appeared in **3+ papers**:

| Topic | Appeared in |
|-------|--------------|
| MapReduce pseudo code to multiply two matrices | May'23, Dec'23, May'24, Dec'24, May'25 |
| Clique Percolation Method (CPM) with graph example | May'23, Dec'23, Dec'24, May'25 |
| PCY algorithm with hash function & min support | May'23, Dec'23, May'24, Dec'25 |
| DGIM algorithm for counting 1's in a stream | Dec'23, May'24, Dec'24, Dec'25 |
| Collaborative filtering vs Content-based filtering | May'23, Dec'23, May'25 |
| HITS algorithm (Hub & Authority scores) | May'23, Dec'23, Dec'24 |
| CURE algorithm for clustering | May'23, Dec'23, May'25, Dec'25 |
| CAP theorem & BASE property in NoSQL | May'23, Dec'23, May'24 |

---

## High-Yield Practice List (Curated for 3-hour mock exam)

**Prioritize in this order:**

1. Write MapReduce pseudo code to multiply two matrices. Show example step-by-step. **[10 marks]**
2. Apply PCY algorithm to find frequent itemsets (support=3, h(i,j)=i*j mod 8) for given transactions. **[10 marks]**
3. Explain DGIM algorithm with example binary stream. **[10 marks]**
4. Apply CPM to find all communities in a given graph. Show steps. **[10 marks]**
5. Explain HITS algorithm. Compute Hub & Authority scores after 2 iterations. **[10 marks]**
6. Compare Collaborative filtering vs Content-based filtering with real-life examples. **[10 marks]**
7. Draw Hadoop ecosystem architecture. Explain 5 components. **[10 marks]**
8. Explain Column family store & Graph store NoSQL patterns with examples. **[10 marks]**
9. Explain CURE algorithm & its advantages over traditional clustering. **[10 marks]**
10. Explain Flajolet-Martin algorithm for distinct element estimation. **[5-10 marks]**
11. Explain MapReduce grouping & aggregation with example. **[10 marks]**
12. Write short note on: Bloom filter, CAP theorem, KNN algorithm, Relational Algebra in MapReduce. **[5 marks each]**

---

## The "Wildcard" Prediction (Due for a comeback)

### **Flajolet-Martin (FM) Algorithm** – Hasn't appeared directly since May'23 and Dec'25 (only in short notes).  
📌 **Last seen:** May'23 (Q6a) and Dec'25 (Q6b).  
📌 **Why it's due:** It's a classic streaming algorithm, often paired with DGIM. The examiner has asked "Bloom filter" and "FM algorithm" as short notes in recent papers. Expect a **5-mark or full 10-mark question** asking you to apply FM on a stream with hash functions.

**Prepare this exact style:**
> Stream: 1,3,5,4,6,1,5,9,3,2  
> Hash functions: h(x)=x+1 mod 16, h(x)=2x+3 mod 16, h(x)=3x+1 mod 16  
> Estimate distinct elements.

---

## Predicted Exam Structure for your 3-hour paper

| Section | Type | Marks | Likely Topics |
|---------|------|-------|----------------|
| Q1 (Compulsory) | 4 × 5 = 20 | Short notes | Big Data characteristics, CAP/BASE, MapReduce phases, Bloom filter, Distance measures |
| Q2 | 2 × 10 = 20 | Long | Matrix multiplication + HDFS/Hadoop ecosystem |
| Q3 | 2 × 10 = 20 | Long | PCY algorithm + DGIM algorithm |
| Q4 | 2 × 10 = 20 | Long | CPM (graph communities) + Recommendation systems (collaborative vs content) |
| Q5 | 2 × 10 = 20 | Long | CURE algorithm + PageRank / HITS |
| Q6 | 2 × 10 = 20 | Long/Short notes | FM algorithm / Relational Algebra / KNN / Bloom filter |

> **Note:** You must attempt Q1 + any 3 from Q2–Q6. So prepare **Q1 fully** + your strongest 3 long-answer topics.

---

## Time Management Strategy for Exam Day

| Activity | Time |
|----------|------|
| Q1 (20 marks = 4 short answers) | 30 min |
| Q2 (20 marks = 2 long answers) | 40 min |
| Q3 (20 marks) | 40 min |
| Q4 (20 marks) | 40 min |
| **Buffer for diagrams, checking, complex calculations** | 30 min |
| **Total** | **180 min (3 hours)** |

---

Good luck! Would you like me to generate a **full model answer** for any of the top 5 predicted questions?