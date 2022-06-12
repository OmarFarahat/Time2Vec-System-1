Requirements are in file requirements.txt
All dependencies are in environment.yml

To download dataset:
python data_prep.py --download --mel

To train base model:
python training_system1.py --gpu 1 --seed 1

To train model 2 with gradient centralization technique:
python training_model_gc.py --gpu 1 --seed 1

To train model 3 with increase in cnn layers as relu as an activation function:
python training_model3_cnn_relu.py --gpu 1 --seed 1

Outputs obtained are in folder Output Files
