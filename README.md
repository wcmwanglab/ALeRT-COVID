 
The package contains the data and code to implement ALerT-COVID and the compare models in the paper "ALeRT-COVID: Attentive Lockdown-awaRe Transfer learning for predicting COVID-19 pandemics in different countries" .



-----------------------------------  

### Description of the code
•	modelA.ipynb: code for building and evaluating model A;
(without transfer: sing only the previous cumulative CCPM (confirmed cases per million people) as the predictor and training it directly on each country without transfer learning;)

•	ModelB.ipynb: code for building and evaluating model B;
(transfer: using only the previous cumulative CCPM as predictor and fine tune the transferred source model)

•	ModelC.ipynb: code for building and evaluating model C;
(transfer+lockdown: add the lockdown measure as an additional predictor for model B)

•	ALeRT-COVID.ipynb: code for building and evaluating ALeRT-COVID;
(transfer+lockdown+attention: add the attention mechanism for model C)


  
### Description of the data
--- source: the processed data sets of source countries or areas
--- target: the processed data sets of five target countries


### "model" folder: the pkl file of the constructed source models of model B,C and ALeRT-COVID, which utilize the transfer learning.


### "result" folder: 
--- result.xlsx: the mape results we obtained by running the jupyter notebook.

