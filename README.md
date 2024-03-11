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

![图片](https://github.com/BBuf/megatron-lm-parallel-group-playground/assets/35585791/2475ed38-8931-4a3b-82d8-eff92f2d7497)


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

