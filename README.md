# 📊 SEC 10-K Document Information Retrieval System

The financial statements of a company provide valuable insights about its performance. However, extracting crucial information from these statements can be time-consuming and cumbersome. This interactive information retrieval system allows users to query the financial information of a company, summarize SEC 10-K filings, and visualize the company's performance over the past few years. This system is ideal for investors, traders, analysts, auditors, and corporate executives.

## 📁 Folder Structure

```
.
├── Backend
│ ├── helper.py
│ ├── requirements.txt
│ └── server.py
├── Frontend
│ ├── babel.config.js
│ ├── package.json
│ ├── public
│ ├── server.js
│ ├── src
│ ├── static.json
│ └── vue.config.js
├── Other
│ ├── Notebooks
│ ├── Presentation.pdf
│ └── Report.pdf
└── README.md
```


## Setup 🛠️

### Backend
1. Install the required libraries using:
    ```bash
    pip install -r requirements.txt
    ```
2. Download the data folder from [here](#) and place it in the `Backend` directory.

### Frontend
1. Install the required node modules using:
    ```bash
    npm install
    ```

## Build ⚙️

### Backend
1. Navigate to the Backend directory:
    ```bash
    cd Backend
    ```
2. Run the server:
    ```bash
    python3 server.py
    ```

### Frontend
1. Navigate to the Frontend directory:
    ```bash
    cd Frontend
    ```
2. Run the frontend server:
    ```bash
    npm run serve
    ```

## Features ⭐
- User can give natural language queries to search for relevant financial documents.
- Important parts of 10-K documents of a company are summarised.
- Important tables are extracted and presented to the user.
- Change in crucial financial indicators of a company are visualised using plots.
- Sentiment Analysis on Management's Decisions.

## Evaluation 📊

| Method      | Precision@3 | Precision@5 | Precision@10 |
|-------------|-------------|-------------|--------------|
| TF-IDF      | 0.78        | 0.74        | 0.54         |
| log(TF)-IDF | 0.48        | 0.46        | 0.41         |
| BM-25       | 0.66        | 0.65        | 0.51         |

