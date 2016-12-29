# SSTMCSPGAAS - Stupidly Simple Tiny Minimal Coming Soon Page Generator As A Service

> "Create a website!" - My brain on bash.

## About

CSPAAS is a coming soon page generator that weighs in at 7kb and produces an html file of 7-8kb complete with simple meta tags, space for title and message, a countdown timer and social media links.

![alt text](https://raw.githubusercontent.com/impshum/SSTMCSPGAAS/examples/screenshot.jpg "The end result")

![alt text](https://raw.githubusercontent.com/impshum/SSTMCSPGAAS/examples/example.gif "Here we go")

##### What's good about it then?

* Ridiculously easy to use.
* Less than a minute average.
* No jQuery.
* Blazing fast.
* HTML5 valid.
* CSS3 Animations.
* Doesn't eat the cat.

## Requirements

* Curl
* A need for a coming soon page

## Usage

Simply pop this is your terminal and follow the prompts.
```
bash <(curl -s -L https://git.io/sstmcspgaas)
```

## Recommended Usage

Just to make it even more stupidly easy we'll create an alias so all you'll have to type is 3 letters to initiate the script. Feel free to edit your alias to your needs or just stick with the mighty "csp".

### OSX

```
sudo nano ~/.bash_profile
```
Add this to the bottom.
```
alias csp='bash <(curl -s -L https://git.io/sstmcspgaas)'
```
And refresh
```
source ~/.bash_profile
```
Then run it.
```
csp
```

### Linux

```
sudo nano ~/.bashrc
```
Add this to the bottom.
```
alias csp='bash <(curl -s -L https://git.io/sstmcspgaas)'
```
And refresh
```
source ~/.bashrc
```
Then run it.
```
csp
```

### Windows

I'll get round to this. I think it's called doskey, registry edit and a .bat file somewhere. Eugh!

## Contributing

Suggestions are more than welcome. Create an issue up top and label it "Feature Request".
Or you can get your fork out and dig in.
