# ThaiCrimeNER
 
- This project is the part of the CAMELON - CRIME AND ACCIDENT MONITORING ANDESTIMATION FROM LARGE-SCALE ONLINE NEWS. 
- The objective is to extract the information from Online News

### Data that use in this project is from 
- https://github.com/sorrapoln/ner-th-crime-news


### **Classification_report**
```
                   precision   recall   f1-score   support

       B-COLOR      0.408     0.635     0.497        63
       I-COLOR      0.308     0.596     0.406        47
        B-DATE      0.976     0.941     0.958       340
        I-DATE      0.983     0.952     0.967       475
    B-LOCATION      0.876     0.799     0.836      1038
    I-LOCATION      0.880     0.694     0.776      1310
          B-LP      0.615     0.508     0.557        63
          I-LP      0.531     0.589     0.559       129
      B-OBJECT      0.676     0.481     0.562       104
      I-OBJECT      0.552     0.577     0.564       137
B-ORGANIZATION      0.728     0.725     0.726       498
I-ORGANIZATION      0.568     0.599     0.583       735
      B-PERSON      0.562     0.958     0.709      1294
      I-PERSON      0.375     0.944     0.536      3201
        B-TIME      0.976     0.981     0.979       374
        I-TIME      0.972     0.985     0.979       394
     B-VEHICLE      0.631     0.754     0.687       195
     I-VEHICLE      0.841     0.804     0.822       276
      B-WEAPON      0.667     0.376     0.481       117
      I-WEAPON      0.887     0.412     0.562       153

     micro avg      0.558     0.832     0.668     10943
     macro avg      0.701     0.715     0.687     10943
  weighted avg      0.656     0.832     0.698     10943
  ```
