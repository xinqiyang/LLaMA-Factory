# 执行流程

执行模型的流程

jupyterlab 

```bash
docker compose -f docker/docker-cuda-jupyter/docker-compose.yml up -d
API_PORT=8000 llamafactory-cli api examples/inference/phi3_vllm.yaml
```


```bash
docker compose -f docker/docker-cuda/docker-compose.yml up -d 
API_PORT=8000 llamafactory-cli api examples/inference/phi3_vllm.yaml
```

