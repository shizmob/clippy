clippy
======
Easy Python clipboard management.
---------------------------------


### copy to
```python
>>> clip.set(u'nice meme')    # accepts unicode or str
```

### get from
```python
>>> clip.get()                # returns unicode or None
u'nice meme'
```

### clear
```python
>>> clip.clear()
>>> clip.get()
None
```

### self-test
```sh
$ python -m clip
testing ASCII... success
testing Unicode... success
testing clear... success
```

License
-------
Do What the Fuck You Want to Public License.
