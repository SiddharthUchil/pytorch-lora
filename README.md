# LoRA: Low-Rank Adaptation of Large Language Models

LoRA reduces the number of trainable parameters by learning pairs of rank-decompostion matrices while freezing the original weights.
This vastly reduces the storage requirement for large language models adapted to specific tasks and enables efficient task-switching during deployment all without introducing inference latency.
LoRA also outperforms several other adaptation methods including adapter, prefix-tuning, and fine-tuning.
