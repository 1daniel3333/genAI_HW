---
base_model: TinyLlama/TinyLlama-1.1B-Chat-v1.0
library_name: peft
---
Source:
程式碼來源: https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php

Get information from https://speech.ee.ntu.edu.tw/~hylee/genai/2024-spring.php

再做對應修改

課程:
https://www.youtube.com/playlist?list=PLJV_el3uVTsPz6CTopeRp2L2t4aL_KgiI

生成式AI導論2024

當git clone 之後
記得在root 創一個檔名為 "cred.py' 的檔案
裡面貼上以下

keys = {
  'GEMINI_API_KEY': '這裡放入你的API Key',
}
### Framework versions

- PEFT 0.15.2