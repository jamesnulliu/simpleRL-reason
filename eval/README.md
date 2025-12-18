### Requirements
You can install the required packages with the following command:
```bash
pip install -r requirements.txt 
pip install -e . vllm==0.11.0 flash-attn==2.7.3 --no-build-isolation
```

### Evaluation
```
bash sh/run.sh
```

## Acknowledgement
The codebase is adapted from [math-evaluation-harness](https://github.com/ZubinGou/math-evaluation-harness).
