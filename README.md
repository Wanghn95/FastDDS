# FastDDS

Learning with FastDDS, Go Go Go！

**Updates July 31 2022** ： I'll keep updating the repository.  
# Envirment：

* The required environment of the code.

## Envirment in x86

## Envirment in arrch64

## Using in X86
* Cmake

## Using in arrch64


## Requirements
* Python 3.6

### Download the processed data link：
#### [Pre-processed data](https://drive.google.com/open?id=1DN7ClZCCXsk2KegmC6t4ClBwtAf5galI)

#### 1> Download Stories

### 2.Validate by ROUGE:
```
python train.py -task hybrid -mode validate -batch_size 15000 --hybrid_loss -control Rel -test_batch_size 15000 -data_path DATA_PATH -log_file LOG_PATH -model_path MODEL_PATH -sep_optim true -use_interval true -visible_gpus 2 -max_pos 512 -max_length 200 -alpha 0.95 -min_length 50 -result_path RESULT_PATH -test_all 
```
* You can choose the `-test_all` parameter, the system'll load all checkpoints and select the top ones to generate summaries, IF you have enough time.












