# _Asilidae_

## What is Asilidae?

Hi!

This is Asilidae. It's a bash (unix shell) encrypted, mutant and polymorphic virus that can infect bash files in the same working directory where it is located. The code in each generation changes more than 80 percent.

# But...why?

I am passionate about computer virus and similar codes that perform some biological-like behaviour. Many people have never seen a virus working and this an educational example of virus that you can test easily and safely in your computer if you want to see a virus working. It tries to emulate those polymorphic/encrypted viruses that were created in the 90s that still amaze me.

## Does it work?

Yes, it does. It was tested on MX Linux and Lubuntu and it works perfectly.

## Is it safe to test?

There is no payload so you can test it safely. Anyway remember that this is a relf-replicating code so any bug becomes an interesting a brand-new feature.

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
    
## Hey, wouldn't it be better if you <put your advice, suggestion, whatever...here>?

I know i can improve the code a lot in many ways. This won't be the last version of this code and I will be pleased to read your suggestions in order to improve it.

Thank you very much for your attention.


