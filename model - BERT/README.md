原本有把BERT model轉成tflite的code，但因為硬體問題，在轉的過程中notebook皆crash掉，
所以轉tflite的code還不確定是否正確。使用tflite的code為github上找到的。加速棒為Google
的Coral。

在使用 TFLite 模型進行推理之前，你需要以下步驟：

1. 載入 TFLite 模型：將 TFLite 模型從文件中載入到記憶體中。
2. 創建解譯器（interpreter）：建立 TFLite 模型的解譯器，用於執行推理操作。
3. 分配張量：為輸入和輸出張量分配內存空間。