# donkeycar: Final exam for ML
### Get ready to use donkey
First, you need to download this file in your computer. Then:
```python
cd <path to this file>/donkeycar
git checkout master
```
Create the Python anaconda environment
```python
conda env create -f install\envs\windows.yml
conda activate donkey
pip install --user tensorflow
pip install -e .[pc]
```
Then you need to download gym-donkeycar for simulator: 
https://docs.donkeycar.com/guide/simulator/

### Get driving.
After building a Donkey car, you can turn on your car and go to http://localhost:8887 to drive.

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
The green line in this video represents throttle and steering\
https://drive.google.com/file/d/11B0VQQKeMASIE-ECoQUfKE0HjSg8YcS7/view?usp=sharing

