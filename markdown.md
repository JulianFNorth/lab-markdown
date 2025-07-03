#Julian Fullmer – Dev Log (July 2, 2025)

## What I Learned Today

1. I learned how LLMs *think*: they take input, use their weights, and calculate the next token.
    * **I was also amazed at how many parameters (billions) a model needs to function.**
2. I learned how to structure markdown (*md*) files, with headings and other syntax.
### Additional Insight

- AI models are both amazing and scary (==stochastic==).
    - **Because of this, I’ll try to stay cautious of AI, but also embrace its potential.**
- Something I found funny was how base LLaMA models can be confidently wrong — they act aloof sometimes.

## Lab Reflection

> I was really *challenged by trying to understand the differences between tokenization and embedding*.  
> But after reviewing how Token IDs get translated to vectors, I closed the gap in my knowledge.

## Code Snippet
```
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split

X = df[["feature1", "feature2"]]
y = df["target"]

X_train, X_test, y_train, y_test = train_test_split(X, y)
model = LinearRegression()
model.fit(X_train, y_train)
```

## Helpful Links

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [CSV File Handling in Python](https://realpython.com/python-csv/)

---

