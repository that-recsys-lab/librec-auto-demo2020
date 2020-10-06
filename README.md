# librec-auto-demo2020
Data and configuration files for the [demo at RecSys 2020](https://dl.acm.org/doi/10.1145/3383313.3411525).

## Installing librec-auto

You will need to install [librec-auto](https://github.com/that-recsys-lab/librec-auto) in order to run this example.

### Installing via pip

```
pip install librec-auto
```

### Installing from source

```
git clone https://github.com/that-recsys-lab/librec-auto.git
cd librec-auto
python setup.py develop
```

## Running an example

Clone this repository:

```
git clone https://github.com/that-recsys-lab/librec-auto-demo2020.git
```

You can run a basic matrix factorization recommender over a movie ratings data set using the following command:

```
python -m librec_auto -t librec-auto-demo2020/demo01 run
```

(Python 3.7+ is required.)

The configuration file for the above study is located at:

```
librec-auto-demo2020/demo02/config/config.xml
```

The `-c` command line parameter allows other configuration files to be selected.
