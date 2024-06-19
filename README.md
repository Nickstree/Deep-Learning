Deep Learning homework 2
===

先將原始資料images的資料夾包成一個images.pickle的檔案，將其放在HW2此處的images底下，便可以執行。

* Q1_model
    * 尋找Q1的baseline參數，此處train, validation, test皆為3 channels
* Q1_model_diff_ch
    * 使用Q1_model，train為3 channels，其餘validation和test為r隨機選擇channels
    * 在第一層Layer分別有使用正常的kernel和依channels數加權的kernel，作為不同種baseline
* Q1_model_diff_ch_reweight
    * 使用Q1_model，train為3 channels，其餘validation和test為r隨機選擇channels
    * 在第一層Layer使用自行設計的CustomConv作為特徵提取器，為本題自行設計的model
* Q2_model
    * Baseline的ResNet34使用各種參數
* Q2_modelQ2_model_less_layers
    * 本題自行設計的model
