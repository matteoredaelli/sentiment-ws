# sentiment-ws
Sentiment analysis via REST

COPYRIGHT (c) 2015  - matteo DOT redaelli AT gmail DOT com

## Requirements

https://github.com/livioivil/TextWiller

```R
library(devtools)
install_github("TextWiller", "livioivil")
library(TextWiller)
```

## Usage

git clone https://github.com/matteoredaelli/sentiment-ws

cd sentiment-ws
Rscript sent-ws.R

Open a browser and test it with

 http://localhost:8000/sent?text=mi%20piace%20leggere

