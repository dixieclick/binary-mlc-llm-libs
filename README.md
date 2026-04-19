# binary-mlc-llm-libs (dixieclick fork)

Compiled MLC-LLM model library binaries for the dixieclick fork of
mlc-ai/web-llm + mlc-ai/mlc-llm. Mirrors the layout of
[mlc-ai/binary-mlc-llm-libs](https://github.com/mlc-ai/binary-mlc-llm-libs).

Filename format:
```
{model_name}-{quantization}-{metadata}-{platform}.{suffix}
```

Metadata tokens:
- `ctx`: context window size
- `sw`: sliding window size
- `cs`: prefill chunk size

