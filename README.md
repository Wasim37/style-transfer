Github:
https://github.com/Wasim37/fast-style-transfer

参数文档
https://github.com/lengstrom/fast-style-transfer/blob/master/docs.md#stylepy

Benchmark 一般是行业标准

evaluate.py执行生成命令
"--checkpoint ./model/la_muse.ckpt --in-path ./examples/content/dog.jpg --out-path ./"

style.py执行生成命令
"--checkpoint-dir ./model/ --style ./style/wave.jpg"