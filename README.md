Description:

Firm collapse prediction has been a subject of interests for almost a century and it still ranks high among hottest topics in economics. The aim of predicting financial distress is to develop a predictive model that combines various econometric measures and allows to foresee a financial condition of a firm. The purpose of the bankruptcy prediction is to assess the financial condition of a company and its future perspectives within the context of longterm operation on the market.
This is an in-class competition for MGMT 571 at Purdue University. Please try other available data competition if you are not a student in this course. Thank you!

Evaluation:

The evaluation metric for this competition is AUC, i.e., area under the receiver operator curve.

Submission Format:

Submission files should contain the predicted probability of bankruptcy for each test sample.
The file should contain a header and have the following format:

ID, class
1, 0.01
2, 0.20
3, 0.99
4, 0.40
etc.

Dataset Description:

File descriptions:

  bankruptcy_Train.csv - the training set with 64 predictors and 1 target variable
  
  bankruptcy_Test_X.csv - the test set with ID and 64 predictors
  
  bankruptcy_sample_submission.csv - the sample submission with ID and the predicted probability of firm bankruptcy

Data fields:

  attr1 - net profit / total assets
  
  attr2 - total liabilities / total assets
  
  attr3 - working capital / total assets
  
  attr4 - current assets / short-term liabilities
  
  attr5 - [(cash + short-term securities + receivables - short-term liabilities) / (operating expenses - depreciation)] * 365
  
  attr6 - retained earnings / total assets
  
  attr7 - EBIT / total assets
  
  attr8 - book value of equity / total liabilities
  
  attr9 - sales / total assets
  
  attr10 - equity / total assets
  
  attr11 - (gross profit + extraordinary items + financial expenses) / total assets
  
  attr12 - gross profit / short-term liabilities
  
  attr13 - (gross profit + depreciation) / sales
  
  attr14 - (gross profit + interest) / total assets
  
  attr15 - (total liabilities * 365) / (gross profit + depreciation)
  
  attr16 - (gross profit + depreciation) / total liabilities
  
  attr17 - total assets / total liabilities
  
  attr18 - gross profit / total assets
  
  attr19 - gross profit / sales
  
  attr20 - (inventory * 365) / sales
  
  attr21 - sales (n) / sales (n-1)
  
  attr22 - profit on operating activities / total assets
  
  attr23 - net profit / sales
  
  attr24 - gross profit (in 3 years) / total assets
  
  attr25 - (equity - share capital) / total assets
  
  attr26 - (net profit + depreciation) / total liabilities
  
  attr27 - profit on operating activities / financial expenses
  
  attr28 - working capital / fixed assets
  
  attr29 - logarithm of total assets
  
  attr30 - (total liabilities - cash) / sales
  
  attr31 - (gross profit + interest) / sales
  
  attr32 - (current liabilities * 365) / cost of products sold
  
  attr33 - operating expenses / short-term liabilities
  
  attr34 - operating expenses / total liabilities
  
  attr35 - profit on sales / total assets
  
  attr36 - total sales / total assets
  
  attr37 - (current assets - inventories) / long-term liabilities
  
  attr38 - constant capital / total assets
  
  attr39 - profit on sales / sales
  
  attr40 - (current assets - inventory - receivables) / short-term liabilities
  
  attr41 - total liabilities / ((profit on operating activities + depreciation) * (12/365))
  
  attr42 - profit on operating activities / sales
  
  attr43 - rotation receivables + inventory turnover in days
  
  attr44 - (receivables * 365) / sales
  
  attr45 - net profit / inventory
  
  attr46 - (current assets - inventory) / short-term liabilities
  
  attr47 - (inventory * 365) / cost of products sold
  
  attr48 - EBITDA (profit on operating activities - depreciation) / total assets
  
  attr49 - EBITDA (profit on operating activities - depreciation) / sales
  
  attr50 - current assets / total liabilities
  
  attr51 - short-term liabilities / total assets
  
  attr52 - (short-term liabilities * 365) / cost of products sold)
  
  attr53 - equity / fixed assets
  
  attr54 - constant capital / fixed assets
  
  attr55 - working capital
  
  attr56 - (sales - cost of products sold) / sales
  
  attr57 - (current assets - inventory - short-term liabilities) / (sales - gross profit - depreciation)
  
  attr58 - total costs /total sales
  
  attr59 - long-term liabilities / equity
  
  attr60 - sales / inventory
  
  attr61 - sales / receivables
  
  attr62 - (short-term liabilities *365) / sales
  
  attr63 - sales / short-term liabilities
  
  attr64 - sales / fixed assets
  
  class - the response variable Y: 0 = did not bankrupt; 1 = bankrupt
