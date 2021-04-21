# Recognizance-Prastuti'21

**Recognizance** is a two Round Machine Learning Competition Organised by the Department of Electrical Engineering IIT BHU(Varanasi) in their Annual Fest Prastuti. 

This year the Competition includes

 - **Round1** - To perdict frauds in electricity bill, More Details - [Here](https://www.kaggle.com/c/recognizance-1)
 - **Round2** - To Detect the images containing the power lines from set of given visible and infrared images. - [Here](https://www.kaggle.com/c/recognizance-2)

## Summary of Our Approach

### ROUND1

- Used Feature Aggregation on invoice data
- Used Optuna for Hyperparameter tuning
- Used LGBM Classifier

### ROUND2

- Used Preprocessing Using IMAGE DATA GENERATOR
- Trained Deep learning model using stratified KFold
- Finally Used Post processing to increase accuracy from **0.9829 to 0.9895**

For more info check codes [Round1](recognizance-round1.ipynb) [Round2](recognizance-round-2.ipynb)


## References

 - [Best notebook to start](https://www.kaggle.com/yassineghouzam/titanic-top-4-with-ensemble-modeling)
 - [Optuna Tuning](https://towardsdatascience.com/how-to-make-your-model-awesome-with-optuna-b56d490368af)
 - [LGBM](https://medium.com/@pushkarmandot/https-medium-com-pushkarmandot-what-is-lightgbm-how-to-implement-it-how-to-fine-tune-the-parameters-60347819b7fc)
 - [Aggreation and Magic Features](https://www.kaggle.com/cdeotte/xgb-fraud-with-magic-0-9600) (**Credits - Chris Deotte**)
  
## :sparkles: Achievement

**We got 3rd position in Round1, 2nd position in Round2 and overall 2nd position in the event while applying these approaches**


## **Team - CREATORZ** :sparkles::sparkles:

<table>
   <td align="center">
      <a href="https://github.com/monako2001">
         <img src="https://avatars2.githubusercontent.com/u/56964886?s=400&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Mainak Samanta</b>
         </sub>
      </a>
      <br />
   </td>
   <td align="center">
      <a href="https://github.com/Amshra267">
         <img src="https://avatars1.githubusercontent.com/u/60649720?s=460&u=9ea334300de5e3e7586af294904f4f76c24f5424&v=4" width="100px;" alt=""/>
         <br />
         <sub>
            <b>Aman Mishra</b>
      </a>
      <br />
   </td>
</table>
