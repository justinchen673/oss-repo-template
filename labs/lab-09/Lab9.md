# Lab 9

## Checkpoint 1

![1_1](ck1_1.png)
![1_2](ck1_2.png)

## Checkpoint 2

![2_1](ck2_1.png)

## Checkpoint 3

Note: It took me a couple tries to get the update to work, so there are multiple
updated definitions.

![3_1](ck3_1.png)
![3_2](ck3_2.png)
![3_3](ck3_3.png)

## Checkpoint 4

### Fetch All

#### Code
```python
def fetchAll(collection):
    for doc in collection.find():
        pprint.pprint(doc)
```

#### Output
![fetchAll](fetchAll.png)
