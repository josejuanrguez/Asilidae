# _Asilidae_

## What is Asilidae?

Hi!

This is Asilidae. It's a bash (unix shell) encrypted, mutant and polymorphic virus that can infect bash files in the same working directory where it is located. The code in each generation changes more than 80 percent.

## Does it work?

Yes, it does. It was tested on MX Linux and Lubuntu and it works perfectly.

## Is it safe to test?

There is no payload so you can test it safely. Anyway remember that this is a relf-replicant code so any bug becomes an interesting a brand-new feature.

## Dependency

It uses standard Linux tools like cat, sed, head, tail and openssl so they have to be installed in your system if you want to see the virus working.

## Testing the mutation engine.

Let's create two simple identical bait files. We will call them "hello1" and "hello2".

``` js
#!/bin/bash
echo "Hello World!"
```

We proceed to infect them and check for the diferences between them:

```
$ diffpercent hello1 hello2
hello1 hello2 81.97
```
As you can see, from two identical files we get two files with the same size that differs in a 81.97% before the infection. 
    
