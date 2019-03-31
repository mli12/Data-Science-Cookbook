> Written with [StackEdit](https://stackedit.io/).
# Atom Notes

### How to use Anaconda environment with Atom

First install Anaconda. During the Anaconda installation click on the option "Add Anaconda to my PATH environment variable:

![](https://cdn-images-1.medium.com/max/640/1*7a9zVyGP3iMXu9aB4e_Vhw.png)

Now install Atom. Atom will open, close it. Then install the Atom package  `platformio-ide-terminal`. To do that, open windows CMD console as administrator. Then write:
```
$ apm install platform-ide-terminal
```
Now open Atom. But, to make Atom works with Anaconda, you need to open Atom through the Anaconda propm using:

```
$ atom --new-instance
```

If you have an Anaconda virtual environment, In your Anaconda terminal, activate your Conda environment and then run `atom --new-instance`.

Now create a `test.py` file like that using Atom:
```python
print("Hello Word!")
```
Now open a terminal inside Atom using `platformio-ide-terminal`. The Windows CMD terminal will open. To run the `test.py` using the Windows terminal just write `ipyth 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MjE2NDk0MDJdfQ==
-->