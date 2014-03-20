clippy
======
Easy Python clipboard management.
---------------------------------


### copy to
```python
>>> clip.set('nice meme')     # accepts unicode/str/bytes
```

### get from
```python
>>> clip.get()                # returns unicode string or None
'nice meme'
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
