Python Implementation of Apriori Algorithm 
==========================================

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/asaini/apriori/python3) [![Build Status](https://travis-ci.org/asaini/Apriori.svg?branch=master)](https://travis-ci.org/asaini/Apriori)

The code attempts to implement the following introduction link bellow: 

http://bis.net.vn/forums/p/389/683.aspx

Interactive Streamlit App
-------------
To run steamlit follow command. 

    streamlit run streamlit_app.py 


CLI Usage
-----
To run the program with dataset provided and default values for *minSupport* = 0.15 and *minConfidence* = 0.6

    python apriori.py -f INTEGRATED-DATASET.csv

To run program with dataset  

    python apriori.py -f INTEGRATED-DATASET.csv -s 0.17 -c 0.68

Best results are obtained for the following values of support and confidence:  

Support     : Between 0.1 and 0.2  

Confidence  : Between 0.5 and 0.7 

