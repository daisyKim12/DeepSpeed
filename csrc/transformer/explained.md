## Content
- inference
    - csrc
        - gelu
        - layer_norm
        - pointwise_ops
        - relu
        - softmax: softmax하는 커널
        - transform: qkv에 특정 Bias를 더하고 rotate 시키는 커널
    - includes: header file
- cublas_wrappers
- dropout_kernels
- gelu_kernels
- general_kernels
- normalize_kernels
- softmax_kernels: fused attention and softmax 근데 곱셈 없음 그냥 qkv에 softmax 하는 듯
- transform_kernels