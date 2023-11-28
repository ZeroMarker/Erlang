# Erlang


```sh
sudo apt-get install erlang-ic
erlc helloworld.erl

$ ls
helloworld.beam  helloworld.erl

erl -noshell -s helloworld start -s init stop
```

***

```sh
erlc hello.erl
# hello.beam

erl>

c(hello).

hello:start().

halt().
```
