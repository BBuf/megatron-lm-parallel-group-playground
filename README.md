> 我也维护了一个cuda以及LLM学习仓库 https://github.com/BBuf/how-to-optim-algorithm-in-cuda , 有需要的小伙伴可以**点一点star**

## Megatron-LM Parallel Group Playground

This is a playground for parallelism group display in Megatron-LM.

### 1. requirements

- gradio>=4.16.0

### 2. deploy

```python
python3 app.py
```

then open the link created by gradio.


You can also visit [huggingface space link]( https://huggingface.co/spaces/BBuf/megatron-lm-parallel-group-playground) .

### 3. display example

![图片](https://github.com/BBuf/megatron-lm-parallel-group-playground/assets/35585791/2804c4db-37a2-4575-a8bb-409dd19d961f)


## Plan
- [x] 2D Parallelism Group support (DP+TP, DP+PP)
- [x] 3D Parallelism Group support (DP+TP+PP)
- [x] 3D Parallelism Group support (CP+DP, CP+TP, CP+PP, CP+TP+PP)
- [ ] Zero
- [ ] Collective Communication Display

contributions and issues are welcome.

## Reference

- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM)
- [gradio](https://github.com/gradio-app/gradio)

