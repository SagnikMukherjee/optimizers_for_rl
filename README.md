* Preprocess data with 1. examples/data_preprocess/numinamath.py (trainset) and 2. examples/data_preprocess/math_dataset.py (testset)
* train with examples/grpo_trainer/run_qwen2-7b_math.sh
* The optimizer is currently hardcoded (sry) in verl/workers/fsdp_workers.py (switch out both actor and critic's optimizers)
