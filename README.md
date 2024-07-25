# Information Retrieval on SEC 10-K Documents

<<<<<<< HEAD
The financial statements of a company provide a lot of valuable insights about it. However, extracting crucial information from these statements is time-consuming and often quite cumbersome. We propose an interactive information retrieval system that can query the financial information of a company, summarise SEC 10-K filings, and visualise a company’s performance over the past few years. Our proposed system can be used by, but not limited to, investors, traders, analysts, auditors, and corporate executives.
=======
The financial statements of a company provide a lot of valuable insights about it. However, extracting crucial information from these statements is time-consuming and often quite cumbersome. We propose an interactive information retrieval system that can query the financial information of a company, summarise SEC 10-K filings and visualise a company’s performance over the past few years. Our proposed system can be used by, but not limited to, investors, traders, analysts, auditors, and corporate executives.
>>>>>>> 126d7be (Project file added)

## Folder Structure
```
.
├── Backend
<<<<<<< HEAD
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
=======
│   ├── helper.py
│   ├── requirements.txt
│   └── server.py
├── Frontend
│   ├── babel.config.js
│   ├── package.json
│   ├── public
│   ├── server.js
│   ├── src
│   ├── static.json
│   └── vue.config.js
├── Other
│   ├── Notebooks
│   ├── Presentation.pdf
│   └── Report.pdf
>>>>>>> 126d7be (Project file added)
└── README.md
```
## Setup 🛠️

### Backend
<<<<<<< HEAD
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
=======
- Install the required libraries using `pip install -r requirements.txt`
- Download the data folder from [here](https://drive.google.com/drive/folders/1bidGP1Les9kusT4RcOqL_jvCKWIad3db?usp=sharing) and place it in the Backend directory

### Frontend
- Install the required node modules using ```npm install```
>>>>>>> 126d7be (Project file added)

## Build ⚙️

### Backend
<<<<<<< HEAD
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
=======
```
cd Backend
python3 server.py
```
### Frontend
```
cd Frontend
npm run serve
```

## Features :star:
>>>>>>> 126d7be (Project file added)
- User can give natural language queries to search for relevant financial documents.
- Important parts of 10-K documents of a company are summarised.
- Important tables are extracted and presented to the user.
- Change in crucial financial indicators of a company are visualised using plots.
- Sentiment Analysis on Management's Decisions.

## Evaluation 📊
<<<<<<< HEAD

| Method      | Precision@3 | Precision@5 | Precision@10 |
|-------------|-------------|-------------|--------------|
=======
| Method      | Precision@3 | Precision@5 | Precision@10 |
| ----------- | ----------- | ----------- | ------------ |
>>>>>>> 126d7be (Project file added)
| TF-IDF      | 0.78        | 0.74        | 0.54         |
| log(TF)-IDF | 0.48        | 0.46        | 0.41         |
| BM-25       | 0.66        | 0.65        | 0.51         |

<<<<<<< HEAD
=======
## Team

[Anuneet Anand](https://github.com/anuneetanand)    
[Isha Gupta](https://github.com/IshaGupta18)  
[Osheen Sachdev](https://github.com/oshhh)  
[Paras Mehan](https://github.com/parasmehan123)   
[Uday Narayan Goel](https://github.com/uday2000)    
>>>>>>> 126d7be (Project file added)
