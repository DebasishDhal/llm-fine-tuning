TRAIN_DATASET = "KisanVaani/agriculture-qa-english-only" #https://huggingface.co/datasets/KisanVaani/agriculture-qa-english-only
Benchmark dataset = "bharatgenai/BhashaBench-Krishi" #https://huggingface.co/datasets/bharatgenai/BhashaBench-Krishi

Training runs - https://wandb.ai/debasishdhal/AgriFineTuningDemo-Sep2026/runs (private for now, wandb is making it impossible to make it public view)

Didn't work as expected, base model results = 39%, ft model results = 33% (reason is most likely the 4-bit quantization)
