# LORA

* 先找出大約10至20張訓練照片
* 對照片做預處理(裁切和產生提示詞文本)
    * 利用 [BIRME](https://www.birme.net/?target_width=512&target_height=512) 裁切
    * 利用 stable diffusion webui 產生文本
* 將資料集上傳至google drive
* 打開下列[網址](https://colab.research.google.com/github/hollowstrawberry/kohya-colab/blob/main/Lora_Trainer.ipynb)將參數設定好即可開始訓練LORA模型
* 再將模型結果放至stable-diffusion-webui的models/Lora目錄中，就可利用模型產生圖片

參考網址：[Stable Diffusion -- 訓練LoRA](https://vocus.cc/article/642db062fd897800014596ad)