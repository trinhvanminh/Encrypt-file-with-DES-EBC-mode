# DES EBC mode



```python 1712601.py -i <filename> -k <key: 8 bytes> -m <mode: e/d>```

For example:
```
python 1712601.py -i a.txt -k 11111111 -m e
```
And the result was a encrypted file

> return a.txt.enc

	python 1712601.py -i a.txt.enc -k 11111111 -m d
    
The plantext file:
> return a.txt
