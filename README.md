# donkeycar: Final exam for ML

### Get driving.
After building a Donkey2 you can turn on your car and go to http://localhost:8887 to drive.

### How to use this function.
Create a car
```python
donkey createcar --path ~/yourcarname
```
Drive car
```python
python manage.py drive
```
Train model
```python
python train.py --tub=<your path to tubs> --model models/<your model> --type=(linear/categorical/inferred/imu/memory/behavior/localizer/rnn/3d)
```
Autopilot
```python
python manage.py drive --model models/<your model>
```

