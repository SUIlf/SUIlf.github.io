---
author: Navdeep Kaur
title: "Boston Housing Prices: Regression"
permalink: /datasets/boston-housing/
date: 2018-02-26
excerpt: "Using regression to predict housing values in Boston suburbs."
---

### Overview

This dataset concerns housing values in Boston suburbs. It's based on the "[Boston Housing Dataset](https://archive.ics.uci.edu/ml/datasets/Housing)" from _University of California, Irvine_, which in turn was taken from the StatLib library maintained at _Carnegie Mellon University_.

The target is `medv`: median value of owner-occupied homes in terms of thousands of dollars ($1000s).

Features:

1. `crim`: per-capita crime rate by town.
2. `zn`: proportion of residential land zoned for lots over 25,000 sq.ft.
3. `indus`: proportion of non-retail business acres per town.
4. `chas`: Charles River dummy variable (=1 if tract bounds river; 0 otherwise)
5. `nox`: nitric oxides concentration (parts per 10 million)
6. `rm`: average number of rooms per dwelling.
7. `age`: proportion of owner-occupied units built prior to 1940.
8. `dis`: weighted distances to five Boston employment centres.
9. `rad`: index of accessibility to radial highways.
10. `tax`: full-value property-tax rate per $10,000.
11. `ptratio`: pupil-teacher ratio by town.
12. `b`: 1000(Bk-0.63)^2 where Bk is the proportion of black people by town.
13. `lsat`: percent lower status of the population.
14. `medv`: median value of owner-occupied homes in terms of thousands of dollars ($1000s).

---

### Download

Download: [Boston-Housing.zip](https://github.com/boost-starai/BoostSRL-Misc/blob/master/Datasets/Boston-Housing/Boston-Housing.zip?raw=true) (19 KB)

* `md5sum`:
  <p style="word-break: break-all;">5306de665616e7d76e98ea8d98ffd4b2</p>

* `sha256sum`:
  <p style="word-break: break-all;">e029e7695a87910c26861180d77c95db306ccbc01c0decfacedbf91e38c077c5</p>

---

### Setup


1. After downloading, unzip Boston-Housing.zip

    `unzip Boston-Housing.zip`

2. If you're using a jar file, move it into the Boston-Housing directory:
    `mv (BoostSRL jar file) Boston-Housing/`  
    `mv (auc jar file) Boston-Housing/`

3. For learning/inference, full explanations are available on the ["Regression Tutorial"](https://github.com/boost-starai/BoostSRL/wiki/Regression). Commands are also listed below.

  * Learning:  

`java -cp BoostSRL.jar edu.wisc.cs.will.Boosting.Regression.RunBoostedRegressionTrees -reg -l -train train/ -target medv -trees 20`

  * Inference:  

`java -cp BoostSRL.jar edu.wisc.cs.will.Boosting.Regression.RunBoostedRegressionTrees -i -test test/ -aucJarPath . -target medv -model train/models/ -trees 20`

---

### Modes

Notice that since the values have been discretized, we can treat the values as constants and therefore we can use an octothorpe (#) in the modes file.

```text
mode: crim(+id,#varsrim).
mode: zn(+id,#varzn).
mode: indus(+id,#varindus).
mode: chas(+id,#varchas).
mode: nox(+id,#varnox).
mode: rm(+id,#varrm).
mode: age(+id,#varage).
mode: dis(+id,#vardis).
mode: rad(+id,#varrad).
mode: tax(+id,#vartax).
mode: ptratio(+id,#varptrat).
mode: b(+id,#varb).
mode: lstat(+id,#varlstat).
mode: medv(+id).
```
