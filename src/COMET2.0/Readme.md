# Acknowledgement: 

This code is highly motivated from original COMET: https://github.com/atcbosselut/comet-commonsense and mostly same as original repo expect 
now it has GPT-2 instead of GPT. 

Run:
```
python scripts/data/make_atomic_data_loader.py
python src/main.py --experiment_type atomic --experiment_num #
python scripts/evaluate/evaluate_atomic_generation_model.py --split $DATASET_SPLIT --model_name /path/to/model/file
```
We  use  commonsense  transformer(COMET2.0,Bosselut et al. (2019)) to extract social commonsense knowledge about the extractedevents. 
COMET2.0 is trained on the ATOMIC (Sapet al., 2019) inferential knowledge resource whichconsists of 877K everyday events, each character-ized by nine relation types (xIntent, xNeed, xReact,etc.) which we call dimensions. 
