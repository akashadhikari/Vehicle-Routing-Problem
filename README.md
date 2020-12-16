## Vehicle Routing Problem
A Travelling Salesman Problem for multiple delivery points. 


## Installation
Create a virtual environment and install the requirements  

```
pip install -r requirements.txt
```

Copy .env_example inside `src/` directory and rename it to `env.py `.

```
cp .env_example src/
cd src
mv .env_example env.py
```

Include your own `API_KEY` inside `env.py`  

Run the files. Example:  
```
python3 cvrp.py
```

## Contains
Inside `src/`  
- `vrp.py` : Vehicle Routing Problem
- `cvrp.py`: Capacity Constrains
- `pickup_del.py`: Pickups and Deliveries

