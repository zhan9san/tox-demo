# tox-demo

Tox demo

## 获取源代码

```shell
mkdir ~/test
cd ~/test
git clone https://github.com/zhan9san/tox-demo
```

## 切换到tox基础章节

```shell
cd tox-demo
git checkout 1-base
```

安装tox

```shell
python3.9 -m pip install tox
```

运行tox

```shell
$ tox
GLOB sdist-make: /Users/jackzhang/src/github/tox-demo/setup.py
py39 inst-nodeps: /Users/jackzhang/src/github/tox-demo/.tox/.tmp/package/1/tox-demo-0.0.1.zip
py39 installed: attrs==21.4.0,iniconfig==1.1.1,packaging==21.3,pluggy==1.0.0,py==1.11.0,pyparsing==3.0.8,pytest==7.1.1,tomli==2.0.1,tox-demo @ file:///Users/jackzhang/src/github/tox-demo/.tox/.tmp/package/1/tox-demo-0.0.1.zip
py39 run-test-pre: PYTHONHASHSEED='1553718969'
py39 run-test: commands[0] | pytest
====================================================================== test session starts ======================================================================
platform darwin -- Python 3.9.12, pytest-7.1.1, pluggy-1.0.0
cachedir: .tox/py39/.pytest_cache
rootdir: /Users/jackzhang/src/github/tox-demo
collected 1 item                                                                                                                                                

tests/test_sample.py .                                                                                                                                    [100%]

======================================================================= 1 passed in 0.01s =======================================================================
____________________________________________________________________________ summary ____________________________________________________________________________
  py39: commands succeeded
  congratulations :)
```
