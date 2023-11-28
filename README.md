# Erlang

[Erlang Hello World Example](https://www.thegeekstuff.com/2010/05/erlang-hello-world-example/)

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
