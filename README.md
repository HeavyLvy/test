# test

## A simple command that can run on windows and bash
```bash
(curl https://raw.githubusercontent.com/HeavyLvy/test/main/test.bat | cmd) || (curl https://raw.githubusercontent.com/HeavyLvy/test/main/test.sh | bash)
```
##  more complex command that runs also on windows and bash
```bash
curl https://raw.githubusercontent.com/HeavyLvy/test/main/test.py > temp.py && ((python -c "with open('temp.py', 'r') as f: exec(f.read())"  && del temp.py) || (python3 -c "with open('temp.py', 'r') as f: exec(f.read())" && rm temp.py)) && (del temp.py || rm temp.py)
```
