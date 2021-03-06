# Monero-X v0.1.0 <sup>`alpha`</sup>

**Monero-X** is a Monero Github trunk Hardfork with different Genesis aimed to enable **Smart Contracts** to port them back to Monero and all other forks after all dev cycles finished.

Another approach is adopting Monero engine to be true `Data Driven` instead of Monero maintainers vision:

> https://github.com/monero-project/monero/issues/4343

And this is only one rejected issue of many.

Total Supply is limited to 180M and **size limits are doubled**. This is **highly experimental currency** supposed to use to test and debug independent Smart Contracts implementation based on **Python3** interpreter as Contracts Language and `pyledger` with `monero-python` libraries as contracts runtime.

## Building Requirements

In Monero-X outdated scheme of dependencies handling (putting code to `external` folder) is changed to using system
libraries search. Almost everything git submodules are removed. You will need following libraries to build Monero-X:

### Mac OS X

```bash
brew install rapidjson unbound miniupnp readline
```

### Ubuntu

```bash
sudo apt install rapidjson-dev libreadline-dev
```

## Building process

Project builds with CLang already available in OSX:

```bash
./build.sh
```

Sample output:

```bash
-- The C compiler identification is AppleClang 9.1.0.9020039
-- The CXX compiler identification is AppleClang 9.1.0.9020039
```

## mr X

![mr. X](./mrx.png)

## Copyrights

- 2018 &copy; The Monero-X Project.
- 2014-2018 &copy; The Monero Project.   
- 2012-2013 &copy; The Cryptonote developers.
