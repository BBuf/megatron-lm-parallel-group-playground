## Megatron-LM Parallel Group Playground

This is a playground for parallelism group display in Megatron-LM.

### 1. requirements

- gradio>=4.16.0

### 2. deploy

```python
python3 playground.py
```

then open the link created by gradio.


You can also try [this](https://f1afaf41093e453206.gradio.live) temporary link.

### 3. display example

![图片](https://github.com/CC-LLM/megatron-lm/assets/35585791/32a22470-8b5e-44c2-aa42-896effa424b1)


## Plan
- [x] 2D Parallelism Group support (DP+TP, DP+PP)
- [x] 3D Parallelism Group support (DP+TP+PP)
- [ ] Zero
- [ ] Collective Communication Display

contributions and issues are welcome.

## Reference

- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM)
- [gradio](https://github.com/gradio-app/gradio)

