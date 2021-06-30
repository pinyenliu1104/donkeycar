# donkeycar: Final exam for ML

### Get driving.
After building a Donkey you can turn on your car and go to http://localhost:8887 to drive.

### How to use this function.
Create a car
```python
donkey createcar --path ~/yourcarname
```
If you want to use our car, you need to:
```python
cd <path to our car>/finalcar
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
#### Our dataset
https://drive.google.com/file/d/1Hprn8L35qctdmGpRkIB8pNrgtTbJWjMk/view?usp=sharing

#### Our dataset movie
https://drive.google.com/file/d/11B0VQQKeMASIE-ECoQUfKE0HjSg8YcS7/view?usp=sharing

