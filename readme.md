# A python interpreter for [Brainfuck](https://pt.wikipedia.org/wiki/Brainfuck)

If you don't know Brainfuck, please check [this video from Fireship](https://www.youtube.com/watch?v=hdHjjBS4cs8) and check [this gist](https://gist.github.com/roachhd/dce54bec8ba55fb17d3a).

This project is based on a compiler made with Java that you can see [here](https://www.geeksforgeeks.org/brainfuck-interpreter-java/)

## how to use

```bash
chmod +x interpreter 
```

write a .bf file, like this

```
> test.bf

>+++++++++[<++++++++>-]<.>+++++++[<++++>-]<+.+++++++..+++.[-]>++++++++[<++++>-] <.>+++++++++++[<++++++++>-]<-.--------.+++.------.--------.[-]>++++++++[<++++>- ]<+.[-]++++++++++.
```

and run 
```bash
./interpreter file.bf
```




